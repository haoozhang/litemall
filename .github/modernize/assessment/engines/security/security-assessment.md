# Security Assessment Report

**Generated:** 2026-06-22T07:13:18.0000000Z

## Summary

| Metric | Count |
|--------|-------|
| Total Findings | 159 |
| CVE Vulnerabilities | 143 |
| CWE Vulnerabilities | 16 |
| Total Rules Assessed | 59 |
| Rules Passed | 43 |

### By Severity

| Severity | Count |
|----------|-------|
| mandatory | 147 |
| optional | 5 |
| potential | 7 |

## CVE Findings (Dependency Vulnerabilities)

### CVE-2025-52999: jackson-core can throw a StackoverflowError when processing deeply nested data
- **Severity:** mandatory
- **Story Points:** 1
- **Files:** N/A

[CVE-2025-52999](https://github.com/advisories/GHSA-h46c-h94j-95f3): jackson-core can throw a StackoverflowError when processing deeply nested data

Severity: HIGH

Affected dependencies:
  - com.fasterxml.jackson.core:jackson-core:2.9.8 (transitive)

Recommended fix:
  - Upgrade com.fasterxml.jackson.core:jackson-core to 2.15.0 or later

### CVE-2023-6378: logback serialization vulnerability
- **Severity:** mandatory
- **Story Points:** 1
- **Files:** N/A

[CVE-2023-6378](https://github.com/advisories/GHSA-vmq6-5m68-f53m): logback serialization vulnerability

Severity: HIGH

Affected dependencies:
  - ch.qos.logback:logback-classic:1.2.3 (transitive)
  - ch.qos.logback:logback-core:1.2.3 (transitive)
  - ch.qos.logback:logback-classic:1.2.3 (transitive)
  - ch.qos.logback:logback-core:1.2.3 (transitive)
  - ch.qos.logback:logback-core:1.2.3 (transitive)
  - ch.qos.logback:logback-classic:1.2.3 (transitive)

Recommended fix:
  - Upgrade ch.qos.logback:logback-classic to 1.4.12 or later
  - Upgrade ch.qos.logback:logback-core to 1.4.12 or later
  - Upgrade ch.qos.logback:logback-classic to 1.3.12 or later
  - Upgrade ch.qos.logback:logback-core to 1.3.12 or later
  - Upgrade ch.qos.logback:logback-core to 1.2.13 or later
  - Upgrade ch.qos.logback:logback-classic to 1.2.13 or later

### CVE-2022-42003: Uncontrolled Resource Consumption in Jackson-databind
- **Severity:** mandatory
- **Story Points:** 1
- **Files:** N/A

[CVE-2022-42003](https://github.com/advisories/GHSA-jjjh-jjxp-wpff): Uncontrolled Resource Consumption in Jackson-databind

Severity: HIGH

Affected dependencies:
  - com.fasterxml.jackson.core:jackson-databind:2.9.8 (transitive)
  - com.fasterxml.jackson.core:jackson-databind:2.9.8 (transitive)

Recommended fix:
  - Upgrade com.fasterxml.jackson.core:jackson-databind to 2.12.7.1 or later
  - Upgrade com.fasterxml.jackson.core:jackson-databind to 2.13.4.2 or later

### CVE-2022-42004: Uncontrolled Resource Consumption in FasterXML jackson-databind
- **Severity:** mandatory
- **Story Points:** 1
- **Files:** N/A

[CVE-2022-42004](https://github.com/advisories/GHSA-rgv9-q543-rqg4): Uncontrolled Resource Consumption in FasterXML jackson-databind

Severity: HIGH

Affected dependencies:
  - com.fasterxml.jackson.core:jackson-databind:2.9.8 (transitive)
  - com.fasterxml.jackson.core:jackson-databind:2.9.8 (transitive)

Recommended fix:
  - Upgrade com.fasterxml.jackson.core:jackson-databind to 2.13.4 or later
  - Upgrade com.fasterxml.jackson.core:jackson-databind to 2.12.7.1 or later

### CVE-2020-10650: jackson-databind vulnerable to unsafe deserialization
- **Severity:** mandatory
- **Story Points:** 1
- **Files:** N/A

[CVE-2020-10650](https://github.com/advisories/GHSA-rpr3-cw39-3pxh): jackson-databind vulnerable to unsafe deserialization

Severity: HIGH

Affected dependencies:
  - com.fasterxml.jackson.core:jackson-databind:2.9.8 (transitive)

Recommended fix:
  - Upgrade com.fasterxml.jackson.core:jackson-databind to 2.9.10.4 or later

### CVE-2022-28111: MyBatis PageHelper vulnerable to time-blind SQL injection via orderBy parameter
- **Severity:** mandatory
- **Story Points:** 1
- **Files:** N/A

[CVE-2022-28111](https://github.com/advisories/GHSA-w559-623p-vfg8): MyBatis PageHelper vulnerable to time-blind SQL injection via orderBy parameter

Severity: CRITICAL

Affected dependencies:
  - com.github.pagehelper:pagehelper:5.1.4 (transitive)

Recommended fix:
  - Upgrade com.github.pagehelper:pagehelper to 5.3.1 or later

### CVE-2022-25647: Deserialization of Untrusted Data in Gson
- **Severity:** mandatory
- **Story Points:** 1
- **Files:** N/A

[CVE-2022-25647](https://github.com/advisories/GHSA-4jrv-ppp4-jm57): Deserialization of Untrusted Data in Gson

Severity: HIGH

Affected dependencies:
  - com.google.code.gson:gson:2.8.5 (transitive)

Recommended fix:
  - Upgrade com.google.code.gson:gson to 2.8.9 or later

### CVE-2020-36518: Deeply nested json in jackson-databind
- **Severity:** mandatory
- **Story Points:** 1
- **Files:** N/A

[CVE-2020-36518](https://github.com/advisories/GHSA-57j2-w4cx-62h2): Deeply nested json in jackson-databind

Severity: HIGH

Affected dependencies:
  - com.fasterxml.jackson.core:jackson-databind:2.9.8 (transitive)
  - com.fasterxml.jackson.core:jackson-databind:2.9.8 (transitive)

Recommended fix:
  - Upgrade com.fasterxml.jackson.core:jackson-databind to 2.13.2.1 or later
  - Upgrade com.fasterxml.jackson.core:jackson-databind to 2.12.6.1 or later

### CVE-2020-36189: Unsafe Deserialization in jackson-databind
- **Severity:** mandatory
- **Story Points:** 1
- **Files:** N/A

[CVE-2020-36189](https://github.com/advisories/GHSA-vfqx-33qm-g869): Unsafe Deserialization in jackson-databind

Severity: HIGH

Affected dependencies:
  - com.fasterxml.jackson.core:jackson-databind:2.9.8 (transitive)
  - com.fasterxml.jackson.core:jackson-databind:2.9.8 (transitive)

Recommended fix:
  - Upgrade com.fasterxml.jackson.core:jackson-databind to 2.9.10.8 or later
  - Upgrade com.fasterxml.jackson.core:jackson-databind to 2.6.7.5 or later

### CVE-2020-36187: Unsafe Deserialization in jackson-databind
- **Severity:** mandatory
- **Story Points:** 1
- **Files:** N/A

[CVE-2020-36187](https://github.com/advisories/GHSA-r695-7vr9-jgc2): Unsafe Deserialization in jackson-databind

Severity: HIGH

Affected dependencies:
  - com.fasterxml.jackson.core:jackson-databind:2.9.8 (transitive)

Recommended fix:
  - Upgrade com.fasterxml.jackson.core:jackson-databind to 2.9.10.8 or later

### CVE-2020-36188: Unsafe Deserialization in jackson-databind
- **Severity:** mandatory
- **Story Points:** 1
- **Files:** N/A

[CVE-2020-36188](https://github.com/advisories/GHSA-f9xh-2qgp-cq57): Unsafe Deserialization in jackson-databind

Severity: HIGH

Affected dependencies:
  - com.fasterxml.jackson.core:jackson-databind:2.9.8 (transitive)
  - com.fasterxml.jackson.core:jackson-databind:2.9.8 (transitive)

Recommended fix:
  - Upgrade com.fasterxml.jackson.core:jackson-databind to 2.9.10.8 or later
  - Upgrade com.fasterxml.jackson.core:jackson-databind to 2.6.7.5 or later

### CVE-2020-36183: Unsafe Deserialization in jackson-databind
- **Severity:** mandatory
- **Story Points:** 1
- **Files:** N/A

[CVE-2020-36183](https://github.com/advisories/GHSA-9m6f-7xcq-8vf8): Unsafe Deserialization in jackson-databind

Severity: HIGH

Affected dependencies:
  - com.fasterxml.jackson.core:jackson-databind:2.9.8 (transitive)
  - com.fasterxml.jackson.core:jackson-databind:2.9.8 (transitive)

Recommended fix:
  - Upgrade com.fasterxml.jackson.core:jackson-databind to 2.9.10.8 or later
  - Upgrade com.fasterxml.jackson.core:jackson-databind to 2.6.7.5 or later

### CVE-2020-36184: Unsafe Deserialization in jackson-databind
- **Severity:** mandatory
- **Story Points:** 1
- **Files:** N/A

[CVE-2020-36184](https://github.com/advisories/GHSA-m6x4-97wx-4q27): Unsafe Deserialization in jackson-databind

Severity: HIGH

Affected dependencies:
  - com.fasterxml.jackson.core:jackson-databind:2.9.8 (transitive)

Recommended fix:
  - Upgrade com.fasterxml.jackson.core:jackson-databind to 2.9.10.8 or later

### CVE-2020-36180: Unsafe Deserialization in jackson-databind
- **Severity:** mandatory
- **Story Points:** 1
- **Files:** N/A

[CVE-2020-36180](https://github.com/advisories/GHSA-8c4j-34r4-xr8g): Unsafe Deserialization in jackson-databind

Severity: HIGH

Affected dependencies:
  - com.fasterxml.jackson.core:jackson-databind:2.9.8 (transitive)
  - com.fasterxml.jackson.core:jackson-databind:2.9.8 (transitive)

Recommended fix:
  - Upgrade com.fasterxml.jackson.core:jackson-databind to 2.9.10.8 or later
  - Upgrade com.fasterxml.jackson.core:jackson-databind to 2.6.7.5 or later

### CVE-2020-36181: Unsafe Deserialization in jackson-databind
- **Severity:** mandatory
- **Story Points:** 1
- **Files:** N/A

[CVE-2020-36181](https://github.com/advisories/GHSA-cvm9-fjm9-3572): Unsafe Deserialization in jackson-databind

Severity: HIGH

Affected dependencies:
  - com.fasterxml.jackson.core:jackson-databind:2.9.8 (transitive)
  - com.fasterxml.jackson.core:jackson-databind:2.9.8 (transitive)

Recommended fix:
  - Upgrade com.fasterxml.jackson.core:jackson-databind to 2.9.10.8 or later
  - Upgrade com.fasterxml.jackson.core:jackson-databind to 2.6.7.5 or later

### CVE-2020-36185: Unsafe Deserialization in jackson-databind
- **Severity:** mandatory
- **Story Points:** 1
- **Files:** N/A

[CVE-2020-36185](https://github.com/advisories/GHSA-8w26-6f25-cm9x): Unsafe Deserialization in jackson-databind

Severity: HIGH

Affected dependencies:
  - com.fasterxml.jackson.core:jackson-databind:2.9.8 (transitive)

Recommended fix:
  - Upgrade com.fasterxml.jackson.core:jackson-databind to 2.9.10.8 or later

### CVE-2020-36179: Unsafe Deserialization in jackson-databind
- **Severity:** mandatory
- **Story Points:** 1
- **Files:** N/A

[CVE-2020-36179](https://github.com/advisories/GHSA-9gph-22xh-8x98): Unsafe Deserialization in jackson-databind

Severity: HIGH

Affected dependencies:
  - com.fasterxml.jackson.core:jackson-databind:2.9.8 (transitive)
  - com.fasterxml.jackson.core:jackson-databind:2.9.8 (transitive)

Recommended fix:
  - Upgrade com.fasterxml.jackson.core:jackson-databind to 2.9.10.8 or later
  - Upgrade com.fasterxml.jackson.core:jackson-databind to 2.6.7.5 or later

### CVE-2020-36182: Unsafe Deserialization in jackson-databind
- **Severity:** mandatory
- **Story Points:** 1
- **Files:** N/A

[CVE-2020-36182](https://github.com/advisories/GHSA-89qr-369f-5m5x): Unsafe Deserialization in jackson-databind

Severity: HIGH

Affected dependencies:
  - com.fasterxml.jackson.core:jackson-databind:2.9.8 (transitive)
  - com.fasterxml.jackson.core:jackson-databind:2.9.8 (transitive)

Recommended fix:
  - Upgrade com.fasterxml.jackson.core:jackson-databind to 2.9.10.8 or later
  - Upgrade com.fasterxml.jackson.core:jackson-databind to 2.6.7.5 or later

### CVE-2020-24750: Unsafe Deserialization in jackson-databind
- **Severity:** mandatory
- **Story Points:** 1
- **Files:** N/A

[CVE-2020-24750](https://github.com/advisories/GHSA-qjw2-hr98-qgfh): Unsafe Deserialization in jackson-databind

Severity: HIGH

Affected dependencies:
  - com.fasterxml.jackson.core:jackson-databind:2.9.8 (transitive)
  - com.fasterxml.jackson.core:jackson-databind:2.9.8 (transitive)

Recommended fix:
  - Upgrade com.fasterxml.jackson.core:jackson-databind to 2.6.7.5 or later
  - Upgrade com.fasterxml.jackson.core:jackson-databind to 2.9.10.6 or later

### CVE-2020-35728: Serialization gadget exploit in jackson-databind
- **Severity:** mandatory
- **Story Points:** 1
- **Files:** N/A

[CVE-2020-35728](https://github.com/advisories/GHSA-5r5r-6hpj-8gg9): Serialization gadget exploit in jackson-databind

Severity: HIGH

Affected dependencies:
  - com.fasterxml.jackson.core:jackson-databind:2.9.8 (transitive)

Recommended fix:
  - Upgrade com.fasterxml.jackson.core:jackson-databind to 2.9.10.8 or later

### CVE-2020-35491: Serialization gadgets exploit in jackson-databind
- **Severity:** mandatory
- **Story Points:** 1
- **Files:** N/A

[CVE-2020-35491](https://github.com/advisories/GHSA-r3gr-cxrf-hg25): Serialization gadgets exploit in jackson-databind

Severity: HIGH

Affected dependencies:
  - com.fasterxml.jackson.core:jackson-databind:2.9.8 (transitive)

Recommended fix:
  - Upgrade com.fasterxml.jackson.core:jackson-databind to 2.9.10.8 or later

### CVE-2020-35490: Serialization gadgets exploit in jackson-databind
- **Severity:** mandatory
- **Story Points:** 1
- **Files:** N/A

[CVE-2020-35490](https://github.com/advisories/GHSA-wh8g-3j2c-rqj5): Serialization gadgets exploit in jackson-databind

Severity: HIGH

Affected dependencies:
  - com.fasterxml.jackson.core:jackson-databind:2.9.8 (transitive)

Recommended fix:
  - Upgrade com.fasterxml.jackson.core:jackson-databind to 2.9.10.8 or later

### CVE-2020-24616: Code Injection in jackson-databind
- **Severity:** mandatory
- **Story Points:** 1
- **Files:** N/A

[CVE-2020-24616](https://github.com/advisories/GHSA-h3cw-g4mq-c5x2): Code Injection in jackson-databind

Severity: HIGH

Affected dependencies:
  - com.fasterxml.jackson.core:jackson-databind:2.9.8 (transitive)

Recommended fix:
  - Upgrade com.fasterxml.jackson.core:jackson-databind to 2.9.10.6 or later

### CVE-2020-36186: Unsafe Deserialization in jackson-databind
- **Severity:** mandatory
- **Story Points:** 1
- **Files:** N/A

[CVE-2020-36186](https://github.com/advisories/GHSA-v585-23hc-c647): Unsafe Deserialization in jackson-databind

Severity: HIGH

Affected dependencies:
  - com.fasterxml.jackson.core:jackson-databind:2.9.8 (transitive)

Recommended fix:
  - Upgrade com.fasterxml.jackson.core:jackson-databind to 2.9.10.8 or later

### CVE-2020-25649: XML External Entity (XXE) Injection in Jackson Databind
- **Severity:** mandatory
- **Story Points:** 1
- **Files:** N/A

[CVE-2020-25649](https://github.com/advisories/GHSA-288c-cq4h-88gq): XML External Entity (XXE) Injection in Jackson Databind

Severity: HIGH

Affected dependencies:
  - com.fasterxml.jackson.core:jackson-databind:2.9.8 (transitive)
  - com.fasterxml.jackson.core:jackson-databind:2.9.8 (transitive)
  - com.fasterxml.jackson.core:jackson-databind:2.9.8 (transitive)

Recommended fix:
  - Upgrade com.fasterxml.jackson.core:jackson-databind to 2.9.10.7 or later
  - Upgrade com.fasterxml.jackson.core:jackson-databind to 2.10.5.1 or later
  - Upgrade com.fasterxml.jackson.core:jackson-databind to 2.6.7.4 or later

### CVE-2021-20190: Deserialization of untrusted data in jackson-databind
- **Severity:** mandatory
- **Story Points:** 1
- **Files:** N/A

[CVE-2021-20190](https://github.com/advisories/GHSA-5949-rw7g-wx7w): Deserialization of untrusted data in jackson-databind

Severity: HIGH

Affected dependencies:
  - com.fasterxml.jackson.core:jackson-databind:2.9.8 (transitive)
  - com.fasterxml.jackson.core:jackson-databind:2.9.8 (transitive)

Recommended fix:
  - Upgrade com.fasterxml.jackson.core:jackson-databind to 2.9.10.7 or later
  - Upgrade com.fasterxml.jackson.core:jackson-databind to 2.6.7.5 or later

### CVE-2020-14061: Deserialization of untrusted data in Jackson Databind
- **Severity:** mandatory
- **Story Points:** 1
- **Files:** N/A

[CVE-2020-14061](https://github.com/advisories/GHSA-c2q3-4qrh-fm48): Deserialization of untrusted data in Jackson Databind

Severity: HIGH

Affected dependencies:
  - com.fasterxml.jackson.core:jackson-databind:2.9.8 (transitive)

Recommended fix:
  - Upgrade com.fasterxml.jackson.core:jackson-databind to 2.9.10.5 or later

### CVE-2020-14062: Deserialization of untrusted data in Jackson Databind
- **Severity:** mandatory
- **Story Points:** 1
- **Files:** N/A

[CVE-2020-14062](https://github.com/advisories/GHSA-c265-37vj-cwcc): Deserialization of untrusted data in Jackson Databind

Severity: HIGH

Affected dependencies:
  - com.fasterxml.jackson.core:jackson-databind:2.9.8 (transitive)

Recommended fix:
  - Upgrade com.fasterxml.jackson.core:jackson-databind to 2.9.10.5 or later

### CVE-2020-14060: Deserialization of untrusted data in Jackson Databind
- **Severity:** mandatory
- **Story Points:** 1
- **Files:** N/A

[CVE-2020-14060](https://github.com/advisories/GHSA-j823-4qch-3rgm): Deserialization of untrusted data in Jackson Databind

Severity: HIGH

Affected dependencies:
  - com.fasterxml.jackson.core:jackson-databind:2.9.8 (transitive)

Recommended fix:
  - Upgrade com.fasterxml.jackson.core:jackson-databind to 2.9.10.5 or later

### CVE-2020-14195: Deserialization of untrusted data in Jackson Databind
- **Severity:** mandatory
- **Story Points:** 1
- **Files:** N/A

[CVE-2020-14195](https://github.com/advisories/GHSA-mc6h-4qgp-37qh): Deserialization of untrusted data in Jackson Databind

Severity: HIGH

Affected dependencies:
  - com.fasterxml.jackson.core:jackson-databind:2.9.8 (transitive)

Recommended fix:
  - Upgrade com.fasterxml.jackson.core:jackson-databind to 2.9.10.5 or later

### CVE-2019-17267: Improper Input Validation in jackson-databind
- **Severity:** mandatory
- **Story Points:** 1
- **Files:** N/A

[CVE-2019-17267](https://github.com/advisories/GHSA-f3j5-rmmp-3fc5): Improper Input Validation in jackson-databind

Severity: CRITICAL

Affected dependencies:
  - com.fasterxml.jackson.core:jackson-databind:2.9.8 (transitive)
  - com.fasterxml.jackson.core:jackson-databind:2.9.8 (transitive)

Recommended fix:
  - Upgrade com.fasterxml.jackson.core:jackson-databind to 2.9.10 or later
  - Upgrade com.fasterxml.jackson.core:jackson-databind to 2.8.11.5 or later

### CVE-2020-11112: jackson-databind mishandles the interaction between serialization gadgets and typing
- **Severity:** mandatory
- **Story Points:** 1
- **Files:** N/A

[CVE-2020-11112](https://github.com/advisories/GHSA-58pp-9c76-5625): jackson-databind mishandles the interaction between serialization gadgets and typing

Severity: HIGH

Affected dependencies:
  - com.fasterxml.jackson.core:jackson-databind:2.9.8 (transitive)

Recommended fix:
  - Upgrade com.fasterxml.jackson.core:jackson-databind to 2.9.10.4 or later

### CVE-2020-9547: jackson-databind mishandles the interaction between serialization gadgets and typing
- **Severity:** mandatory
- **Story Points:** 1
- **Files:** N/A

[CVE-2020-9547](https://github.com/advisories/GHSA-q93h-jc49-78gg): jackson-databind mishandles the interaction between serialization gadgets and typing

Severity: CRITICAL

Affected dependencies:
  - com.fasterxml.jackson.core:jackson-databind:2.9.8 (transitive)
  - com.fasterxml.jackson.core:jackson-databind:2.9.8 (transitive)
  - com.fasterxml.jackson.core:jackson-databind:2.9.8 (transitive)

Recommended fix:
  - Upgrade com.fasterxml.jackson.core:jackson-databind to 2.9.10.4 or later
  - Upgrade com.fasterxml.jackson.core:jackson-databind to 2.8.11.6 or later
  - Upgrade com.fasterxml.jackson.core:jackson-databind to 2.7.9.7 or later

### CVE-2019-14893: Polymorphic deserialization of malicious object in jackson-databind
- **Severity:** mandatory
- **Story Points:** 1
- **Files:** N/A

[CVE-2019-14893](https://github.com/advisories/GHSA-qmqc-x3r4-6v39): Polymorphic deserialization of malicious object in jackson-databind

Severity: HIGH

Affected dependencies:
  - com.fasterxml.jackson.core:jackson-databind:2.9.8 (transitive)

Recommended fix:
  - Upgrade com.fasterxml.jackson.core:jackson-databind to 2.9.10 or later

### CVE-2020-10673: jackson-databind mishandles the interaction between serialization gadgets and typing
- **Severity:** mandatory
- **Story Points:** 1
- **Files:** N/A

[CVE-2020-10673](https://github.com/advisories/GHSA-fqwf-pjwf-7vqv): jackson-databind mishandles the interaction between serialization gadgets and typing

Severity: HIGH

Affected dependencies:
  - com.fasterxml.jackson.core:jackson-databind:2.9.8 (transitive)
  - com.fasterxml.jackson.core:jackson-databind:2.9.8 (transitive)

Recommended fix:
  - Upgrade com.fasterxml.jackson.core:jackson-databind to 2.9.10.4 or later
  - Upgrade com.fasterxml.jackson.core:jackson-databind to 2.6.7.4 or later

### CVE-2020-9548: jackson-databind mishandles the interaction between serialization gadgets and typing
- **Severity:** mandatory
- **Story Points:** 1
- **Files:** N/A

[CVE-2020-9548](https://github.com/advisories/GHSA-p43x-xfjf-5jhr): jackson-databind mishandles the interaction between serialization gadgets and typing

Severity: CRITICAL

Affected dependencies:
  - com.fasterxml.jackson.core:jackson-databind:2.9.8 (transitive)
  - com.fasterxml.jackson.core:jackson-databind:2.9.8 (transitive)
  - com.fasterxml.jackson.core:jackson-databind:2.9.8 (transitive)

Recommended fix:
  - Upgrade com.fasterxml.jackson.core:jackson-databind to 2.9.10.4 or later
  - Upgrade com.fasterxml.jackson.core:jackson-databind to 2.8.11.6 or later
  - Upgrade com.fasterxml.jackson.core:jackson-databind to 2.7.9.7 or later

### CVE-2019-14892: Polymorphic deserialization of malicious object in jackson-databind
- **Severity:** mandatory
- **Story Points:** 1
- **Files:** N/A

[CVE-2019-14892](https://github.com/advisories/GHSA-cf6r-3wgc-h863): Polymorphic deserialization of malicious object in jackson-databind

Severity: HIGH

Affected dependencies:
  - com.fasterxml.jackson.core:jackson-databind:2.9.8 (transitive)
  - com.fasterxml.jackson.core:jackson-databind:2.9.8 (transitive)
  - com.fasterxml.jackson.core:jackson-databind:2.9.8 (transitive)

Recommended fix:
  - Upgrade com.fasterxml.jackson.core:jackson-databind to 2.6.7.3 or later
  - Upgrade com.fasterxml.jackson.core:jackson-databind to 2.9.10 or later
  - Upgrade com.fasterxml.jackson.core:jackson-databind to 2.8.11.5 or later

### CVE-2020-10968: jackson-databind mishandles the interaction between serialization gadgets and typing
- **Severity:** mandatory
- **Story Points:** 1
- **Files:** N/A

[CVE-2020-10968](https://github.com/advisories/GHSA-rf6r-2c4q-2vwg): jackson-databind mishandles the interaction between serialization gadgets and typing

Severity: HIGH

Affected dependencies:
  - com.fasterxml.jackson.core:jackson-databind:2.9.8 (transitive)

Recommended fix:
  - Upgrade com.fasterxml.jackson.core:jackson-databind to 2.9.10.4 or later

### CVE-2020-11111: jackson-databind mishandles the interaction between serialization gadgets and typing
- **Severity:** mandatory
- **Story Points:** 1
- **Files:** N/A

[CVE-2020-11111](https://github.com/advisories/GHSA-v3xw-c963-f5hc): jackson-databind mishandles the interaction between serialization gadgets and typing

Severity: HIGH

Affected dependencies:
  - com.fasterxml.jackson.core:jackson-databind:2.9.8 (transitive)

Recommended fix:
  - Upgrade com.fasterxml.jackson.core:jackson-databind to 2.9.10.4 or later

### CVE-2020-11113: jackson-databind mishandles the interaction between serialization gadgets and typing
- **Severity:** mandatory
- **Story Points:** 1
- **Files:** N/A

[CVE-2020-11113](https://github.com/advisories/GHSA-9vvp-fxw6-jcxr): jackson-databind mishandles the interaction between serialization gadgets and typing

Severity: HIGH

Affected dependencies:
  - com.fasterxml.jackson.core:jackson-databind:2.9.8 (transitive)

Recommended fix:
  - Upgrade com.fasterxml.jackson.core:jackson-databind to 2.9.10.4 or later

### CVE-2020-11619: jackson-databind mishandles the interaction between serialization gadgets and typing
- **Severity:** mandatory
- **Story Points:** 1
- **Files:** N/A

[CVE-2020-11619](https://github.com/advisories/GHSA-27xj-rqx5-2255): jackson-databind mishandles the interaction between serialization gadgets and typing

Severity: HIGH

Affected dependencies:
  - com.fasterxml.jackson.core:jackson-databind:2.9.8 (transitive)

Recommended fix:
  - Upgrade com.fasterxml.jackson.core:jackson-databind to 2.9.10.4 or later

### CVE-2020-10969: jackson-databind mishandles the interaction between serialization gadgets and typing
- **Severity:** mandatory
- **Story Points:** 1
- **Files:** N/A

[CVE-2020-10969](https://github.com/advisories/GHSA-758m-v56v-grj4): jackson-databind mishandles the interaction between serialization gadgets and typing

Severity: HIGH

Affected dependencies:
  - com.fasterxml.jackson.core:jackson-databind:2.9.8 (transitive)

Recommended fix:
  - Upgrade com.fasterxml.jackson.core:jackson-databind to 2.9.10.4 or later

### CVE-2020-9546: jackson-databind mishandles the interaction between serialization gadgets and typing
- **Severity:** mandatory
- **Story Points:** 1
- **Files:** N/A

[CVE-2020-9546](https://github.com/advisories/GHSA-5p34-5m6p-p58g): jackson-databind mishandles the interaction between serialization gadgets and typing

Severity: CRITICAL

Affected dependencies:
  - com.fasterxml.jackson.core:jackson-databind:2.9.8 (transitive)

Recommended fix:
  - Upgrade com.fasterxml.jackson.core:jackson-databind to 2.9.10.4 or later

### CVE-2020-11620: jackson-databind mishandles the interaction between serialization gadgets and typing
- **Severity:** mandatory
- **Story Points:** 1
- **Files:** N/A

[CVE-2020-11620](https://github.com/advisories/GHSA-h4rc-386g-6m85): jackson-databind mishandles the interaction between serialization gadgets and typing

Severity: HIGH

Affected dependencies:
  - com.fasterxml.jackson.core:jackson-databind:2.9.8 (transitive)

Recommended fix:
  - Upgrade com.fasterxml.jackson.core:jackson-databind to 2.9.10.4 or later

### CVE-2020-10672: jackson-databind mishandles the interaction between serialization gadgets and typing
- **Severity:** mandatory
- **Story Points:** 1
- **Files:** N/A

[CVE-2020-10672](https://github.com/advisories/GHSA-95cm-88f5-f2c7): jackson-databind mishandles the interaction between serialization gadgets and typing

Severity: HIGH

Affected dependencies:
  - com.fasterxml.jackson.core:jackson-databind:2.9.8 (transitive)

Recommended fix:
  - Upgrade com.fasterxml.jackson.core:jackson-databind to 2.9.10.4 or later

### CVE-2020-8840: Deserialization of Untrusted Data in jackson-databind
- **Severity:** mandatory
- **Story Points:** 1
- **Files:** N/A

[CVE-2020-8840](https://github.com/advisories/GHSA-4w82-r329-3q67): Deserialization of Untrusted Data in jackson-databind

Severity: CRITICAL

Affected dependencies:
  - com.fasterxml.jackson.core:jackson-databind:2.9.8 (transitive)
  - com.fasterxml.jackson.core:jackson-databind:2.9.8 (transitive)
  - com.fasterxml.jackson.core:jackson-databind:2.9.8 (transitive)
  - com.fasterxml.jackson.core:jackson-databind:2.9.8 (transitive)

Recommended fix:
  - Upgrade com.fasterxml.jackson.core:jackson-databind to 2.7.9.7 or later
  - Upgrade com.fasterxml.jackson.core:jackson-databind to 2.8.11.5 or later
  - Upgrade com.fasterxml.jackson.core:jackson-databind to 2.9.10.3 or later
  - Upgrade com.fasterxml.jackson.core:jackson-databind to 2.6.7.4 or later

### CVE-2019-20330: Deserialization of Untrusted Data in jackson-databind
- **Severity:** mandatory
- **Story Points:** 1
- **Files:** N/A

[CVE-2019-20330](https://github.com/advisories/GHSA-gww7-p5w4-wrfv): Deserialization of Untrusted Data in jackson-databind

Severity: CRITICAL

Affected dependencies:
  - com.fasterxml.jackson.core:jackson-databind:2.9.8 (transitive)
  - com.fasterxml.jackson.core:jackson-databind:2.9.8 (transitive)
  - com.fasterxml.jackson.core:jackson-databind:2.9.8 (transitive)
  - com.fasterxml.jackson.core:jackson-databind:2.9.8 (transitive)

Recommended fix:
  - Upgrade com.fasterxml.jackson.core:jackson-databind to 2.7.9.7 or later
  - Upgrade com.fasterxml.jackson.core:jackson-databind to 2.8.11.5 or later
  - Upgrade com.fasterxml.jackson.core:jackson-databind to 2.9.10.2 or later
  - Upgrade com.fasterxml.jackson.core:jackson-databind to 2.6.7.4 or later

### CVE-2019-17531: jackson-databind polymorphic typing issue
- **Severity:** mandatory
- **Story Points:** 1
- **Files:** N/A

[CVE-2019-17531](https://github.com/advisories/GHSA-gjmw-vf9h-g25v): jackson-databind polymorphic typing issue

Severity: CRITICAL

Affected dependencies:
  - com.fasterxml.jackson.core:jackson-databind:2.9.8 (transitive)
  - com.fasterxml.jackson.core:jackson-databind:2.9.8 (transitive)
  - com.fasterxml.jackson.core:jackson-databind:2.9.8 (transitive)

Recommended fix:
  - Upgrade com.fasterxml.jackson.core:jackson-databind to 2.9.10.1 or later
  - Upgrade com.fasterxml.jackson.core:jackson-databind to 2.8.11.5 or later
  - Upgrade com.fasterxml.jackson.core:jackson-databind to 2.6.7.3 or later

### CVE-2019-16943: jackson-databind polymorphic typing issue
- **Severity:** mandatory
- **Story Points:** 1
- **Files:** N/A

[CVE-2019-16943](https://github.com/advisories/GHSA-fmmc-742q-jg75): jackson-databind polymorphic typing issue

Severity: CRITICAL

Affected dependencies:
  - com.fasterxml.jackson.core:jackson-databind:2.9.8 (transitive)
  - com.fasterxml.jackson.core:jackson-databind:2.9.8 (transitive)
  - com.fasterxml.jackson.core:jackson-databind:2.9.8 (transitive)

Recommended fix:
  - Upgrade com.fasterxml.jackson.core:jackson-databind to 2.9.10.1 or later
  - Upgrade com.fasterxml.jackson.core:jackson-databind to 2.8.11.5 or later
  - Upgrade com.fasterxml.jackson.core:jackson-databind to 2.6.7.3 or later

### CVE-2019-16942: Polymorphic Typing in FasterXML jackson-databind
- **Severity:** mandatory
- **Story Points:** 1
- **Files:** N/A

[CVE-2019-16942](https://github.com/advisories/GHSA-mx7p-6679-8g3q): Polymorphic Typing in FasterXML jackson-databind

Severity: CRITICAL

Affected dependencies:
  - com.fasterxml.jackson.core:jackson-databind:2.9.8 (transitive)
  - com.fasterxml.jackson.core:jackson-databind:2.9.8 (transitive)
  - com.fasterxml.jackson.core:jackson-databind:2.9.8 (transitive)

Recommended fix:
  - Upgrade com.fasterxml.jackson.core:jackson-databind to 2.9.10.1 or later
  - Upgrade com.fasterxml.jackson.core:jackson-databind to 2.6.7.3 or later
  - Upgrade com.fasterxml.jackson.core:jackson-databind to 2.8.11.5 or later

### CVE-2019-16335: Polymorphic Typing issue in FasterXML jackson-databind
- **Severity:** mandatory
- **Story Points:** 1
- **Files:** N/A

[CVE-2019-16335](https://github.com/advisories/GHSA-85cw-hj65-qqv9): Polymorphic Typing issue in FasterXML jackson-databind

Severity: CRITICAL

Affected dependencies:
  - com.fasterxml.jackson.core:jackson-databind:2.9.8 (transitive)
  - com.fasterxml.jackson.core:jackson-databind:2.9.8 (transitive)
  - com.fasterxml.jackson.core:jackson-databind:2.9.8 (transitive)

Recommended fix:
  - Upgrade com.fasterxml.jackson.core:jackson-databind to 2.9.10 or later
  - Upgrade com.fasterxml.jackson.core:jackson-databind to 2.8.11.5 or later
  - Upgrade com.fasterxml.jackson.core:jackson-databind to 2.6.7.3 or later

### CVE-2019-14540: Polymorphic Typing issue in FasterXML jackson-databind
- **Severity:** mandatory
- **Story Points:** 1
- **Files:** N/A

[CVE-2019-14540](https://github.com/advisories/GHSA-h822-r4r5-v8jg): Polymorphic Typing issue in FasterXML jackson-databind

Severity: CRITICAL

Affected dependencies:
  - com.fasterxml.jackson.core:jackson-databind:2.9.8 (transitive)
  - com.fasterxml.jackson.core:jackson-databind:2.9.8 (transitive)
  - com.fasterxml.jackson.core:jackson-databind:2.9.8 (transitive)

Recommended fix:
  - Upgrade com.fasterxml.jackson.core:jackson-databind to 2.9.10 or later
  - Upgrade com.fasterxml.jackson.core:jackson-databind to 2.8.11.5 or later
  - Upgrade com.fasterxml.jackson.core:jackson-databind to 2.6.7.3 or later

### CVE-2019-14439: Deserialization of untrusted data in FasterXML jackson-databind
- **Severity:** mandatory
- **Story Points:** 1
- **Files:** N/A

[CVE-2019-14439](https://github.com/advisories/GHSA-gwp4-hfv6-p7hw): Deserialization of untrusted data in FasterXML jackson-databind

Severity: HIGH

Affected dependencies:
  - com.fasterxml.jackson.core:jackson-databind:2.9.8 (transitive)
  - com.fasterxml.jackson.core:jackson-databind:2.9.8 (transitive)
  - com.fasterxml.jackson.core:jackson-databind:2.9.8 (transitive)
  - com.fasterxml.jackson.core:jackson-databind:2.9.8 (transitive)

Recommended fix:
  - Upgrade com.fasterxml.jackson.core:jackson-databind to 2.9.9.2 or later
  - Upgrade com.fasterxml.jackson.core:jackson-databind to 2.7.9.6 or later
  - Upgrade com.fasterxml.jackson.core:jackson-databind to 2.6.7.3 or later
  - Upgrade com.fasterxml.jackson.core:jackson-databind to 2.8.11.4 or later

### CVE-2019-14379: Deserialization of untrusted data in FasterXML jackson-databind
- **Severity:** mandatory
- **Story Points:** 1
- **Files:** N/A

[CVE-2019-14379](https://github.com/advisories/GHSA-6fpp-rgj9-8rwc): Deserialization of untrusted data in FasterXML jackson-databind

Severity: CRITICAL

Affected dependencies:
  - com.fasterxml.jackson.core:jackson-databind:2.9.8 (transitive)
  - com.fasterxml.jackson.core:jackson-databind:2.9.8 (transitive)
  - com.fasterxml.jackson.core:jackson-databind:2.9.8 (transitive)

Recommended fix:
  - Upgrade com.fasterxml.jackson.core:jackson-databind to 2.9.9.2 or later
  - Upgrade com.fasterxml.jackson.core:jackson-databind to 2.8.11.4 or later
  - Upgrade com.fasterxml.jackson.core:jackson-databind to 2.7.9.6 or later

### CVE-2019-12086: Information exposure in FasterXML jackson-databind
- **Severity:** mandatory
- **Story Points:** 1
- **Files:** N/A

[CVE-2019-12086](https://github.com/advisories/GHSA-5ww9-j83m-q7qx): Information exposure in FasterXML jackson-databind

Severity: HIGH

Affected dependencies:
  - com.fasterxml.jackson.core:jackson-databind:2.9.8 (transitive)
  - com.fasterxml.jackson.core:jackson-databind:2.9.8 (transitive)
  - com.fasterxml.jackson.core:jackson-databind:2.9.8 (transitive)
  - com.fasterxml.jackson.core:jackson-databind:2.9.8 (transitive)

Recommended fix:
  - Upgrade com.fasterxml.jackson.core:jackson-databind to 2.9.9 or later
  - Upgrade com.fasterxml.jackson.core:jackson-databind to 2.8.11.4 or later
  - Upgrade com.fasterxml.jackson.core:jackson-databind to 2.7.9.6 or later
  - Upgrade com.fasterxml.jackson.core:jackson-databind to 2.6.7.3 or later

### CVE-2018-18531: Use of Insufficiently Random Values in penggle:kaptcha
- **Severity:** mandatory
- **Story Points:** 1
- **Files:** pom.xml:152

[CVE-2018-18531](https://github.com/advisories/GHSA-8q89-pwhh-7wfq): Use of Insufficiently Random Values in penggle:kaptcha

Severity: CRITICAL

Affected dependencies:
  - com.github.penggle:kaptcha:2.3.2 (declared at pom.xml:152)

### CVE-2025-48734: Apache Commons Improper Access Control vulnerability
- **Severity:** mandatory
- **Story Points:** 1
- **Files:** N/A

[CVE-2025-48734](https://github.com/advisories/GHSA-wxr5-93ph-8wr9): Apache Commons Improper Access Control vulnerability

Severity: HIGH

Affected dependencies:
  - commons-beanutils:commons-beanutils:1.9.4 (transitive)

Recommended fix:
  - Upgrade commons-beanutils:commons-beanutils to 1.11.0 or later

### CVE-2024-47072: XStream is vulnerable to a Denial of Service attack due to stack overflow from a manipulated binary input stream
- **Severity:** mandatory
- **Story Points:** 1
- **Files:** N/A

[CVE-2024-47072](https://github.com/advisories/GHSA-hfq9-hggm-c56q): XStream is vulnerable to a Denial of Service attack due to stack overflow from a manipulated binary input stream

Severity: HIGH

Affected dependencies:
  - com.thoughtworks.xstream:xstream:1.4.17 (transitive)

Recommended fix:
  - Upgrade com.thoughtworks.xstream:xstream to 1.4.21 or later

### CVE-2024-47554: Apache Commons IO: Possible denial of service attack on untrusted input to XmlStreamReader
- **Severity:** mandatory
- **Story Points:** 1
- **Files:** N/A

[CVE-2024-47554](https://github.com/advisories/GHSA-78wr-2p64-hpwj): Apache Commons IO: Possible denial of service attack on untrusted input to XmlStreamReader

Severity: HIGH

Affected dependencies:
  - commons-io:commons-io:2.7 (transitive)

Recommended fix:
  - Upgrade commons-io:commons-io to 2.14.0 or later

### CVE-2024-7254: protobuf-java has potential Denial of Service issue
- **Severity:** mandatory
- **Story Points:** 1
- **Files:** N/A

[CVE-2024-7254](https://github.com/advisories/GHSA-735f-pc8j-v9w8): protobuf-java has potential Denial of Service issue

Severity: HIGH

Affected dependencies:
  - com.google.protobuf:protobuf-java:3.11.4 (transitive)
  - com.google.protobuf:protobuf-java:3.11.4 (transitive)
  - com.google.protobuf:protobuf-java:3.11.4 (transitive)

Recommended fix:
  - Upgrade com.google.protobuf:protobuf-java to 3.25.5 or later
  - Upgrade com.google.protobuf:protobuf-java to 4.27.5 or later
  - Upgrade com.google.protobuf:protobuf-java to 4.28.2 or later

### CVE-2022-40151: XStream can cause a Denial of Service by injecting deeply nested objects raising a stack overflow
- **Severity:** mandatory
- **Story Points:** 1
- **Files:** N/A

[CVE-2022-40151](https://github.com/advisories/GHSA-f8cc-g7j8-xxpm): XStream can cause a Denial of Service by injecting deeply nested objects raising a stack overflow

Severity: HIGH

Affected dependencies:
  - com.thoughtworks.xstream:xstream:1.4.17 (transitive)

Recommended fix:
  - Upgrade com.thoughtworks.xstream:xstream to 1.4.20 or later

### CVE-2022-41966: XStream can cause Denial of Service via stack overflow
- **Severity:** mandatory
- **Story Points:** 1
- **Files:** N/A

[CVE-2022-41966](https://github.com/advisories/GHSA-j563-grx4-pjpv): XStream can cause Denial of Service via stack overflow

Severity: HIGH

Affected dependencies:
  - com.thoughtworks.xstream:xstream:1.4.17 (transitive)

Recommended fix:
  - Upgrade com.thoughtworks.xstream:xstream to 1.4.20 or later

### CVE-2022-3510: Protobuf Java vulnerable to Uncontrolled Resource Consumption
- **Severity:** mandatory
- **Story Points:** 1
- **Files:** N/A

[CVE-2022-3510](https://github.com/advisories/GHSA-4gg5-vx3j-xwc7): Protobuf Java vulnerable to Uncontrolled Resource Consumption

Severity: HIGH

Affected dependencies:
  - com.google.protobuf:protobuf-java:3.11.4 (transitive)
  - com.google.protobuf:protobuf-java:3.11.4 (transitive)
  - com.google.protobuf:protobuf-java:3.11.4 (transitive)
  - com.google.protobuf:protobuf-java:3.11.4 (transitive)

Recommended fix:
  - Upgrade com.google.protobuf:protobuf-java to 3.19.6 or later
  - Upgrade com.google.protobuf:protobuf-java to 3.20.3 or later
  - Upgrade com.google.protobuf:protobuf-java to 3.21.7 or later
  - Upgrade com.google.protobuf:protobuf-java to 3.16.3 or later

### CVE-2022-3509: Protobuf Java vulnerable to Uncontrolled Resource Consumption
- **Severity:** mandatory
- **Story Points:** 1
- **Files:** N/A

[CVE-2022-3509](https://github.com/advisories/GHSA-g5ww-5jh7-63cx): Protobuf Java vulnerable to Uncontrolled Resource Consumption

Severity: HIGH

Affected dependencies:
  - com.google.protobuf:protobuf-java:3.11.4 (transitive)
  - com.google.protobuf:protobuf-java:3.11.4 (transitive)
  - com.google.protobuf:protobuf-java:3.11.4 (transitive)
  - com.google.protobuf:protobuf-java:3.11.4 (transitive)

Recommended fix:
  - Upgrade com.google.protobuf:protobuf-java to 3.19.6 or later
  - Upgrade com.google.protobuf:protobuf-java to 3.20.3 or later
  - Upgrade com.google.protobuf:protobuf-java to 3.21.7 or later
  - Upgrade com.google.protobuf:protobuf-java to 3.16.3 or later

### CVE-2021-0341: Square OkHttp can accept the wrong certificate
- **Severity:** mandatory
- **Story Points:** 1
- **Files:** N/A

[CVE-2021-0341](https://github.com/advisories/GHSA-3cqm-mf7h-prrj): Square OkHttp can accept the wrong certificate

Severity: HIGH

Affected dependencies:
  - com.squareup.okhttp3:okhttp:3.14.4 (transitive)

Recommended fix:
  - Upgrade com.squareup.okhttp3:okhttp to 4.9.2 or later

### CVE-2015-7501: Deserialization of Untrusted Data in Apache commons collections
- **Severity:** mandatory
- **Story Points:** 1
- **Files:** N/A

[CVE-2015-7501](https://github.com/advisories/GHSA-fjq5-5j5f-mvxh): Deserialization of Untrusted Data in Apache commons collections

Severity: CRITICAL

Affected dependencies:
  - commons-collections:commons-collections:3.2.2 (transitive)

Recommended fix:
  - Upgrade commons-collections:commons-collections to 3.2.2 or later

### CVE-2021-43859: Denial of Service by injecting highly recursive collections or maps in XStream
- **Severity:** mandatory
- **Story Points:** 1
- **Files:** N/A

[CVE-2021-43859](https://github.com/advisories/GHSA-rmr5-cpv2-vgjf): Denial of Service by injecting highly recursive collections or maps in XStream

Severity: HIGH

Affected dependencies:
  - com.thoughtworks.xstream:xstream:1.4.17 (transitive)

Recommended fix:
  - Upgrade com.thoughtworks.xstream:xstream to 1.4.19 or later

### CVE-2021-22569: A potential Denial of Service issue in protobuf-java
- **Severity:** mandatory
- **Story Points:** 1
- **Files:** N/A

[CVE-2021-22569](https://github.com/advisories/GHSA-wrvw-hg22-4m67): A potential Denial of Service issue in protobuf-java

Severity: HIGH

Affected dependencies:
  - com.google.protobuf:protobuf-java:3.11.4 (transitive)
  - com.google.protobuf:protobuf-java:3.11.4 (transitive)
  - com.google.protobuf:protobuf-java:3.11.4 (transitive)

Recommended fix:
  - Upgrade com.google.protobuf:protobuf-java to 3.16.1 or later
  - Upgrade com.google.protobuf:protobuf-java to 3.18.2 or later
  - Upgrade com.google.protobuf:protobuf-java to 3.19.2 or later

### CVE-2021-39139: XStream is vulnerable to an Arbitrary Code Execution attack
- **Severity:** mandatory
- **Story Points:** 1
- **Files:** N/A

[CVE-2021-39139](https://github.com/advisories/GHSA-64xx-cq4q-mf44): XStream is vulnerable to an Arbitrary Code Execution attack

Severity: HIGH

Affected dependencies:
  - com.thoughtworks.xstream:xstream:1.4.17 (transitive)

Recommended fix:
  - Upgrade com.thoughtworks.xstream:xstream to 1.4.18 or later

### CVE-2021-39141: XStream is vulnerable to an Arbitrary Code Execution attack
- **Severity:** mandatory
- **Story Points:** 1
- **Files:** N/A

[CVE-2021-39141](https://github.com/advisories/GHSA-g5w6-mrj7-75h2): XStream is vulnerable to an Arbitrary Code Execution attack

Severity: HIGH

Affected dependencies:
  - com.thoughtworks.xstream:xstream:1.4.17 (transitive)

Recommended fix:
  - Upgrade com.thoughtworks.xstream:xstream to 1.4.18 or later

### CVE-2021-39144: XStream is vulnerable to a Remote Command Execution attack
- **Severity:** mandatory
- **Story Points:** 1
- **Files:** N/A

[CVE-2021-39144](https://github.com/advisories/GHSA-j9h8-phrw-h4fh): XStream is vulnerable to a Remote Command Execution attack

Severity: HIGH

Affected dependencies:
  - com.thoughtworks.xstream:xstream:1.4.17 (transitive)

Recommended fix:
  - Upgrade com.thoughtworks.xstream:xstream to 1.4.18 or later

### CVE-2021-39145: XStream is vulnerable to an Arbitrary Code Execution attack
- **Severity:** mandatory
- **Story Points:** 1
- **Files:** N/A

[CVE-2021-39145](https://github.com/advisories/GHSA-8jrj-525p-826v): XStream is vulnerable to an Arbitrary Code Execution attack

Severity: HIGH

Affected dependencies:
  - com.thoughtworks.xstream:xstream:1.4.17 (transitive)

Recommended fix:
  - Upgrade com.thoughtworks.xstream:xstream to 1.4.18 or later

### CVE-2021-39146: XStream is vulnerable to an Arbitrary Code Execution attack
- **Severity:** mandatory
- **Story Points:** 1
- **Files:** N/A

[CVE-2021-39146](https://github.com/advisories/GHSA-p8pq-r894-fm8f): XStream is vulnerable to an Arbitrary Code Execution attack

Severity: HIGH

Affected dependencies:
  - com.thoughtworks.xstream:xstream:1.4.17 (transitive)

Recommended fix:
  - Upgrade com.thoughtworks.xstream:xstream to 1.4.18 or later

### CVE-2021-39147: XStream is vulnerable to an Arbitrary Code Execution attack
- **Severity:** mandatory
- **Story Points:** 1
- **Files:** N/A

[CVE-2021-39147](https://github.com/advisories/GHSA-h7v4-7xg3-hxcc): XStream is vulnerable to an Arbitrary Code Execution attack

Severity: HIGH

Affected dependencies:
  - com.thoughtworks.xstream:xstream:1.4.17 (transitive)

Recommended fix:
  - Upgrade com.thoughtworks.xstream:xstream to 1.4.18 or later

### CVE-2021-39148: XStream is vulnerable to an Arbitrary Code Execution attack
- **Severity:** mandatory
- **Story Points:** 1
- **Files:** N/A

[CVE-2021-39148](https://github.com/advisories/GHSA-qrx8-8545-4wg2): XStream is vulnerable to an Arbitrary Code Execution attack

Severity: HIGH

Affected dependencies:
  - com.thoughtworks.xstream:xstream:1.4.17 (transitive)

Recommended fix:
  - Upgrade com.thoughtworks.xstream:xstream to 1.4.18 or later

### CVE-2021-39149: XStream is vulnerable to an Arbitrary Code Execution attack
- **Severity:** mandatory
- **Story Points:** 1
- **Files:** N/A

[CVE-2021-39149](https://github.com/advisories/GHSA-3ccq-5vw3-2p6x): XStream is vulnerable to an Arbitrary Code Execution attack

Severity: HIGH

Affected dependencies:
  - com.thoughtworks.xstream:xstream:1.4.17 (transitive)

Recommended fix:
  - Upgrade com.thoughtworks.xstream:xstream to 1.4.18 or later

### CVE-2021-39150: A Server-Side Forgery Request can be activated unmarshalling with XStream to access data streams from an arbitrary URL referencing a resource in an intranet or the local host
- **Severity:** mandatory
- **Story Points:** 1
- **Files:** N/A

[CVE-2021-39150](https://github.com/advisories/GHSA-cxfm-5m4g-x7xp): A Server-Side Forgery Request can be activated unmarshalling with XStream to access data streams from an arbitrary URL referencing a resource in an intranet or the local host

Severity: HIGH

Affected dependencies:
  - com.thoughtworks.xstream:xstream:1.4.17 (transitive)

Recommended fix:
  - Upgrade com.thoughtworks.xstream:xstream to 1.4.18 or later

### CVE-2021-39151: XStream is vulnerable to an Arbitrary Code Execution attack
- **Severity:** mandatory
- **Story Points:** 1
- **Files:** N/A

[CVE-2021-39151](https://github.com/advisories/GHSA-hph2-m3g5-xxv4): XStream is vulnerable to an Arbitrary Code Execution attack

Severity: HIGH

Affected dependencies:
  - com.thoughtworks.xstream:xstream:1.4.17 (transitive)

Recommended fix:
  - Upgrade com.thoughtworks.xstream:xstream to 1.4.18 or later

### CVE-2021-39152: A Server-Side Forgery Request can be activated unmarshalling with XStream to access data streams from an arbitrary URL referencing a resource in an intranet or the local host
- **Severity:** mandatory
- **Story Points:** 1
- **Files:** N/A

[CVE-2021-39152](https://github.com/advisories/GHSA-xw4p-crpj-vjx2): A Server-Side Forgery Request can be activated unmarshalling with XStream to access data streams from an arbitrary URL referencing a resource in an intranet or the local host

Severity: HIGH

Affected dependencies:
  - com.thoughtworks.xstream:xstream:1.4.17 (transitive)

Recommended fix:
  - Upgrade com.thoughtworks.xstream:xstream to 1.4.18 or later

### CVE-2021-39153: XStream is vulnerable to an Arbitrary Code Execution attack
- **Severity:** mandatory
- **Story Points:** 1
- **Files:** N/A

[CVE-2021-39153](https://github.com/advisories/GHSA-2q8x-2p7f-574v): XStream is vulnerable to an Arbitrary Code Execution attack

Severity: HIGH

Affected dependencies:
  - com.thoughtworks.xstream:xstream:1.4.17 (transitive)

Recommended fix:
  - Upgrade com.thoughtworks.xstream:xstream to 1.4.18 or later

### CVE-2021-39154: XStream is vulnerable to an Arbitrary Code Execution attack
- **Severity:** mandatory
- **Story Points:** 1
- **Files:** N/A

[CVE-2021-39154](https://github.com/advisories/GHSA-6w62-hx7r-mw68): XStream is vulnerable to an Arbitrary Code Execution attack

Severity: HIGH

Affected dependencies:
  - com.thoughtworks.xstream:xstream:1.4.17 (transitive)

Recommended fix:
  - Upgrade com.thoughtworks.xstream:xstream to 1.4.18 or later

### CVE-2015-6420: Insecure Deserialization in Apache Commons Collection
- **Severity:** mandatory
- **Story Points:** 1
- **Files:** N/A

[CVE-2015-6420](https://github.com/advisories/GHSA-6hgm-866r-3cjv): Insecure Deserialization in Apache Commons Collection

Severity: HIGH

Affected dependencies:
  - commons-collections:commons-collections:3.2.2 (transitive)

Recommended fix:
  - Upgrade commons-collections:commons-collections to 3.2.2 or later

### CVE-2026-49268: Apache Shiro: LDAP DN Injection in DefaultLdapRealm
- **Severity:** mandatory
- **Story Points:** 1
- **Files:** N/A

[CVE-2026-49268](https://github.com/advisories/GHSA-x96m-rh44-vgv8): Apache Shiro: LDAP DN Injection in DefaultLdapRealm

Severity: HIGH

Affected dependencies:
  - org.apache.shiro:shiro-core:1.6.0 (transitive)
  - org.apache.shiro:shiro-core:1.6.0 (transitive)

Recommended fix:
  - Upgrade org.apache.shiro:shiro-core to 2.2.1 or later
  - Upgrade org.apache.shiro:shiro-core to 3.0.0-alpha-2 or later

### CVE-2023-22102: MySQL Connectors takeover vulnerability
- **Severity:** mandatory
- **Story Points:** 1
- **Files:** litemall-db/pom.xml:25

[CVE-2023-22102](https://github.com/advisories/GHSA-m6vm-37g8-gqvh): MySQL Connectors takeover vulnerability

Severity: HIGH

Affected dependencies:
  - mysql:mysql-connector-java:8.0.28 (declared at litemall-db/pom.xml:25)

### CVE-2023-1370: json-smart Uncontrolled Recursion vulnerability
- **Severity:** mandatory
- **Story Points:** 1
- **Files:** N/A

[CVE-2023-1370](https://github.com/advisories/GHSA-493p-pfq6-5258): json-smart Uncontrolled Recursion vulnerability

Severity: HIGH

Affected dependencies:
  - net.minidev:json-smart:2.3 (transitive)

Recommended fix:
  - Upgrade net.minidev:json-smart to 2.4.9 or later

### CVE-2022-40664: Apache Shiro Authentication Bypass vulnerability
- **Severity:** mandatory
- **Story Points:** 1
- **Files:** N/A

[CVE-2022-40664](https://github.com/advisories/GHSA-45x9-q6vj-cqgq): Apache Shiro Authentication Bypass vulnerability

Severity: CRITICAL

Affected dependencies:
  - org.apache.shiro:shiro-core:1.6.0 (transitive)

Recommended fix:
  - Upgrade org.apache.shiro:shiro-core to 1.10.0 or later

### CVE-2022-32532: Improper Authorization in Apache Shiro
- **Severity:** mandatory
- **Story Points:** 1
- **Files:** N/A

[CVE-2022-32532](https://github.com/advisories/GHSA-4cf5-xmhp-3xj7): Improper Authorization in Apache Shiro

Severity: CRITICAL

Affected dependencies:
  - org.apache.shiro:shiro-core:1.6.0 (transitive)

Recommended fix:
  - Upgrade org.apache.shiro:shiro-core to 1.9.1 or later

### CVE-2021-41303: Apache Shiro vulnerable to a specially crafted HTTP request causing an authentication bypass
- **Severity:** mandatory
- **Story Points:** 1
- **Files:** N/A

[CVE-2021-41303](https://github.com/advisories/GHSA-f6jp-j6w3-w9hm): Apache Shiro vulnerable to a specially crafted HTTP request causing an authentication bypass

Severity: CRITICAL

Affected dependencies:
  - org.apache.shiro:shiro-core:1.6.0 (transitive)

Recommended fix:
  - Upgrade org.apache.shiro:shiro-core to 1.8.0 or later

### CVE-2026-41284: Apache Tomcat: Unbounded read in WebDAV LOCK and  PROPFIND handling
- **Severity:** mandatory
- **Story Points:** 1
- **Files:** N/A

[CVE-2026-41284](https://github.com/advisories/GHSA-gx5v-xp9w-j4cg): Apache Tomcat: Unbounded read in WebDAV LOCK and  PROPFIND handling

Severity: HIGH

Affected dependencies:
  - org.apache.tomcat.embed:tomcat-embed-core:9.0.19 (transitive)
  - org.apache.tomcat.embed:tomcat-embed-core:9.0.19 (transitive)
  - org.apache.tomcat.embed:tomcat-embed-core:9.0.19 (transitive)

Recommended fix:
  - Upgrade org.apache.tomcat.embed:tomcat-embed-core to 9.0.118 or later
  - Upgrade org.apache.tomcat.embed:tomcat-embed-core to 10.1.55 or later
  - Upgrade org.apache.tomcat.embed:tomcat-embed-core to 11.0.22 or later

### CVE-2026-43512: Apache Tomcat - Digest authenticator will authenticate any unknown user
- **Severity:** mandatory
- **Story Points:** 1
- **Files:** N/A

[CVE-2026-43512](https://github.com/advisories/GHSA-h6fc-48rj-7qqh): Apache Tomcat - Digest authenticator will authenticate any unknown user

Severity: CRITICAL

Affected dependencies:
  - org.apache.tomcat.embed:tomcat-embed-core:9.0.19 (transitive)
  - org.apache.tomcat.embed:tomcat-embed-core:9.0.19 (transitive)
  - org.apache.tomcat.embed:tomcat-embed-core:9.0.19 (transitive)

Recommended fix:
  - Upgrade org.apache.tomcat.embed:tomcat-embed-core to 9.0.118 or later
  - Upgrade org.apache.tomcat.embed:tomcat-embed-core to 10.1.55 or later
  - Upgrade org.apache.tomcat.embed:tomcat-embed-core to 11.0.22 or later

### CVE-2026-43513: Apache Tomcat: LockOutRealm treats user names as case-sensitive
- **Severity:** mandatory
- **Story Points:** 1
- **Files:** N/A

[CVE-2026-43513](https://github.com/advisories/GHSA-5mp6-jrq3-r938): Apache Tomcat: LockOutRealm treats user names as case-sensitive

Severity: HIGH

Affected dependencies:
  - org.apache.tomcat.embed:tomcat-embed-core:9.0.19 (transitive)
  - org.apache.tomcat.embed:tomcat-embed-core:9.0.19 (transitive)
  - org.apache.tomcat.embed:tomcat-embed-core:9.0.19 (transitive)

Recommended fix:
  - Upgrade org.apache.tomcat.embed:tomcat-embed-core to 9.0.118 or later
  - Upgrade org.apache.tomcat.embed:tomcat-embed-core to 10.1.55 or later
  - Upgrade org.apache.tomcat.embed:tomcat-embed-core to 11.0.22 or later

### CVE-2026-43515: Apache Tomcat - Security constraints not correctly applied
- **Severity:** mandatory
- **Story Points:** 1
- **Files:** N/A

[CVE-2026-43515](https://github.com/advisories/GHSA-5m62-pw8w-7w9f): Apache Tomcat - Security constraints not correctly applied

Severity: CRITICAL

Affected dependencies:
  - org.apache.tomcat.embed:tomcat-embed-core:9.0.19 (transitive)
  - org.apache.tomcat.embed:tomcat-embed-core:9.0.19 (transitive)
  - org.apache.tomcat.embed:tomcat-embed-core:9.0.19 (transitive)

Recommended fix:
  - Upgrade org.apache.tomcat.embed:tomcat-embed-core to 9.0.118 or later
  - Upgrade org.apache.tomcat.embed:tomcat-embed-core to 10.1.55 or later
  - Upgrade org.apache.tomcat.embed:tomcat-embed-core to 11.0.22 or later

### CVE-2026-41293: Apache Tomcat - HTTP/2 request headers not validated
- **Severity:** mandatory
- **Story Points:** 1
- **Files:** N/A

[CVE-2026-41293](https://github.com/advisories/GHSA-r29c-68gh-xp6x): Apache Tomcat - HTTP/2 request headers not validated

Severity: CRITICAL

Affected dependencies:
  - org.apache.tomcat.embed:tomcat-embed-core:9.0.19 (transitive)
  - org.apache.tomcat.embed:tomcat-embed-core:9.0.19 (transitive)
  - org.apache.tomcat.embed:tomcat-embed-core:9.0.19 (transitive)

Recommended fix:
  - Upgrade org.apache.tomcat.embed:tomcat-embed-core to 9.0.118 or later
  - Upgrade org.apache.tomcat.embed:tomcat-embed-core to 10.1.55 or later
  - Upgrade org.apache.tomcat.embed:tomcat-embed-core to 11.0.22 or later

### CVE-2026-42498: Apache Tomcat - WebSocket authentication header exposure
- **Severity:** mandatory
- **Story Points:** 1
- **Files:** N/A

[CVE-2026-42498](https://github.com/advisories/GHSA-fv25-8xcx-gqjc): Apache Tomcat - WebSocket authentication header exposure

Severity: HIGH

Affected dependencies:
  - org.apache.tomcat.embed:tomcat-embed-core:9.0.19 (transitive)
  - org.apache.tomcat.embed:tomcat-embed-core:9.0.19 (transitive)
  - org.apache.tomcat.embed:tomcat-embed-core:9.0.19 (transitive)

Recommended fix:
  - Upgrade org.apache.tomcat.embed:tomcat-embed-core to 9.0.118 or later
  - Upgrade org.apache.tomcat.embed:tomcat-embed-core to 10.1.55 or later
  - Upgrade org.apache.tomcat.embed:tomcat-embed-core to 11.0.22 or later

### CVE-2026-24880: Apache Tomcat has an HTTP Request/Response Smuggling vulnerability
- **Severity:** mandatory
- **Story Points:** 1
- **Files:** N/A

[CVE-2026-24880](https://github.com/advisories/GHSA-563x-q5rq-57qp): Apache Tomcat has an HTTP Request/Response Smuggling vulnerability

Severity: HIGH

Affected dependencies:
  - org.apache.tomcat.embed:tomcat-embed-core:9.0.19 (transitive)
  - org.apache.tomcat.embed:tomcat-embed-core:9.0.19 (transitive)
  - org.apache.tomcat.embed:tomcat-embed-core:9.0.19 (transitive)

Recommended fix:
  - Upgrade org.apache.tomcat.embed:tomcat-embed-core to 9.0.116 or later
  - Upgrade org.apache.tomcat.embed:tomcat-embed-core to 10.1.52 or later
  - Upgrade org.apache.tomcat.embed:tomcat-embed-core to 11.0.20 or later

### CVE-2026-24400: AssertJ has XML External Entity (XXE) vulnerability when parsing untrusted XML via isXmlEqualTo assertion
- **Severity:** mandatory
- **Story Points:** 1
- **Files:** N/A

[CVE-2026-24400](https://github.com/advisories/GHSA-rqfh-9r24-8c9r): AssertJ has XML External Entity (XXE) vulnerability when parsing untrusted XML via isXmlEqualTo assertion

Severity: HIGH

Affected dependencies:
  - org.assertj:assertj-core:3.11.1 (transitive)

Recommended fix:
  - Upgrade org.assertj:assertj-core to 3.27.7 or later

### CVE-2025-55752: Apache Tomcat Vulnerable to Relative Path Traversal
- **Severity:** mandatory
- **Story Points:** 1
- **Files:** N/A

[CVE-2025-55752](https://github.com/advisories/GHSA-wmwf-9ccg-fff5): Apache Tomcat Vulnerable to Relative Path Traversal

Severity: HIGH

Affected dependencies:
  - org.apache.tomcat.embed:tomcat-embed-core:9.0.19 (transitive)
  - org.apache.tomcat.embed:tomcat-embed-core:9.0.19 (transitive)
  - org.apache.tomcat.embed:tomcat-embed-core:9.0.19 (transitive)
  - org.apache.tomcat.embed:tomcat-embed-core:9.0.19 (transitive)

Recommended fix:
  - Upgrade org.apache.tomcat.embed:tomcat-embed-core to 11.0.11 or later
  - Upgrade org.apache.tomcat.embed:tomcat-embed-core to 10.1.45 or later
  - Upgrade org.apache.tomcat.embed:tomcat-embed-core to 9.0.109 or later

### CVE-2025-48989: Apache Tomcat Improper Resource Shutdown or Release vulnerability
- **Severity:** mandatory
- **Story Points:** 1
- **Files:** N/A

[CVE-2025-48989](https://github.com/advisories/GHSA-gqp3-2cvr-x8m3): Apache Tomcat Improper Resource Shutdown or Release vulnerability

Severity: HIGH

Affected dependencies:
  - org.apache.tomcat.embed:tomcat-embed-core:9.0.19 (transitive)
  - org.apache.tomcat.embed:tomcat-embed-core:9.0.19 (transitive)
  - org.apache.tomcat.embed:tomcat-embed-core:9.0.19 (transitive)

Recommended fix:
  - Upgrade org.apache.tomcat.embed:tomcat-embed-core to 11.0.10 or later
  - Upgrade org.apache.tomcat.embed:tomcat-embed-core to 10.1.44 or later
  - Upgrade org.apache.tomcat.embed:tomcat-embed-core to 9.0.108 or later

### CVE-2025-53506: Apache Tomcat Coyote vulnerable to Denial of Service via excessive HTTP/2 streams
- **Severity:** mandatory
- **Story Points:** 1
- **Files:** N/A

[CVE-2025-53506](https://github.com/advisories/GHSA-25xr-qj8w-c4vf): Apache Tomcat Coyote vulnerable to Denial of Service via excessive HTTP/2 streams

Severity: HIGH

Affected dependencies:
  - org.apache.tomcat.embed:tomcat-embed-core:9.0.19 (transitive)
  - org.apache.tomcat.embed:tomcat-embed-core:9.0.19 (transitive)
  - org.apache.tomcat.embed:tomcat-embed-core:9.0.19 (transitive)
  - org.apache.tomcat.embed:tomcat-embed-core:9.0.19 (transitive)

Recommended fix:
  - Upgrade org.apache.tomcat.embed:tomcat-embed-core to 9.0.107 or later
  - Upgrade org.apache.tomcat.embed:tomcat-embed-core to 10.1.43 or later
  - Upgrade org.apache.tomcat.embed:tomcat-embed-core to 11.0.9 or later

### CVE-2025-52520: Apache Tomcat Catalina is vulnerable to DoS attack through bypassing of size limits
- **Severity:** mandatory
- **Story Points:** 1
- **Files:** N/A

[CVE-2025-52520](https://github.com/advisories/GHSA-wr62-c79q-cv37): Apache Tomcat Catalina is vulnerable to DoS attack through bypassing of size limits

Severity: HIGH

Affected dependencies:
  - org.apache.tomcat.embed:tomcat-embed-core:9.0.19 (transitive)
  - org.apache.tomcat.embed:tomcat-embed-core:9.0.19 (transitive)
  - org.apache.tomcat.embed:tomcat-embed-core:9.0.19 (transitive)
  - org.apache.tomcat.embed:tomcat-embed-core:9.0.19 (transitive)

Recommended fix:
  - Upgrade org.apache.tomcat.embed:tomcat-embed-core to 11.0.9 or later
  - Upgrade org.apache.tomcat.embed:tomcat-embed-core to 10.1.43 or later
  - Upgrade org.apache.tomcat.embed:tomcat-embed-core to 9.0.107 or later

### CVE-2025-48988: Apache Tomcat - DoS in multipart upload
- **Severity:** mandatory
- **Story Points:** 1
- **Files:** N/A

[CVE-2025-48988](https://github.com/advisories/GHSA-h3gc-qfqq-6h8f): Apache Tomcat - DoS in multipart upload

Severity: HIGH

Affected dependencies:
  - org.apache.tomcat.embed:tomcat-embed-core:9.0.19 (transitive)
  - org.apache.tomcat.embed:tomcat-embed-core:9.0.19 (transitive)
  - org.apache.tomcat.embed:tomcat-embed-core:9.0.19 (transitive)
  - org.apache.tomcat.embed:tomcat-embed-core:9.0.19 (transitive)

Recommended fix:
  - Upgrade org.apache.tomcat.embed:tomcat-embed-core to 11.0.8 or later
  - Upgrade org.apache.tomcat.embed:tomcat-embed-core to 10.1.42 or later
  - Upgrade org.apache.tomcat.embed:tomcat-embed-core to 9.0.106 or later

### CVE-2025-24813: Apache Tomcat: Potential RCE and/or information disclosure and/or information corruption with partial PUT
- **Severity:** mandatory
- **Story Points:** 1
- **Files:** N/A

[CVE-2025-24813](https://github.com/advisories/GHSA-83qj-6fr2-vhqg): Apache Tomcat: Potential RCE and/or information disclosure and/or information corruption with partial PUT

Severity: CRITICAL

Affected dependencies:
  - org.apache.tomcat.embed:tomcat-embed-core:9.0.19 (transitive)
  - org.apache.tomcat.embed:tomcat-embed-core:9.0.19 (transitive)
  - org.apache.tomcat.embed:tomcat-embed-core:9.0.19 (transitive)
  - org.apache.tomcat.embed:tomcat-embed-core:9.0.19 (transitive)

Recommended fix:
  - Upgrade org.apache.tomcat.embed:tomcat-embed-core to 11.0.3 or later
  - Upgrade org.apache.tomcat.embed:tomcat-embed-core to 10.1.35 or later
  - Upgrade org.apache.tomcat.embed:tomcat-embed-core to 9.0.99 or later

### CVE-2024-56337: Apache Tomcat Time-of-check Time-of-use (TOCTOU) Race Condition vulnerability
- **Severity:** mandatory
- **Story Points:** 1
- **Files:** N/A

[CVE-2024-56337](https://github.com/advisories/GHSA-27hp-xhwr-wr2m): Apache Tomcat Time-of-check Time-of-use (TOCTOU) Race Condition vulnerability

Severity: HIGH

Affected dependencies:
  - org.apache.tomcat.embed:tomcat-embed-core:9.0.19 (transitive)
  - org.apache.tomcat.embed:tomcat-embed-core:9.0.19 (transitive)
  - org.apache.tomcat.embed:tomcat-embed-core:9.0.19 (transitive)

Recommended fix:
  - Upgrade org.apache.tomcat.embed:tomcat-embed-core to 11.0.2 or later
  - Upgrade org.apache.tomcat.embed:tomcat-embed-core to 10.1.34 or later
  - Upgrade org.apache.tomcat.embed:tomcat-embed-core to 9.0.98 or later

### CVE-2024-50379: Apache Tomcat Time-of-check Time-of-use (TOCTOU) Race Condition vulnerability
- **Severity:** mandatory
- **Story Points:** 1
- **Files:** N/A

[CVE-2024-50379](https://github.com/advisories/GHSA-5j33-cvvr-w245): Apache Tomcat Time-of-check Time-of-use (TOCTOU) Race Condition vulnerability

Severity: HIGH

Affected dependencies:
  - org.apache.tomcat.embed:tomcat-embed-core:9.0.19 (transitive)
  - org.apache.tomcat.embed:tomcat-embed-core:9.0.19 (transitive)
  - org.apache.tomcat.embed:tomcat-embed-core:9.0.19 (transitive)
  - org.apache.tomcat.embed:tomcat-embed-core:9.0.19 (transitive)

Recommended fix:
  - Upgrade org.apache.tomcat.embed:tomcat-embed-core to 11.0.2 or later
  - Upgrade org.apache.tomcat.embed:tomcat-embed-core to 10.1.34 or later
  - Upgrade org.apache.tomcat.embed:tomcat-embed-core to 9.0.98 or later

### CVE-2024-34750: Apache Tomcat - Denial of Service
- **Severity:** mandatory
- **Story Points:** 1
- **Files:** N/A

[CVE-2024-34750](https://github.com/advisories/GHSA-wm9w-rjj3-j356): Apache Tomcat - Denial of Service

Severity: HIGH

Affected dependencies:
  - org.apache.tomcat.embed:tomcat-embed-core:9.0.19 (transitive)
  - org.apache.tomcat.embed:tomcat-embed-core:9.0.19 (transitive)
  - org.apache.tomcat.embed:tomcat-embed-core:9.0.19 (transitive)
  - org.apache.tomcat.embed:tomcat-embed-core:9.0.19 (transitive)

Recommended fix:
  - Upgrade org.apache.tomcat.embed:tomcat-embed-core to 11.0.0-M21 or later
  - Upgrade org.apache.tomcat.embed:tomcat-embed-core to 10.1.25 or later
  - Upgrade org.apache.tomcat.embed:tomcat-embed-core to 9.0.90 or later

### CVE-2023-46589: Apache Tomcat Improper Input Validation vulnerability
- **Severity:** mandatory
- **Story Points:** 1
- **Files:** N/A

[CVE-2023-46589](https://github.com/advisories/GHSA-fccv-jmmp-qg76): Apache Tomcat Improper Input Validation vulnerability

Severity: HIGH

Affected dependencies:
  - org.apache.tomcat.embed:tomcat-embed-core:9.0.19 (transitive)
  - org.apache.tomcat.embed:tomcat-embed-core:9.0.19 (transitive)
  - org.apache.tomcat.embed:tomcat-embed-core:9.0.19 (transitive)
  - org.apache.tomcat.embed:tomcat-embed-core:9.0.19 (transitive)

Recommended fix:
  - Upgrade org.apache.tomcat.embed:tomcat-embed-core to 11.0.0-M11 or later
  - Upgrade org.apache.tomcat.embed:tomcat-embed-core to 10.1.16 or later
  - Upgrade org.apache.tomcat.embed:tomcat-embed-core to 9.0.83 or later
  - Upgrade org.apache.tomcat.embed:tomcat-embed-core to 8.5.96 or later

### CVE-2023-5072: Java: DoS Vulnerability in JSON-JAVA
- **Severity:** mandatory
- **Story Points:** 1
- **Files:** N/A

[CVE-2023-5072](https://github.com/advisories/GHSA-4jq9-2xhw-jpx7): Java: DoS Vulnerability in JSON-JAVA

Severity: HIGH

Affected dependencies:
  - org.json:json:20170516 (transitive)

Recommended fix:
  - Upgrade org.json:json to 20231013 or later

### CVE-2023-34478: Path Traversal in Apache Shiro
- **Severity:** mandatory
- **Story Points:** 1
- **Files:** N/A

[CVE-2023-34478](https://github.com/advisories/GHSA-pmhc-2g4f-85cg): Path Traversal in Apache Shiro

Severity: CRITICAL

Affected dependencies:
  - org.apache.shiro:shiro-web:1.6.0 (transitive)
  - org.apache.shiro:shiro-web:1.6.0 (transitive)

Recommended fix:
  - Upgrade org.apache.shiro:shiro-web to 1.12.0 or later
  - Upgrade org.apache.shiro:shiro-web to 2.0.0-alpha-3 or later

### CVE-2023-24998: Apache Commons FileUpload denial of service vulnerability
- **Severity:** mandatory
- **Story Points:** 1
- **Files:** N/A

[CVE-2023-24998](https://github.com/advisories/GHSA-hfrx-6qgj-fp6c): Apache Commons FileUpload denial of service vulnerability

Severity: HIGH

Affected dependencies:
  - org.apache.tomcat.embed:tomcat-embed-core:9.0.19 (transitive)
  - org.apache.tomcat.embed:tomcat-embed-core:9.0.19 (transitive)
  - org.apache.tomcat.embed:tomcat-embed-core:9.0.19 (transitive)
  - org.apache.tomcat.embed:tomcat-embed-core:9.0.19 (transitive)

Recommended fix:
  - Upgrade org.apache.tomcat.embed:tomcat-embed-core to 10.1.5 or later
  - Upgrade org.apache.tomcat.embed:tomcat-embed-core to 11.0.0-M5 or later
  - Upgrade org.apache.tomcat.embed:tomcat-embed-core to 8.5.88 or later
  - Upgrade org.apache.tomcat.embed:tomcat-embed-core to 9.0.71 or later

### CVE-2022-45688: json stack overflow vulnerability
- **Severity:** mandatory
- **Story Points:** 1
- **Files:** N/A

[CVE-2022-45688](https://github.com/advisories/GHSA-3vqj-43w4-2q58): json stack overflow vulnerability

Severity: HIGH

Affected dependencies:
  - org.json:json:20170516 (transitive)

Recommended fix:
  - Upgrade org.json:json to 20230227 or later

### CVE-2022-42252: Apache Tomcat may reject request containing invalid Content-Length header
- **Severity:** mandatory
- **Story Points:** 1
- **Files:** N/A

[CVE-2022-42252](https://github.com/advisories/GHSA-p22x-g9px-3945): Apache Tomcat may reject request containing invalid Content-Length header

Severity: HIGH

Affected dependencies:
  - org.apache.tomcat.embed:tomcat-embed-core:9.0.19 (transitive)
  - org.apache.tomcat.embed:tomcat-embed-core:9.0.19 (transitive)
  - org.apache.tomcat.embed:tomcat-embed-core:9.0.19 (transitive)
  - org.apache.tomcat.embed:tomcat-embed-core:9.0.19 (transitive)

Recommended fix:
  - Upgrade org.apache.tomcat.embed:tomcat-embed-core to 8.5.83 or later
  - Upgrade org.apache.tomcat.embed:tomcat-embed-core to 9.0.68 or later
  - Upgrade org.apache.tomcat.embed:tomcat-embed-core to 10.0.27 or later
  - Upgrade org.apache.tomcat.embed:tomcat-embed-core to 10.1.1 or later

### CVE-2022-29631: Server-Side Request Forgery in Jodd HTTP
- **Severity:** mandatory
- **Story Points:** 1
- **Files:** N/A

[CVE-2022-29631](https://github.com/advisories/GHSA-pp3c-cf6j-m3ff): Server-Side Request Forgery in Jodd HTTP

Severity: HIGH

Affected dependencies:
  - org.jodd:jodd-http:5.2.0 (transitive)

Recommended fix:
  - Upgrade org.jodd:jodd-http to 6.2.1 or later

### CVE-2020-11996: Uncontrolled Resource Consumption in Apache Tomcat
- **Severity:** mandatory
- **Story Points:** 1
- **Files:** N/A

[CVE-2020-11996](https://github.com/advisories/GHSA-53hp-jpwq-2jgq): Uncontrolled Resource Consumption in Apache Tomcat

Severity: HIGH

Affected dependencies:
  - org.apache.tomcat.embed:tomcat-embed-core:9.0.19 (transitive)
  - org.apache.tomcat.embed:tomcat-embed-core:9.0.19 (transitive)
  - org.apache.tomcat.embed:tomcat-embed-core:9.0.19 (transitive)

Recommended fix:
  - Upgrade org.apache.tomcat.embed:tomcat-embed-core to 10.0.0-M5 or later
  - Upgrade org.apache.tomcat.embed:tomcat-embed-core to 9.0.35 or later
  - Upgrade org.apache.tomcat.embed:tomcat-embed-core to 8.5.55 or later

### CVE-2020-17523: Authentication bypass in Apache Shiro
- **Severity:** mandatory
- **Story Points:** 1
- **Files:** N/A

[CVE-2020-17523](https://github.com/advisories/GHSA-v98j-7crc-wvrj): Authentication bypass in Apache Shiro

Severity: CRITICAL

Affected dependencies:
  - org.apache.shiro:shiro-web:1.6.0 (transitive)
  - org.apache.shiro:shiro-spring:1.6.0 (transitive)
  - org.apache.shiro:shiro-spring-boot-starter:1.6.0 (transitive)

Recommended fix:
  - Upgrade org.apache.shiro:shiro-web to 1.7.1 or later
  - Upgrade org.apache.shiro:shiro-spring to 1.7.1 or later
  - Upgrade org.apache.shiro:shiro-spring-boot-starter to 1.7.1 or later

### CVE-2020-13935: Infinite Loop in Apache Tomcat
- **Severity:** mandatory
- **Story Points:** 1
- **Files:** N/A

[CVE-2020-13935](https://github.com/advisories/GHSA-m7jv-hq7h-mq7c): Infinite Loop in Apache Tomcat

Severity: HIGH

Affected dependencies:
  - org.apache.tomcat.embed:tomcat-embed-websocket:9.0.19 (transitive)
  - org.apache.tomcat.embed:tomcat-embed-websocket:9.0.19 (transitive)
  - org.apache.tomcat.embed:tomcat-embed-websocket:9.0.19 (transitive)
  - org.apache.tomcat.embed:tomcat-embed-websocket:9.0.19 (transitive)

Recommended fix:
  - Upgrade org.apache.tomcat.embed:tomcat-embed-websocket to 7.0.105 or later
  - Upgrade org.apache.tomcat.embed:tomcat-embed-websocket to 8.5.57 or later
  - Upgrade org.apache.tomcat.embed:tomcat-embed-websocket to 9.0.37 or later
  - Upgrade org.apache.tomcat.embed:tomcat-embed-websocket to 10.0.0-M7 or later

### CVE-2021-33813: XML External Entity (XXE) Injection in JDOM
- **Severity:** mandatory
- **Story Points:** 1
- **Files:** N/A

[CVE-2021-33813](https://github.com/advisories/GHSA-2363-cqg2-863c): XML External Entity (XXE) Injection in JDOM

Severity: HIGH

Affected dependencies:
  - org.jdom:jdom:1.1 (transitive)

### CVE-2021-25122: Exposure of Sensitive Information to an Unauthorized Actor in Apache Tomcat
- **Severity:** mandatory
- **Story Points:** 1
- **Files:** N/A

[CVE-2021-25122](https://github.com/advisories/GHSA-j39c-c8hj-x4j3): Exposure of Sensitive Information to an Unauthorized Actor in Apache Tomcat

Severity: HIGH

Affected dependencies:
  - org.apache.tomcat.embed:tomcat-embed-core:9.0.19 (transitive)
  - org.apache.tomcat.embed:tomcat-embed-core:9.0.19 (transitive)
  - org.apache.tomcat.embed:tomcat-embed-core:9.0.19 (transitive)

Recommended fix:
  - Upgrade org.apache.tomcat.embed:tomcat-embed-core to 8.5.63 or later
  - Upgrade org.apache.tomcat.embed:tomcat-embed-core to 10.0.2 or later
  - Upgrade org.apache.tomcat.embed:tomcat-embed-core to 9.0.43 or later

### CVE-2020-17510: Authentication bypass in Apache Shiro
- **Severity:** mandatory
- **Story Points:** 1
- **Files:** N/A

[CVE-2020-17510](https://github.com/advisories/GHSA-7cj4-gj8m-m2f7): Authentication bypass in Apache Shiro

Severity: CRITICAL

Affected dependencies:
  - org.apache.shiro:shiro-spring:1.6.0 (transitive)

Recommended fix:
  - Upgrade org.apache.shiro:shiro-spring to 1.7.0 or later

### CVE-2021-25329: Potential remote code execution in Apache Tomcat
- **Severity:** mandatory
- **Story Points:** 1
- **Files:** N/A

[CVE-2021-25329](https://github.com/advisories/GHSA-jgwr-3qm3-26f3): Potential remote code execution in Apache Tomcat

Severity: HIGH

Affected dependencies:
  - org.apache.tomcat.embed:tomcat-embed-core:9.0.19 (transitive)
  - org.apache.tomcat.embed:tomcat-embed-core:9.0.19 (transitive)
  - org.apache.tomcat.embed:tomcat-embed-core:9.0.19 (transitive)
  - org.apache.tomcat.embed:tomcat-embed-core:9.0.19 (transitive)

Recommended fix:
  - Upgrade org.apache.tomcat.embed:tomcat-embed-core to 10.0.2 or later
  - Upgrade org.apache.tomcat.embed:tomcat-embed-core to 9.0.41 or later
  - Upgrade org.apache.tomcat.embed:tomcat-embed-core to 8.5.61 or later
  - Upgrade org.apache.tomcat.embed:tomcat-embed-core to 7.0.108 or later

### CVE-2020-1938: Improper Privilege Management in Tomcat
- **Severity:** mandatory
- **Story Points:** 1
- **Files:** N/A

[CVE-2020-1938](https://github.com/advisories/GHSA-c9hw-wf7x-jp9j): Improper Privilege Management in Tomcat

Severity: CRITICAL

Affected dependencies:
  - org.apache.tomcat.embed:tomcat-embed-core:9.0.19 (transitive)
  - org.apache.tomcat.embed:tomcat-embed-core:9.0.19 (transitive)
  - org.apache.tomcat.embed:tomcat-embed-core:9.0.19 (transitive)

Recommended fix:
  - Upgrade org.apache.tomcat.embed:tomcat-embed-core to 9.0.31 or later
  - Upgrade org.apache.tomcat.embed:tomcat-embed-core to 8.5.51 or later
  - Upgrade org.apache.tomcat.embed:tomcat-embed-core to 7.0.100 or later

### CVE-2020-9484: Potential remote code execution in Apache Tomcat
- **Severity:** mandatory
- **Story Points:** 1
- **Files:** N/A

[CVE-2020-9484](https://github.com/advisories/GHSA-344f-f5vg-2jfj): Potential remote code execution in Apache Tomcat

Severity: HIGH

Affected dependencies:
  - org.apache.tomcat.embed:tomcat-embed-core:9.0.19 (transitive)
  - org.apache.tomcat.embed:tomcat-embed-core:9.0.19 (transitive)
  - org.apache.tomcat.embed:tomcat-embed-core:9.0.19 (transitive)
  - org.apache.tomcat.embed:tomcat-embed-core:9.0.19 (transitive)

Recommended fix:
  - Upgrade org.apache.tomcat.embed:tomcat-embed-core to 10.0.0-M5 or later
  - Upgrade org.apache.tomcat.embed:tomcat-embed-core to 9.0.35 or later
  - Upgrade org.apache.tomcat.embed:tomcat-embed-core to 8.5.55 or later
  - Upgrade org.apache.tomcat.embed:tomcat-embed-core to 7.0.104 or later

### CVE-2019-12418: Insufficiently Protected Credentials in Apache Tomcat
- **Severity:** mandatory
- **Story Points:** 1
- **Files:** N/A

[CVE-2019-12418](https://github.com/advisories/GHSA-hh3j-x4mc-g48r): Insufficiently Protected Credentials in Apache Tomcat

Severity: HIGH

Affected dependencies:
  - org.apache.tomcat.embed:tomcat-embed-core:9.0.19 (transitive)
  - org.apache.tomcat.embed:tomcat-embed-core:9.0.19 (transitive)
  - org.apache.tomcat.embed:tomcat-embed-core:9.0.19 (transitive)

Recommended fix:
  - Upgrade org.apache.tomcat.embed:tomcat-embed-core to 7.0.99 or later
  - Upgrade org.apache.tomcat.embed:tomcat-embed-core to 8.5.49 or later
  - Upgrade org.apache.tomcat.embed:tomcat-embed-core to 9.0.29 or later

### CVE-2019-17563: In Apache Tomcat, when using FORM authentication there was a narrow window where an attacker could perform a session fixation attack
- **Severity:** mandatory
- **Story Points:** 1
- **Files:** N/A

[CVE-2019-17563](https://github.com/advisories/GHSA-9xcj-c8cr-8c3c): In Apache Tomcat, when using FORM authentication there was a narrow window where an attacker could perform a session fixation attack

Severity: HIGH

Affected dependencies:
  - org.apache.tomcat.embed:tomcat-embed-core:9.0.19 (transitive)
  - org.apache.tomcat.embed:tomcat-embed-core:9.0.19 (transitive)
  - org.apache.tomcat.embed:tomcat-embed-core:9.0.19 (transitive)

Recommended fix:
  - Upgrade org.apache.tomcat.embed:tomcat-embed-core to 7.0.99 or later
  - Upgrade org.apache.tomcat.embed:tomcat-embed-core to 8.5.50 or later
  - Upgrade org.apache.tomcat.embed:tomcat-embed-core to 9.0.30 or later

### CVE-2019-10072: Improper Locking in Apache Tomcat
- **Severity:** mandatory
- **Story Points:** 1
- **Files:** N/A

[CVE-2019-10072](https://github.com/advisories/GHSA-q4hg-rmq2-52q9): Improper Locking in Apache Tomcat

Severity: HIGH

Affected dependencies:
  - org.apache.tomcat.embed:tomcat-embed-core:9.0.19 (transitive)
  - org.apache.tomcat.embed:tomcat-embed-core:9.0.19 (transitive)

Recommended fix:
  - Upgrade org.apache.tomcat.embed:tomcat-embed-core to 9.0.20 or later
  - Upgrade org.apache.tomcat.embed:tomcat-embed-core to 8.5.41 or later

### CVE-2026-40972: Spring Boot DevTools remote secret comparison is vulnerable to timing attacks
- **Severity:** mandatory
- **Story Points:** 1
- **Files:** N/A

[CVE-2026-40972](https://github.com/advisories/GHSA-56v8-86gj-66jp): Spring Boot DevTools remote secret comparison is vulnerable to timing attacks

Severity: HIGH

Affected dependencies:
  - org.springframework.boot:spring-boot-devtools:2.1.5.RELEASE (transitive)
  - org.springframework.boot:spring-boot-devtools:2.1.5.RELEASE (transitive)
  - org.springframework.boot:spring-boot-devtools:2.1.5.RELEASE (transitive)
  - org.springframework.boot:spring-boot-devtools:2.1.5.RELEASE (transitive)
  - org.springframework.boot:spring-boot-devtools:2.1.5.RELEASE (transitive)

Recommended fix:
  - Upgrade org.springframework.boot:spring-boot-devtools to 4.0.6 or later
  - Upgrade org.springframework.boot:spring-boot-devtools to 3.5.14 or later

### CVE-2023-20883: Spring Boot Welcome Page Denial of Service
- **Severity:** mandatory
- **Story Points:** 1
- **Files:** N/A

[CVE-2023-20883](https://github.com/advisories/GHSA-xf96-w227-r7c4): Spring Boot Welcome Page Denial of Service

Severity: HIGH

Affected dependencies:
  - org.springframework.boot:spring-boot-autoconfigure:2.1.5.RELEASE (transitive)
  - org.springframework.boot:spring-boot-autoconfigure:2.1.5.RELEASE (transitive)
  - org.springframework.boot:spring-boot-autoconfigure:2.1.5.RELEASE (transitive)
  - org.springframework.boot:spring-boot-autoconfigure:2.1.5.RELEASE (transitive)

Recommended fix:
  - Upgrade org.springframework.boot:spring-boot-autoconfigure to 3.0.7 or later
  - Upgrade org.springframework.boot:spring-boot-autoconfigure to 2.7.12 or later
  - Upgrade org.springframework.boot:spring-boot-autoconfigure to 2.6.15 or later
  - Upgrade org.springframework.boot:spring-boot-autoconfigure to 2.5.15 or later

### CVE-2022-22965: Remote Code Execution in Spring Framework
- **Severity:** mandatory
- **Story Points:** 1
- **Files:** litemall-core/pom.xml:19

[CVE-2022-22965](https://github.com/advisories/GHSA-36p3-wjmg-h94x): Remote Code Execution in Spring Framework

Severity: CRITICAL

Affected dependencies:
  - org.springframework:spring-beans:5.1.7.RELEASE (transitive)
  - org.springframework:spring-webmvc:5.1.7.RELEASE (transitive)
  - org.springframework.boot:spring-boot-starter-web:2.1.5.RELEASE (declared at litemall-core/pom.xml:19)
  - org.springframework.boot:spring-boot-starter-web:2.1.5.RELEASE (declared at litemall-core/pom.xml:19)
  - org.springframework:spring-beans:5.1.7.RELEASE (transitive)
  - org.springframework:spring-webmvc:5.1.7.RELEASE (transitive)

Recommended fix:
  - Upgrade org.springframework:spring-beans to 5.3.18 or later
  - Upgrade org.springframework:spring-webmvc to 5.3.18 or later
  - Upgrade org.springframework.boot:spring-boot-starter-web to 2.5.12 or later
  - Upgrade org.springframework.boot:spring-boot-starter-web to 2.6.6 or later
  - Upgrade org.springframework:spring-beans to 5.2.20.RELEASE or later
  - Upgrade org.springframework:spring-webmvc to 5.2.20.RELEASE or later

### CVE-2020-26945: "Deserialization errors in MyBatis"
- **Severity:** mandatory
- **Story Points:** 1
- **Files:** N/A

[CVE-2020-26945](https://github.com/advisories/GHSA-qq48-m4jx-xqh8): "Deserialization errors in MyBatis"

Severity: HIGH

Affected dependencies:
  - org.mybatis:mybatis:3.4.6 (transitive)

Recommended fix:
  - Upgrade org.mybatis:mybatis to 3.5.6 or later

### CVE-2026-40973: Spring Boot accepts predictable temp directory without ownership verification
- **Severity:** mandatory
- **Story Points:** 1
- **Files:** N/A

[CVE-2026-40973](https://github.com/advisories/GHSA-wwpq-f5c3-7hvx): Spring Boot accepts predictable temp directory without ownership verification

Severity: HIGH

Affected dependencies:
  - org.springframework.boot:spring-boot:2.1.5.RELEASE (transitive)
  - org.springframework.boot:spring-boot:2.1.5.RELEASE (transitive)
  - org.springframework.boot:spring-boot:2.1.5.RELEASE (transitive)
  - org.springframework.boot:spring-boot:2.1.5.RELEASE (transitive)
  - org.springframework.boot:spring-boot:2.1.5.RELEASE (transitive)

Recommended fix:
  - Upgrade org.springframework.boot:spring-boot to 4.0.6 or later
  - Upgrade org.springframework.boot:spring-boot to 3.5.14 or later

### CVE-2025-22235: Spring Boot EndpointRequest.to() creates wrong matcher if actuator endpoint is not exposed
- **Severity:** mandatory
- **Story Points:** 1
- **Files:** N/A

[CVE-2025-22235](https://github.com/advisories/GHSA-rc42-6c7j-7h5r): Spring Boot EndpointRequest.to() creates wrong matcher if actuator endpoint is not exposed

Severity: HIGH

Affected dependencies:
  - org.springframework.boot:spring-boot:2.1.5.RELEASE (transitive)
  - org.springframework.boot:spring-boot:2.1.5.RELEASE (transitive)
  - org.springframework.boot:spring-boot:2.1.5.RELEASE (transitive)
  - org.springframework.boot:spring-boot:2.1.5.RELEASE (transitive)
  - org.springframework.boot:spring-boot:2.1.5.RELEASE (transitive)

Recommended fix:
  - Upgrade org.springframework.boot:spring-boot to 3.3.11 or later
  - Upgrade org.springframework.boot:spring-boot to 3.4.5 or later

### CVE-2024-38819: Spring Framework Path Traversal vulnerability
- **Severity:** mandatory
- **Story Points:** 1
- **Files:** N/A

[CVE-2024-38819](https://github.com/advisories/GHSA-g5vr-rgqm-vf78): Spring Framework Path Traversal vulnerability

Severity: HIGH

Affected dependencies:
  - org.springframework:spring-webmvc:5.1.7.RELEASE (transitive)
  - org.springframework:spring-webmvc:5.1.7.RELEASE (transitive)
  - org.springframework:spring-webmvc:5.1.7.RELEASE (transitive)

Recommended fix:
  - Upgrade org.springframework:spring-webmvc to 6.1.14 or later

### CVE-2024-22262: Spring Framework URL Parsing with Host Validation
- **Severity:** mandatory
- **Story Points:** 1
- **Files:** N/A

[CVE-2024-22262](https://github.com/advisories/GHSA-2wrp-6fg6-hmc5): Spring Framework URL Parsing with Host Validation

Severity: HIGH

Affected dependencies:
  - org.springframework:spring-web:5.1.7.RELEASE (transitive)
  - org.springframework:spring-web:5.1.7.RELEASE (transitive)
  - org.springframework:spring-web:5.1.7.RELEASE (transitive)

Recommended fix:
  - Upgrade org.springframework:spring-web to 5.3.34 or later
  - Upgrade org.springframework:spring-web to 6.0.19 or later
  - Upgrade org.springframework:spring-web to 6.1.6 or later

### CVE-2024-22259: Spring Framework URL Parsing with Host Validation Vulnerability
- **Severity:** mandatory
- **Story Points:** 1
- **Files:** N/A

[CVE-2024-22259](https://github.com/advisories/GHSA-hgjh-9rj2-g67j): Spring Framework URL Parsing with Host Validation Vulnerability

Severity: HIGH

Affected dependencies:
  - org.springframework:spring-web:5.1.7.RELEASE (transitive)
  - org.springframework:spring-web:5.1.7.RELEASE (transitive)
  - org.springframework:spring-web:5.1.7.RELEASE (transitive)

Recommended fix:
  - Upgrade org.springframework:spring-web to 6.1.5 or later
  - Upgrade org.springframework:spring-web to 6.0.18 or later
  - Upgrade org.springframework:spring-web to 5.3.33 or later

### CVE-2024-22243: Spring Web vulnerable to Open Redirect or Server Side Request Forgery
- **Severity:** mandatory
- **Story Points:** 1
- **Files:** N/A

[CVE-2024-22243](https://github.com/advisories/GHSA-ccgv-vj62-xf9h): Spring Web vulnerable to Open Redirect or Server Side Request Forgery

Severity: HIGH

Affected dependencies:
  - org.springframework:spring-web:5.1.7.RELEASE (transitive)
  - org.springframework:spring-web:5.1.7.RELEASE (transitive)
  - org.springframework:spring-web:5.1.7.RELEASE (transitive)
  - org.springframework:spring-web:5.1.7.RELEASE (transitive)

Recommended fix:
  - Upgrade org.springframework:spring-web to 6.1.4 or later
  - Upgrade org.springframework:spring-web to 6.0.17 or later
  - Upgrade org.springframework:spring-web to 5.3.32 or later

### CVE-2023-20863: Spring Framework vulnerable to denial of service
- **Severity:** mandatory
- **Story Points:** 1
- **Files:** N/A

[CVE-2023-20863](https://github.com/advisories/GHSA-wxqc-pxw9-g2p8): Spring Framework vulnerable to denial of service

Severity: HIGH

Affected dependencies:
  - org.springframework:spring-expression:5.1.7.RELEASE (transitive)
  - org.springframework:spring-expression:5.1.7.RELEASE (transitive)
  - org.springframework:spring-expression:5.1.7.RELEASE (transitive)

Recommended fix:
  - Upgrade org.springframework:spring-expression to 6.0.8 or later
  - Upgrade org.springframework:spring-expression to 5.3.27 or later
  - Upgrade org.springframework:spring-expression to 5.2.24.RELEASE or later

### CVE-2022-1471: SnakeYaml Constructor Deserialization Remote Code Execution
- **Severity:** mandatory
- **Story Points:** 1
- **Files:** N/A

[CVE-2022-1471](https://github.com/advisories/GHSA-mjmj-j48q-9wg2): SnakeYaml Constructor Deserialization Remote Code Execution

Severity: HIGH

Affected dependencies:
  - org.yaml:snakeyaml:1.23 (transitive)

Recommended fix:
  - Upgrade org.yaml:snakeyaml to 2.0 or later

### CVE-2022-25857: Uncontrolled Resource Consumption in snakeyaml
- **Severity:** mandatory
- **Story Points:** 1
- **Files:** N/A

[CVE-2022-25857](https://github.com/advisories/GHSA-3mc7-4q67-w48m): Uncontrolled Resource Consumption in snakeyaml

Severity: HIGH

Affected dependencies:
  - org.yaml:snakeyaml:1.23 (transitive)

Recommended fix:
  - Upgrade org.yaml:snakeyaml to 1.31 or later

### CVE-2022-27772: Temporary Directory Hijacking to Local Privilege Escalation Vulnerability in org.springframework.boot:spring-boot
- **Severity:** mandatory
- **Story Points:** 1
- **Files:** N/A

[CVE-2022-27772](https://github.com/advisories/GHSA-cm59-pr5q-cw85): Temporary Directory Hijacking to Local Privilege Escalation Vulnerability in org.springframework.boot:spring-boot

Severity: HIGH

Affected dependencies:
  - org.springframework.boot:spring-boot:2.1.5.RELEASE (transitive)

Recommended fix:
  - Upgrade org.springframework.boot:spring-boot to 2.2.11.RELEASE or later

### CVE-2016-1000027: Pivotal Spring Framework contains unsafe Java deserialization methods
- **Severity:** mandatory
- **Story Points:** 1
- **Files:** N/A

[CVE-2016-1000027](https://github.com/advisories/GHSA-4wrc-f8pq-fpqp): Pivotal Spring Framework contains unsafe Java deserialization methods

Severity: CRITICAL

Affected dependencies:
  - org.springframework:spring-web:5.1.7.RELEASE (transitive)

Recommended fix:
  - Upgrade org.springframework:spring-web to 6.0.0 or later

### CVE-2022-22970: Denial of service in Spring Framework
- **Severity:** mandatory
- **Story Points:** 1
- **Files:** N/A

[CVE-2022-22970](https://github.com/advisories/GHSA-hh26-6xwr-ggv7): Denial of service in Spring Framework

Severity: HIGH

Affected dependencies:
  - org.springframework:spring-beans:5.1.7.RELEASE (transitive)
  - org.springframework:spring-beans:5.1.7.RELEASE (transitive)

Recommended fix:
  - Upgrade org.springframework:spring-beans to 5.2.22.RELEASE or later
  - Upgrade org.springframework:spring-beans to 5.3.20 or later

### CVE-2022-22968: Improper handling of case sensitivity in Spring Framework
- **Severity:** mandatory
- **Story Points:** 1
- **Files:** N/A

[CVE-2022-22968](https://github.com/advisories/GHSA-g5mm-vmx4-3rg7): Improper handling of case sensitivity in Spring Framework

Severity: HIGH

Affected dependencies:
  - org.springframework:spring-context:5.1.7.RELEASE (transitive)
  - org.springframework:spring-context:5.1.7.RELEASE (transitive)

Recommended fix:
  - Upgrade org.springframework:spring-context to 5.3.19 or later
  - Upgrade org.springframework:spring-context to 5.2.21.RELEASE or later

### CVE-2017-18640: SnakeYAML Entity Expansion during load operation
- **Severity:** mandatory
- **Story Points:** 1
- **Files:** N/A

[CVE-2017-18640](https://github.com/advisories/GHSA-rvwf-54qp-4r6v): SnakeYAML Entity Expansion during load operation

Severity: HIGH

Affected dependencies:
  - org.yaml:snakeyaml:1.23 (transitive)

Recommended fix:
  - Upgrade org.yaml:snakeyaml to 1.26 or later

### CVE-2020-5398: RFD attack via Content-Disposition header sourced from request input by Spring MVC or Spring WebFlux Application
- **Severity:** mandatory
- **Story Points:** 1
- **Files:** N/A

[CVE-2020-5398](https://github.com/advisories/GHSA-8wx2-9q48-vm9r): RFD attack via Content-Disposition header sourced from request input by Spring MVC or Spring WebFlux Application

Severity: HIGH

Affected dependencies:
  - org.springframework:spring-webmvc:5.1.7.RELEASE (transitive)
  - org.springframework:spring-webmvc:5.1.7.RELEASE (transitive)
  - org.springframework:spring-webmvc:5.1.7.RELEASE (transitive)

Recommended fix:
  - Upgrade org.springframework:spring-webmvc to 5.2.3.RELEASE or later
  - Upgrade org.springframework:spring-webmvc to 5.1.13.RELEASE or later
  - Upgrade org.springframework:spring-webmvc to 5.0.16.RELEASE or later


## CWE Findings (Code-Level Vulnerabilities)

### CWE-477: Use of Obsolete Function
- **Category:** Code Quality
- **Severity:** optional
- **Story Points:** 1
- **Files:** litemall-db/src/main/java/org/linlinjava/litemall/db/service/LitemallAdService.java, litemall-db/src/main/java/org/linlinjava/litemall/db/util/DbUtil.java

The codebase extensively uses org.springframework.util.StringUtils.isEmpty() which is deprecated in Spring 5.3+ (used in dozens of service classes including LitemallAdService.java line 29, LitemallGoodsService.java, etc.). Additionally, DbUtil.java lines 13-14 and 34-35 use the single-string form of Runtime.getRuntime().exec(command), which is considered obsolete in favor of ProcessBuilder.

### CWE-681: Incorrect Conversion between Numeric Types
- **Category:** Code Quality
- **Severity:** potential
- **Story Points:** 3
- **Files:** litemall-db/src/main/java/org/linlinjava/litemall/db/service/LitemallGoodsService.java, litemall-db/src/main/java/org/linlinjava/litemall/db/service/LitemallOrderService.java

Multiple service classes cast the long return value of MyBatis countByExample() to int using (int) without range checking: LitemallGoodsService.java lines 186 and 212, LitemallOrderService.java lines 36, 63, 141, LitemallGoodsProductService.java line 44, LitemallTopicService.java line 37, LitemallUserService.java line 73, LitemallCommentService.java line 50, LitemallCollectService.java line 22. If the database table contains more than Integer.MAX_VALUE (2,147,483,647) rows, the cast will overflow and produce a negative or incorrect count.

### CWE-772: Missing Release of Resource after Effective Lifetime
- **Category:** Code Quality
- **Severity:** potential
- **Story Points:** 3
- **Files:** litemall-db/src/main/java/org/linlinjava/litemall/db/util/DbUtil.java

DbUtil.backup() (lines 15-25) and DbUtil.load() (lines 36-46) open InputStream, BufferedReader, and OutputStreamWriter inside a try-catch block but close them sequentially at the end without try-with-resources. If an IOException or RuntimeException occurs during the write loop (e.g., mid-write), the close() calls are skipped and the file descriptors and process streams are never released, causing a resource leak.

### CWE-775: Missing Release of File Descriptor or Handle after Effective Lifetime
- **Category:** Code Quality
- **Severity:** potential
- **Story Points:** 3
- **Files:** litemall-db/src/main/java/org/linlinjava/litemall/db/util/DbUtil.java

DbUtil.java backup() at line 17 opens a FileOutputStream and DbUtil.load() at line 37 opens a FileInputStream, both without using try-with-resources. The file handles are closed manually at lines 25 and 45, but if any exception occurs before those lines are reached (e.g., during the while-loop at lines 19-21 or 40-42), the file descriptors are never closed, causing a file handle leak.

### CWE-567: Unsynchronized Access to Shared Data in a Multithreaded Context
- **Category:** Concurrency & Synchronization
- **Severity:** potential
- **Story Points:** 5
- **Files:** litemall-wx-api/src/main/java/org/linlinjava/litemall/wx/service/HomeCacheManager.java

HomeCacheManager.java declares a static mutable field `cacheDataList` (line 17) without the `volatile` keyword. The `clearAll()` method at line 70 reassigns the entire reference: `cacheDataList = new ConcurrentHashMap<>()`. In a multi-threaded environment, threads that have already read the old reference will continue operating on the old ConcurrentHashMap instance after clearAll() replaces it, leading to inconsistent cache state. Additionally, the check-then-act pattern in loadData() (lines 25-37: get, then put) is not atomic, allowing race conditions between concurrent requests.

### CWE-820: Missing Synchronization
- **Category:** Concurrency & Synchronization
- **Severity:** potential
- **Story Points:** 8
- **Files:** litemall-wx-api/src/main/java/org/linlinjava/litemall/wx/web/WxHomeController.java, litemall-wx-api/src/main/java/org/linlinjava/litemall/wx/web/WxGoodsController.java

WxHomeController.java line 60 and WxGoodsController.java line 80 declare static `ThreadPoolExecutor executorService` fields that are not declared `volatile` and are not `final`. These shared thread pool references are accessed concurrently by multiple request threads without any synchronization. The absence of `volatile` means the JVM is free to cache the field value in CPU registers, potentially causing threads to use stale executor references. In WxHomeController, all 9 async tasks (lines 122-130) submit to this unsynchronized static executor.

### CWE-259: Use of Hard-coded Password
- **Category:** Credentials & Secrets
- **Severity:** optional
- **Story Points:** 5
- **Files:** deploy/litemall/application.yml, docker/litemall/application.yml

deploy/litemall/application.yml line 11 and docker/litemall/application.yml line 11 both contain a hardcoded MySQL database password: 'litemall123456' (spring.datasource.druid.password). Additionally, deploy/litemall/application.yml contains a hardcoded email password at the smtp.password field. These credentials are committed to source control and would expose the database if the repository is accessed.

### CWE-321: Use of Hard-coded Cryptographic Key
- **Category:** Credentials & Secrets
- **Severity:** potential
- **Story Points:** 5
- **Files:** deploy/litemall/application.yml

deploy/litemall/application.yml contains multiple hardcoded cryptographic API keys and secrets: WeChat Mini Program app-secret 'e04004829d4c383b4db7769d88dfbca1' (line for wx.app-secret), Tencent COS secretId 'AKIDOccMr856uoU1Tsa2MQL5aqseBUWRrb5i' and secretKey 'XqtgEhIdrupTs4ygaWlkUUXv3w3FiwuD'. These cloud API credentials are committed to source control and allow unauthorized access to the associated cloud services.

### CWE-778: Insufficient Logging
- **Category:** Credentials & Secrets
- **Severity:** potential
- **Story Points:** 3
- **Files:** litemall-admin-api/src/main/java/org/linlinjava/litemall/admin/web/AdminAuthController.java, litemall-wx-api/src/main/java/org/linlinjava/litemall/wx/web/WxAuthController.java

AdminAuthController.java and WxAuthController.java contain login, logout, and registration endpoints but do not log security-critical events such as failed authentication attempts, successful logins, or account lockouts. No logger.info/warn/error calls are present in either authentication controller. This makes it impossible to detect or audit unauthorized access attempts or brute-force attacks.

### CWE-798: Use of Hard-coded Credentials
- **Category:** Credentials & Secrets
- **Severity:** optional
- **Story Points:** 5
- **Files:** deploy/litemall/application.yml, docker/litemall/application.yml

Both deploy/litemall/application.yml and docker/litemall/application.yml contain hard-coded credentials committed to source control: database username 'litemall' and password 'litemall123456', WeChat app-secret 'e04004829d4c383b4db7769d88dfbca1', and Tencent COS secretId 'AKIDOccMr856uoU1Tsa2MQL5aqseBUWRrb5i' with secretKey 'XqtgEhIdrupTs4ygaWlkUUXv3w3FiwuD'. Any developer with read access to the repository can use these credentials to access the production database and cloud services.

### CWE-22: Improper Limitation of a Pathname to a Restricted Directory ('Path Traversal')
- **Category:** File & Path Security
- **Severity:** optional
- **Story Points:** 8
- **Files:** litemall-core/src/main/java/org/linlinjava/litemall/core/storage/LocalStorage.java, litemall-wx-api/src/main/java/org/linlinjava/litemall/wx/web/WxStorageController.java

In LocalStorage.java, the store() method at line 57 calls rootLocation.resolve(keyName) where keyName is derived from user-supplied file extension (originalFilename). In WxStorageController.java, the fetch() (line 67) and download() (line 92) endpoints pass a user-supplied URL path variable key directly to storageService.loadAsResource(key) (lines 78, 104). The partial mitigation at lines 72-74 and 97-99 only checks for '../' literal but does not neutralize URL-encoded traversal sequences or absolute paths.

### CWE-23: Relative Path Traversal
- **Category:** File & Path Security
- **Severity:** optional
- **Story Points:** 5
- **Files:** litemall-wx-api/src/main/java/org/linlinjava/litemall/wx/web/WxStorageController.java

WxStorageController.fetch() and download() methods check only for the literal string '../' (lines 72 and 97), but do not handle URL-encoded variants such as '%2E%2E%2F', '%2E%2E/', or '.%2F'. A user-supplied key containing an encoded relative traversal sequence bypasses the check and is passed to LocalStorage.load(filename) at line 77 (LocalStorage.java) which uses rootLocation.resolve(filename) without further sanitization.

### CWE-434: Unrestricted Upload of File with Dangerous Type
- **Category:** File & Path Security
- **Severity:** mandatory
- **Story Points:** 8
- **Files:** litemall-admin-api/src/main/java/org/linlinjava/litemall/admin/web/AdminStorageController.java, litemall-wx-api/src/main/java/org/linlinjava/litemall/wx/web/WxStorageController.java

AdminStorageController.create() at line 49 and WxStorageController.upload() at line 54 both accept any MultipartFile upload without validating the file type, extension, or MIME type. The originalFilename is passed directly to storageService.store() without any whitelist or blacklist of allowed file types. This allows uploading dangerous file types such as .jsp, .exe, or .sh which could be executed by the server.

### CWE-77: Improper Neutralization of Special Elements used in a Command ('Command Injection')
- **Category:** Injection Attacks
- **Severity:** mandatory
- **Story Points:** 13
- **Files:** litemall-db/src/main/java/org/linlinjava/litemall/db/util/DbUtil.java

DbUtil.backup() at line 13 and DbUtil.load() at line 34 construct OS commands by string concatenation: 'mysqldump -u' + user + ' -p' + password + ' ... ' + db and pass the full command string to Runtime.getRuntime().exec(command). Since exec() is called with a single string (not an array), the shell will interpret special characters in user, password, or db values. These values come from Spring datasource configuration properties, which may be influenced through environment variable injection or configuration overrides.

### CWE-78: Improper Neutralization of Special Elements used in an OS Command ('OS Command Injection')
- **Category:** Injection Attacks
- **Severity:** mandatory
- **Story Points:** 13
- **Files:** litemall-db/src/main/java/org/linlinjava/litemall/db/util/DbUtil.java

DbUtil.java lines 12-14 (backup) and 33-35 (load) call Runtime.getRuntime().exec() with a single command string built from concatenated user credentials and database name. The single-string form of exec() is passed to the OS shell, making it vulnerable to OS command injection if any component of the command (user, password, db name) contains shell metacharacters such as ';', '|', '`', or '$'.

### CWE-89: Improper Neutralization of Special Elements used in an SQL Command ('SQL Injection')
- **Category:** Injection Attacks
- **Severity:** mandatory
- **Story Points:** 13
- **Files:** litemall-db/src/main/resources/org/linlinjava/litemall/db/dao/OrderMapper.xml, litemall-db/src/main/java/org/linlinjava/litemall/db/service/LitemallOrderService.java

OrderMapper.xml lines 112-114 and 117-119 use MyBatis string interpolation (${query} and ${orderByClause}) instead of parameterized binding (#{}) directly in SQL. LitemallOrderService.java line 238 builds orderByClause by string concatenation of user-supplied sort and order request parameters: 'o.' + sort + ' ' + order + ', o.id desc'. Although @Sort and @Order annotations validate these values, the query variable at lines 226-233 is built by string concatenation including orderStatusArray values. Additional ${orderByClause} interpolations exist across many mapper XML files (LitemallAdminMapper.xml, LitemallGrouponMapper.xml, etc.).
