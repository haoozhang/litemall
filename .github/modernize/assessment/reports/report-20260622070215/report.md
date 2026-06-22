# litemall

## Summary

| Metric | Value |
|--------|-------|
| Total Issues | 173 |
| Mandatory Blockers | 157 |
| Potential Issues | 9 |

## Component Information

| Property | Value |
|----------|-------|
| Language | Java, JavaScript, Dockerfile |
| Frameworks | Spring Boot, Spring, Vue |
| Build tools | Maven, NodeJs |
| JDK version | 1.8 |

## Cloud Readiness Issues

| Issue Name | Criticality | Story Points | Occurrences |
|------------|-------------|--------------|-------------|
| Avoid File System Logging in Configuration | Mandatory | 1 | [14](#Avoid_File_System_Logging_in_Configuration) |
| Use of unsecured network protocols or URI libraries | Mandatory | 3 | [10](#Use_of_unsecured_network_protocols_or_URI_libraries) |
| CRA: Hard-coded credentials in configuration files | Mandatory | 5 | [6](#CRA_Hard-coded_credentials_in_configuration_files) |
| CRA: Use of insecure random number generator java.util.Random | Mandatory | 5 | [5](#CRA_Use_of_insecure_random_number_generator_java_util_Random) |
| CRA: Default or well-known password detected | Mandatory | 3 | [3](#CRA_Default_or_well-known_password_detected) |
| CRA: Hard-coded password in Java source code | Mandatory | 8 | [2](#CRA_Hard-coded_password_in_Java_source_code) |
| Local JDBC Calls | Mandatory | 5 | [1](#Local_JDBC_Calls) |
| CRA: Use of weak hash algorithm MD5 | Mandatory | 5 | [1](#CRA_Use_of_weak_hash_algorithm_MD5) |
| Hardcoded IP Address | Mandatory | 3 | [1](#Hardcoded_IP_Address) |
| Password found in configuration file | Potential | 3 | [6](#Password_found_in_configuration_file) |
| MySQL database found | Potential | 5 | [5](#MySQL_database_found) |
| Avoid using hardcoded URLs (HTTP protocol) in source code | Optional | 3 | [15](#Avoid_using_hardcoded_URLs_HTTP_protocol_in_source_code) |
| Localhost Usage | Optional | 3 | [1](#Localhost_Usage) |

### Issue Details

<details id="Avoid_File_System_Logging_in_Configuration">
<summary><b>Avoid File System Logging in Configuration</b> — affected files</summary>

- `litemall-all-war/src/main/resources/logback-spring.xml (line 16)`
- `litemall-all-war/src/main/resources/logback-spring.xml (line 17)`
- `litemall-all-war/src/main/resources/logback-spring.xml (line 23)`
- `litemall-all-war/src/main/resources/logback-spring.xml (line 28)`
- `litemall-all-war/src/main/resources/logback-spring.xml (line 29)`
- `litemall-all-war/src/main/resources/logback-spring.xml (line 35)`
- `litemall-all-war/src/main/resources/logback-spring.xml (line 48)`
- `litemall-all/src/main/resources/logback-spring.xml (line 16)`
- `litemall-all/src/main/resources/logback-spring.xml (line 17)`
- `litemall-all/src/main/resources/logback-spring.xml (line 23)`
- `litemall-all/src/main/resources/logback-spring.xml (line 28)`
- `litemall-all/src/main/resources/logback-spring.xml (line 29)`
- `litemall-all/src/main/resources/logback-spring.xml (line 35)`
- `litemall-all/src/main/resources/logback-spring.xml (line 48)`

</details>

<details id="Use_of_unsecured_network_protocols_or_URI_libraries">
<summary><b>Use of unsecured network protocols or URI libraries</b> — affected files</summary>

- `docker/litemall/application.yml (line 44)`
- `docker/litemall/application.yml (line 126)`
- `docker/litemall/application.yml (line 142)`
- `litemall-core/src/main/java/org/linlinjava/litemall/core/express/ExpressService.java (line 26)`
- `deploy/litemall/application.yml (line 44)`
- `deploy/litemall/application.yml (line 126)`
- `deploy/litemall/application.yml (line 142)`
- `litemall-core/src/main/resources/application-core.yml (line 8)`
- `litemall-core/src/main/resources/application-core.yml (line 94)`
- `litemall-core/src/main/resources/application-core.yml (line 110)`

</details>

<details id="CRA_Hard-coded_credentials_in_configuration_files">
<summary><b>CRA: Hard-coded credentials in configuration files</b> — affected files</summary>

- `deploy/litemall/application.yml (line 137)`
- `deploy/litemall/application.yml (line 144)`
- `docker/litemall/application.yml (line 137)`
- `docker/litemall/application.yml (line 144)`
- `litemall-core/src/main/resources/application-core.yml (line 105)`
- `litemall-core/src/main/resources/application-core.yml (line 112)`

</details>

<details id="CRA_Use_of_insecure_random_number_generator_java_util_Random">
<summary><b>CRA: Use of insecure random number generator java.util.Random</b> — affected files</summary>

- `litemall-db/src/main/java/org/linlinjava/litemall/db/service/LitemallOrderService.java (line 51)`
- `litemall-core/src/main/java/org/linlinjava/litemall/core/util/CharUtil.java (line 9)`
- `litemall-core/src/main/java/org/linlinjava/litemall/core/util/CharUtil.java (line 20)`
- `litemall-db/src/main/java/org/linlinjava/litemall/db/service/LitemallAftersaleService.java (line 77)`
- `litemall-db/src/main/java/org/linlinjava/litemall/db/service/LitemallCouponService.java (line 149)`

</details>

<details id="CRA_Default_or_well-known_password_detected">
<summary><b>CRA: Default or well-known password detected</b> — affected files</summary>

- `litemall-core/src/main/java/org/linlinjava/litemall/core/notify/config/NotifyProperties.java (line 67)`
- `litemall-db/src/main/java/org/linlinjava/litemall/db/domain/LitemallUser.java (line 247)`
- `litemall-db/src/main/java/org/linlinjava/litemall/db/domain/LitemallAdmin.java (line 183)`

</details>

<details id="CRA_Hard-coded_password_in_Java_source_code">
<summary><b>CRA: Hard-coded password in Java source code</b> — affected files</summary>

- `litemall-admin-api/src/test/java/org/linlinjava/litemall/admin/BcryptTest.java (line 16)`
- `litemall-admin-api/src/test/java/org/linlinjava/litemall/admin/BcryptTest.java (line 21)`

</details>

<details id="Local_JDBC_Calls">
<summary><b>Local JDBC Calls</b> — affected files</summary>

- `litemall-db/mybatis-generator/generatorConfig.xml (line 46)`

</details>

<details id="CRA_Use_of_weak_hash_algorithm_MD5">
<summary><b>CRA: Use of weak hash algorithm MD5</b> — affected files</summary>

- `litemall-core/src/main/java/org/linlinjava/litemall/core/express/ExpressService.java (line 112)`

</details>

<details id="Hardcoded_IP_Address">
<summary><b>Hardcoded IP Address</b> — affected files</summary>

- `litemall-core/src/main/java/org/linlinjava/litemall/core/util/IpUtil.java (line 29)`

</details>

<details id="Password_found_in_configuration_file">
<summary><b>Password found in configuration file</b> — affected files</summary>

- `deploy/litemall/application.yml (line 11)`
- `deploy/litemall/application.yml (line 56)`
- `docker/litemall/application.yml (line 11)`
- `docker/litemall/application.yml (line 56)`
- `litemall-core/src/main/resources/application-core.yml (line 24)`
- `litemall-db/src/main/resources/application-db.yml (line 13)`

</details>

<details id="MySQL_database_found">
<summary><b>MySQL database found</b> — affected files</summary>

- `litemall-db/mybatis-generator/generatorConfig.xml (line 46)`
- `litemall-db/src/main/resources/application-db.yml (line 10)`
- `deploy/litemall/application.yml (line 8)`
- `docker/litemall/application.yml (line 8)`

</details>

<details id="Avoid_using_hardcoded_URLs_HTTP_protocol_in_source_code">
<summary><b>Avoid using hardcoded URLs (HTTP protocol) in source code</b> — affected files</summary>

- `litemall-wx-api/src/main/java/org/linlinjava/litemall/wx/config/WxSwagger2Configuration.java (line 42)`
- `litemall-wx-api/src/main/java/org/linlinjava/litemall/wx/config/WxSwagger2Configuration.java (line 43)`
- `litemall-wx-api/src/main/java/org/linlinjava/litemall/wx/web/WxAuthController.java (line 301)`
- `litemall-core/src/main/java/org/linlinjava/litemall/core/express/ExpressService.java (line 26)`
- `deploy/litemall/application.yml (line 44)`
- `deploy/litemall/application.yml (line 126)`
- `deploy/litemall/application.yml (line 142)`
- `docker/litemall/application.yml (line 44)`
- `docker/litemall/application.yml (line 126)`
- `docker/litemall/application.yml (line 142)`
- `litemall-admin-api/src/main/java/org/linlinjava/litemall/admin/config/AdminSwagger2Configuration.java (line 43)`
- `litemall-admin-api/src/main/java/org/linlinjava/litemall/admin/config/AdminSwagger2Configuration.java (line 44)`
- `litemall-core/src/main/resources/application-core.yml (line 8)`
- `litemall-core/src/main/resources/application-core.yml (line 94)`
- `litemall-core/src/main/resources/application-core.yml (line 110)`

</details>

<details id="Localhost_Usage">
<summary><b>Localhost Usage</b> — affected files</summary>

- `litemall-core/src/main/java/org/linlinjava/litemall/core/util/IpUtil.java (line 29)`

</details>

## Upgrade Issues

| Issue Name | Criticality | Story Points | Occurrences |
|------------|-------------|--------------|-------------|
| Java Version Has Reached the End of Support | Mandatory | 8 | [3](#Java_Version_Has_Reached_the_End_of_Support) |

### Issue Details

<details id="Java_Version_Has_Reached_the_End_of_Support">
<summary><b>Java Version Has Reached the End of Support</b> — affected files</summary>

- `pom.xml (line 18)`
- `pom.xml (line 240)`
- `pom.xml (line 241)`

</details>

## Security Issues

> **Note:** These issues were generated by AI and may contain inaccuracies or incomplete information. Please review carefully.

| Issue Name | Criticality | Story Points | Files |
|------------|-------------|--------------|-------|
| CWE-77: Improper Neutralization of Special Elements used in a Command ('Command Injection') | Mandatory | 13 | [1](#CWE-77_Improper_Neutralization_of_Special_Elements_used_in_a_Command_Command_Injection) |
| CWE-78: Improper Neutralization of Special Elements used in an OS Command ('OS Command Injection') | Mandatory | 13 | [1](#CWE-78_Improper_Neutralization_of_Special_Elements_used_in_an_OS_Command_OS_Command_Injection) |
| CWE-89: Improper Neutralization of Special Elements used in an SQL Command ('SQL Injection') | Mandatory | 13 | [2](#CWE-89_Improper_Neutralization_of_Special_Elements_used_in_an_SQL_Command_SQL_Injection) |
| CWE-434: Unrestricted Upload of File with Dangerous Type | Mandatory | 8 | [2](#CWE-434_Unrestricted_Upload_of_File_with_Dangerous_Type) |
| CVE-2025-52999: jackson-core can throw a StackoverflowError when processing deeply nested data | Mandatory | 1 | 0 |
| CVE-2023-6378: logback serialization vulnerability | Mandatory | 1 | 0 |
| CVE-2022-42003: Uncontrolled Resource Consumption in Jackson-databind | Mandatory | 1 | 0 |
| CVE-2022-42004: Uncontrolled Resource Consumption in FasterXML jackson-databind | Mandatory | 1 | 0 |
| CVE-2020-10650: jackson-databind vulnerable to unsafe deserialization | Mandatory | 1 | 0 |
| CVE-2022-28111: MyBatis PageHelper vulnerable to time-blind SQL injection via orderBy parameter | Mandatory | 1 | 0 |
| CVE-2022-25647: Deserialization of Untrusted Data in Gson | Mandatory | 1 | 0 |
| CVE-2020-36518: Deeply nested json in jackson-databind | Mandatory | 1 | 0 |
| CVE-2020-36189: Unsafe Deserialization in jackson-databind | Mandatory | 1 | 0 |
| CVE-2020-36187: Unsafe Deserialization in jackson-databind | Mandatory | 1 | 0 |
| CVE-2020-36188: Unsafe Deserialization in jackson-databind | Mandatory | 1 | 0 |
| CVE-2020-36183: Unsafe Deserialization in jackson-databind | Mandatory | 1 | 0 |
| CVE-2020-36184: Unsafe Deserialization in jackson-databind | Mandatory | 1 | 0 |
| CVE-2020-36180: Unsafe Deserialization in jackson-databind | Mandatory | 1 | 0 |
| CVE-2020-36181: Unsafe Deserialization in jackson-databind | Mandatory | 1 | 0 |
| CVE-2020-36185: Unsafe Deserialization in jackson-databind | Mandatory | 1 | 0 |
| CVE-2020-36179: Unsafe Deserialization in jackson-databind | Mandatory | 1 | 0 |
| CVE-2020-36182: Unsafe Deserialization in jackson-databind | Mandatory | 1 | 0 |
| CVE-2020-24750: Unsafe Deserialization in jackson-databind | Mandatory | 1 | 0 |
| CVE-2020-35728: Serialization gadget exploit in jackson-databind | Mandatory | 1 | 0 |
| CVE-2020-35491: Serialization gadgets exploit in jackson-databind | Mandatory | 1 | 0 |
| CVE-2020-35490: Serialization gadgets exploit in jackson-databind | Mandatory | 1 | 0 |
| CVE-2020-24616: Code Injection in jackson-databind | Mandatory | 1 | 0 |
| CVE-2020-36186: Unsafe Deserialization in jackson-databind | Mandatory | 1 | 0 |
| CVE-2020-25649: XML External Entity (XXE) Injection in Jackson Databind | Mandatory | 1 | 0 |
| CVE-2021-20190: Deserialization of untrusted data in jackson-databind | Mandatory | 1 | 0 |
| CVE-2020-14061: Deserialization of untrusted data in Jackson Databind | Mandatory | 1 | 0 |
| CVE-2020-14062: Deserialization of untrusted data in Jackson Databind | Mandatory | 1 | 0 |
| CVE-2020-14060: Deserialization of untrusted data in Jackson Databind | Mandatory | 1 | 0 |
| CVE-2020-14195: Deserialization of untrusted data in Jackson Databind | Mandatory | 1 | 0 |
| CVE-2019-17267: Improper Input Validation in jackson-databind | Mandatory | 1 | 0 |
| CVE-2020-11112: jackson-databind mishandles the interaction between serialization gadgets and typing | Mandatory | 1 | 0 |
| CVE-2020-9547: jackson-databind mishandles the interaction between serialization gadgets and typing | Mandatory | 1 | 0 |
| CVE-2019-14893: Polymorphic deserialization of malicious object in jackson-databind | Mandatory | 1 | 0 |
| CVE-2020-10673: jackson-databind mishandles the interaction between serialization gadgets and typing | Mandatory | 1 | 0 |
| CVE-2020-9548: jackson-databind mishandles the interaction between serialization gadgets and typing | Mandatory | 1 | 0 |
| CVE-2019-14892: Polymorphic deserialization of malicious object in jackson-databind | Mandatory | 1 | 0 |
| CVE-2020-10968: jackson-databind mishandles the interaction between serialization gadgets and typing | Mandatory | 1 | 0 |
| CVE-2020-11111: jackson-databind mishandles the interaction between serialization gadgets and typing | Mandatory | 1 | 0 |
| CVE-2020-11113: jackson-databind mishandles the interaction between serialization gadgets and typing | Mandatory | 1 | 0 |
| CVE-2020-11619: jackson-databind mishandles the interaction between serialization gadgets and typing | Mandatory | 1 | 0 |
| CVE-2020-10969: jackson-databind mishandles the interaction between serialization gadgets and typing | Mandatory | 1 | 0 |
| CVE-2020-9546: jackson-databind mishandles the interaction between serialization gadgets and typing | Mandatory | 1 | 0 |
| CVE-2020-11620: jackson-databind mishandles the interaction between serialization gadgets and typing | Mandatory | 1 | 0 |
| CVE-2020-10672: jackson-databind mishandles the interaction between serialization gadgets and typing | Mandatory | 1 | 0 |
| CVE-2020-8840: Deserialization of Untrusted Data in jackson-databind | Mandatory | 1 | 0 |
| CVE-2019-20330: Deserialization of Untrusted Data in jackson-databind | Mandatory | 1 | 0 |
| CVE-2019-17531: jackson-databind polymorphic typing issue | Mandatory | 1 | 0 |
| CVE-2019-16943: jackson-databind polymorphic typing issue | Mandatory | 1 | 0 |
| CVE-2019-16942: Polymorphic Typing in FasterXML jackson-databind | Mandatory | 1 | 0 |
| CVE-2019-16335: Polymorphic Typing issue in FasterXML jackson-databind | Mandatory | 1 | 0 |
| CVE-2019-14540: Polymorphic Typing issue in FasterXML jackson-databind | Mandatory | 1 | 0 |
| CVE-2019-14439: Deserialization of untrusted data in FasterXML jackson-databind | Mandatory | 1 | 0 |
| CVE-2019-14379: Deserialization of untrusted data in FasterXML jackson-databind | Mandatory | 1 | 0 |
| CVE-2019-12086: Information exposure in FasterXML jackson-databind | Mandatory | 1 | 0 |
| CVE-2018-18531: Use of Insufficiently Random Values in penggle:kaptcha | Mandatory | 1 | [1](#CVE-2018-18531_Use_of_Insufficiently_Random_Values_in_penggle_kaptcha) |
| CVE-2025-48734: Apache Commons Improper Access Control vulnerability | Mandatory | 1 | 0 |
| CVE-2024-47072: XStream is vulnerable to a Denial of Service attack due to stack overflow from a manipulated binary input stream | Mandatory | 1 | 0 |
| CVE-2024-47554: Apache Commons IO: Possible denial of service attack on untrusted input to XmlStreamReader | Mandatory | 1 | 0 |
| CVE-2024-7254: protobuf-java has potential Denial of Service issue | Mandatory | 1 | 0 |
| CVE-2022-40151: XStream can cause a Denial of Service by injecting deeply nested objects raising a stack overflow | Mandatory | 1 | 0 |
| CVE-2022-41966: XStream can cause Denial of Service via stack overflow | Mandatory | 1 | 0 |
| CVE-2022-3510: Protobuf Java vulnerable to Uncontrolled Resource Consumption | Mandatory | 1 | 0 |
| CVE-2022-3509: Protobuf Java vulnerable to Uncontrolled Resource Consumption | Mandatory | 1 | 0 |
| CVE-2021-0341: Square OkHttp can accept the wrong certificate | Mandatory | 1 | 0 |
| CVE-2015-7501: Deserialization of Untrusted Data in Apache commons collections | Mandatory | 1 | 0 |
| CVE-2021-43859: Denial of Service by injecting highly recursive collections or maps in XStream | Mandatory | 1 | 0 |
| CVE-2021-22569: A potential Denial of Service issue in protobuf-java | Mandatory | 1 | 0 |
| CVE-2021-39139: XStream is vulnerable to an Arbitrary Code Execution attack | Mandatory | 1 | 0 |
| CVE-2021-39141: XStream is vulnerable to an Arbitrary Code Execution attack | Mandatory | 1 | 0 |
| CVE-2021-39144: XStream is vulnerable to a Remote Command Execution attack | Mandatory | 1 | 0 |
| CVE-2021-39145: XStream is vulnerable to an Arbitrary Code Execution attack | Mandatory | 1 | 0 |
| CVE-2021-39146: XStream is vulnerable to an Arbitrary Code Execution attack | Mandatory | 1 | 0 |
| CVE-2021-39147: XStream is vulnerable to an Arbitrary Code Execution attack | Mandatory | 1 | 0 |
| CVE-2021-39148: XStream is vulnerable to an Arbitrary Code Execution attack | Mandatory | 1 | 0 |
| CVE-2021-39149: XStream is vulnerable to an Arbitrary Code Execution attack | Mandatory | 1 | 0 |
| CVE-2021-39150: A Server-Side Forgery Request can be activated unmarshalling with XStream to access data streams from an arbitrary URL referencing a resource in an intranet or the local host | Mandatory | 1 | 0 |
| CVE-2021-39151: XStream is vulnerable to an Arbitrary Code Execution attack | Mandatory | 1 | 0 |
| CVE-2021-39152: A Server-Side Forgery Request can be activated unmarshalling with XStream to access data streams from an arbitrary URL referencing a resource in an intranet or the local host | Mandatory | 1 | 0 |
| CVE-2021-39153: XStream is vulnerable to an Arbitrary Code Execution attack | Mandatory | 1 | 0 |
| CVE-2021-39154: XStream is vulnerable to an Arbitrary Code Execution attack | Mandatory | 1 | 0 |
| CVE-2015-6420: Insecure Deserialization in Apache Commons Collection | Mandatory | 1 | 0 |
| CVE-2026-49268: Apache Shiro: LDAP DN Injection in DefaultLdapRealm | Mandatory | 1 | 0 |
| CVE-2023-22102: MySQL Connectors takeover vulnerability | Mandatory | 1 | [1](#CVE-2023-22102_MySQL_Connectors_takeover_vulnerability) |
| CVE-2023-1370: json-smart Uncontrolled Recursion vulnerability | Mandatory | 1 | 0 |
| CVE-2022-40664: Apache Shiro Authentication Bypass vulnerability | Mandatory | 1 | 0 |
| CVE-2022-32532: Improper Authorization in Apache Shiro | Mandatory | 1 | 0 |
| CVE-2021-41303: Apache Shiro vulnerable to a specially crafted HTTP request causing an authentication bypass | Mandatory | 1 | 0 |
| CVE-2026-41284: Apache Tomcat: Unbounded read in WebDAV LOCK and  PROPFIND handling | Mandatory | 1 | 0 |
| CVE-2026-43512: Apache Tomcat - Digest authenticator will authenticate any unknown user | Mandatory | 1 | 0 |
| CVE-2026-43513: Apache Tomcat: LockOutRealm treats user names as case-sensitive | Mandatory | 1 | 0 |
| CVE-2026-43515: Apache Tomcat - Security constraints not correctly applied | Mandatory | 1 | 0 |
| CVE-2026-41293: Apache Tomcat - HTTP/2 request headers not validated | Mandatory | 1 | 0 |
| CVE-2026-42498: Apache Tomcat - WebSocket authentication header exposure | Mandatory | 1 | 0 |
| CVE-2026-24880: Apache Tomcat has an HTTP Request/Response Smuggling vulnerability | Mandatory | 1 | 0 |
| CVE-2026-24400: AssertJ has XML External Entity (XXE) vulnerability when parsing untrusted XML via isXmlEqualTo assertion | Mandatory | 1 | 0 |
| CVE-2025-55752: Apache Tomcat Vulnerable to Relative Path Traversal | Mandatory | 1 | 0 |
| CVE-2025-48989: Apache Tomcat Improper Resource Shutdown or Release vulnerability | Mandatory | 1 | 0 |
| CVE-2025-53506: Apache Tomcat Coyote vulnerable to Denial of Service via excessive HTTP/2 streams | Mandatory | 1 | 0 |
| CVE-2025-52520: Apache Tomcat Catalina is vulnerable to DoS attack through bypassing of size limits | Mandatory | 1 | 0 |
| CVE-2025-48988: Apache Tomcat - DoS in multipart upload | Mandatory | 1 | 0 |
| CVE-2025-24813: Apache Tomcat: Potential RCE and/or information disclosure and/or information corruption with partial PUT | Mandatory | 1 | 0 |
| CVE-2024-56337: Apache Tomcat Time-of-check Time-of-use (TOCTOU) Race Condition vulnerability | Mandatory | 1 | 0 |
| CVE-2024-50379: Apache Tomcat Time-of-check Time-of-use (TOCTOU) Race Condition vulnerability | Mandatory | 1 | 0 |
| CVE-2024-34750: Apache Tomcat - Denial of Service | Mandatory | 1 | 0 |
| CVE-2023-46589: Apache Tomcat Improper Input Validation vulnerability | Mandatory | 1 | 0 |
| CVE-2023-5072: Java: DoS Vulnerability in JSON-JAVA | Mandatory | 1 | 0 |
| CVE-2023-34478: Path Traversal in Apache Shiro | Mandatory | 1 | 0 |
| CVE-2023-24998: Apache Commons FileUpload denial of service vulnerability | Mandatory | 1 | 0 |
| CVE-2022-45688: json stack overflow vulnerability | Mandatory | 1 | 0 |
| CVE-2022-42252: Apache Tomcat may reject request containing invalid Content-Length header | Mandatory | 1 | 0 |
| CVE-2022-29631: Server-Side Request Forgery in Jodd HTTP | Mandatory | 1 | 0 |
| CVE-2020-11996: Uncontrolled Resource Consumption in Apache Tomcat | Mandatory | 1 | 0 |
| CVE-2020-17523: Authentication bypass in Apache Shiro | Mandatory | 1 | 0 |
| CVE-2020-13935: Infinite Loop in Apache Tomcat | Mandatory | 1 | 0 |
| CVE-2021-33813: XML External Entity (XXE) Injection in JDOM | Mandatory | 1 | 0 |
| CVE-2021-25122: Exposure of Sensitive Information to an Unauthorized Actor in Apache Tomcat | Mandatory | 1 | 0 |
| CVE-2020-17510: Authentication bypass in Apache Shiro | Mandatory | 1 | 0 |
| CVE-2021-25329: Potential remote code execution in Apache Tomcat | Mandatory | 1 | 0 |
| CVE-2020-1938: Improper Privilege Management in Tomcat | Mandatory | 1 | 0 |
| CVE-2020-9484: Potential remote code execution in Apache Tomcat | Mandatory | 1 | 0 |
| CVE-2019-12418: Insufficiently Protected Credentials in Apache Tomcat | Mandatory | 1 | 0 |
| CVE-2019-17563: In Apache Tomcat, when using FORM authentication there was a narrow window where an attacker could perform a session fixation attack | Mandatory | 1 | 0 |
| CVE-2019-10072: Improper Locking in Apache Tomcat | Mandatory | 1 | 0 |
| CVE-2026-40972: Spring Boot DevTools remote secret comparison is vulnerable to timing attacks | Mandatory | 1 | 0 |
| CVE-2023-20883: Spring Boot Welcome Page Denial of Service | Mandatory | 1 | 0 |
| CVE-2022-22965: Remote Code Execution in Spring Framework | Mandatory | 1 | [1](#CVE-2022-22965_Remote_Code_Execution_in_Spring_Framework) |
| CVE-2020-26945: "Deserialization errors in MyBatis" | Mandatory | 1 | 0 |
| CVE-2026-40973: Spring Boot accepts predictable temp directory without ownership verification | Mandatory | 1 | 0 |
| CVE-2025-22235: Spring Boot EndpointRequest.to() creates wrong matcher if actuator endpoint is not exposed | Mandatory | 1 | 0 |
| CVE-2024-38819: Spring Framework Path Traversal vulnerability | Mandatory | 1 | 0 |
| CVE-2024-22262: Spring Framework URL Parsing with Host Validation | Mandatory | 1 | 0 |
| CVE-2024-22259: Spring Framework URL Parsing with Host Validation Vulnerability | Mandatory | 1 | 0 |
| CVE-2024-22243: Spring Web vulnerable to Open Redirect or Server Side Request Forgery | Mandatory | 1 | 0 |
| CVE-2023-20863: Spring Framework vulnerable to denial of service | Mandatory | 1 | 0 |
| CVE-2022-1471: SnakeYaml Constructor Deserialization Remote Code Execution | Mandatory | 1 | 0 |
| CVE-2022-25857: Uncontrolled Resource Consumption in snakeyaml | Mandatory | 1 | 0 |
| CVE-2022-27772: Temporary Directory Hijacking to Local Privilege Escalation Vulnerability in org.springframework.boot:spring-boot | Mandatory | 1 | 0 |
| CVE-2016-1000027: Pivotal Spring Framework contains unsafe Java deserialization methods | Mandatory | 1 | 0 |
| CVE-2022-22970: Denial of service in Spring Framework | Mandatory | 1 | 0 |
| CVE-2022-22968: Improper handling of case sensitivity in Spring Framework | Mandatory | 1 | 0 |
| CVE-2017-18640: SnakeYAML Entity Expansion during load operation | Mandatory | 1 | 0 |
| CVE-2020-5398: RFD attack via Content-Disposition header sourced from request input by Spring MVC or Spring WebFlux Application | Mandatory | 1 | 0 |
| CWE-820: Missing Synchronization | Potential | 8 | [2](#CWE-820_Missing_Synchronization) |
| CWE-567: Unsynchronized Access to Shared Data in a Multithreaded Context | Potential | 5 | [1](#CWE-567_Unsynchronized_Access_to_Shared_Data_in_a_Multithreaded_Context) |
| CWE-321: Use of Hard-coded Cryptographic Key | Potential | 5 | [1](#CWE-321_Use_of_Hard-coded_Cryptographic_Key) |
| CWE-681: Incorrect Conversion between Numeric Types | Potential | 3 | [2](#CWE-681_Incorrect_Conversion_between_Numeric_Types) |
| CWE-772: Missing Release of Resource after Effective Lifetime | Potential | 3 | [1](#CWE-772_Missing_Release_of_Resource_after_Effective_Lifetime) |
| CWE-775: Missing Release of File Descriptor or Handle after Effective Lifetime | Potential | 3 | [1](#CWE-775_Missing_Release_of_File_Descriptor_or_Handle_after_Effective_Lifetime) |
| CWE-778: Insufficient Logging | Potential | 3 | [2](#CWE-778_Insufficient_Logging) |
| CWE-22: Improper Limitation of a Pathname to a Restricted Directory ('Path Traversal') | Optional | 8 | [2](#CWE-22_Improper_Limitation_of_a_Pathname_to_a_Restricted_Directory_Path_Traversal) |
| CWE-259: Use of Hard-coded Password | Optional | 5 | [2](#CWE-259_Use_of_Hard-coded_Password) |
| CWE-798: Use of Hard-coded Credentials | Optional | 5 | [2](#CWE-798_Use_of_Hard-coded_Credentials) |
| CWE-23: Relative Path Traversal | Optional | 5 | [1](#CWE-23_Relative_Path_Traversal) |
| CWE-477: Use of Obsolete Function | Optional | 1 | [2](#CWE-477_Use_of_Obsolete_Function) |

### Security Issue Details

<details id="CWE-77_Improper_Neutralization_of_Special_Elements_used_in_a_Command_Command_Injection">
<summary><b>CWE-77: Improper Neutralization of Special Elements used in a Command ('Command Injection')</b> — affected files</summary>

- `litemall-db/src/main/java/org/linlinjava/litemall/db/util/DbUtil.java`

</details>

<details id="CWE-78_Improper_Neutralization_of_Special_Elements_used_in_an_OS_Command_OS_Command_Injection">
<summary><b>CWE-78: Improper Neutralization of Special Elements used in an OS Command ('OS Command Injection')</b> — affected files</summary>

- `litemall-db/src/main/java/org/linlinjava/litemall/db/util/DbUtil.java`

</details>

<details id="CWE-89_Improper_Neutralization_of_Special_Elements_used_in_an_SQL_Command_SQL_Injection">
<summary><b>CWE-89: Improper Neutralization of Special Elements used in an SQL Command ('SQL Injection')</b> — affected files</summary>

- `litemall-db/src/main/resources/org/linlinjava/litemall/db/dao/OrderMapper.xml`
- `litemall-db/src/main/java/org/linlinjava/litemall/db/service/LitemallOrderService.java`

</details>

<details id="CWE-434_Unrestricted_Upload_of_File_with_Dangerous_Type">
<summary><b>CWE-434: Unrestricted Upload of File with Dangerous Type</b> — affected files</summary>

- `litemall-admin-api/src/main/java/org/linlinjava/litemall/admin/web/AdminStorageController.java`
- `litemall-wx-api/src/main/java/org/linlinjava/litemall/wx/web/WxStorageController.java`

</details>

<details id="CVE-2018-18531_Use_of_Insufficiently_Random_Values_in_penggle_kaptcha">
<summary><b>CVE-2018-18531: Use of Insufficiently Random Values in penggle:kaptcha</b> — affected files</summary>

- `pom.xml:152`

</details>

<details id="CVE-2023-22102_MySQL_Connectors_takeover_vulnerability">
<summary><b>CVE-2023-22102: MySQL Connectors takeover vulnerability</b> — affected files</summary>

- `litemall-db/pom.xml:25`

</details>

<details id="CVE-2022-22965_Remote_Code_Execution_in_Spring_Framework">
<summary><b>CVE-2022-22965: Remote Code Execution in Spring Framework</b> — affected files</summary>

- `litemall-core/pom.xml:19`

</details>

<details id="CWE-820_Missing_Synchronization">
<summary><b>CWE-820: Missing Synchronization</b> — affected files</summary>

- `litemall-wx-api/src/main/java/org/linlinjava/litemall/wx/web/WxHomeController.java`
- `litemall-wx-api/src/main/java/org/linlinjava/litemall/wx/web/WxGoodsController.java`

</details>

<details id="CWE-567_Unsynchronized_Access_to_Shared_Data_in_a_Multithreaded_Context">
<summary><b>CWE-567: Unsynchronized Access to Shared Data in a Multithreaded Context</b> — affected files</summary>

- `litemall-wx-api/src/main/java/org/linlinjava/litemall/wx/service/HomeCacheManager.java`

</details>

<details id="CWE-321_Use_of_Hard-coded_Cryptographic_Key">
<summary><b>CWE-321: Use of Hard-coded Cryptographic Key</b> — affected files</summary>

- `deploy/litemall/application.yml`

</details>

<details id="CWE-681_Incorrect_Conversion_between_Numeric_Types">
<summary><b>CWE-681: Incorrect Conversion between Numeric Types</b> — affected files</summary>

- `litemall-db/src/main/java/org/linlinjava/litemall/db/service/LitemallGoodsService.java`
- `litemall-db/src/main/java/org/linlinjava/litemall/db/service/LitemallOrderService.java`

</details>

<details id="CWE-772_Missing_Release_of_Resource_after_Effective_Lifetime">
<summary><b>CWE-772: Missing Release of Resource after Effective Lifetime</b> — affected files</summary>

- `litemall-db/src/main/java/org/linlinjava/litemall/db/util/DbUtil.java`

</details>

<details id="CWE-775_Missing_Release_of_File_Descriptor_or_Handle_after_Effective_Lifetime">
<summary><b>CWE-775: Missing Release of File Descriptor or Handle after Effective Lifetime</b> — affected files</summary>

- `litemall-db/src/main/java/org/linlinjava/litemall/db/util/DbUtil.java`

</details>

<details id="CWE-778_Insufficient_Logging">
<summary><b>CWE-778: Insufficient Logging</b> — affected files</summary>

- `litemall-admin-api/src/main/java/org/linlinjava/litemall/admin/web/AdminAuthController.java`
- `litemall-wx-api/src/main/java/org/linlinjava/litemall/wx/web/WxAuthController.java`

</details>

<details id="CWE-22_Improper_Limitation_of_a_Pathname_to_a_Restricted_Directory_Path_Traversal">
<summary><b>CWE-22: Improper Limitation of a Pathname to a Restricted Directory ('Path Traversal')</b> — affected files</summary>

- `litemall-core/src/main/java/org/linlinjava/litemall/core/storage/LocalStorage.java`
- `litemall-wx-api/src/main/java/org/linlinjava/litemall/wx/web/WxStorageController.java`

</details>

<details id="CWE-259_Use_of_Hard-coded_Password">
<summary><b>CWE-259: Use of Hard-coded Password</b> — affected files</summary>

- `deploy/litemall/application.yml`
- `docker/litemall/application.yml`

</details>

<details id="CWE-798_Use_of_Hard-coded_Credentials">
<summary><b>CWE-798: Use of Hard-coded Credentials</b> — affected files</summary>

- `deploy/litemall/application.yml`
- `docker/litemall/application.yml`

</details>

<details id="CWE-23_Relative_Path_Traversal">
<summary><b>CWE-23: Relative Path Traversal</b> — affected files</summary>

- `litemall-wx-api/src/main/java/org/linlinjava/litemall/wx/web/WxStorageController.java`

</details>

<details id="CWE-477_Use_of_Obsolete_Function">
<summary><b>CWE-477: Use of Obsolete Function</b> — affected files</summary>

- `litemall-db/src/main/java/org/linlinjava/litemall/db/service/LitemallAdService.java`
- `litemall-db/src/main/java/org/linlinjava/litemall/db/util/DbUtil.java`

</details>

---

## Codebase Insights

> **Note:** These documents are generated by AI and may contain inaccuracies or incomplete information. Please review carefully.

> **Codebase Insights aren't available yet.**
>
> These documents are generated when assessment runs with **Full analysis** coverage. Re-run the assessment and set `analysisCoverage: full` to enable them.

[Share feedback](https://aka.ms/ghcp-appmod/feedback)
