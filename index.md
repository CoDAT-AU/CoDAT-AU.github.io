---
layout: default
---

# CoDAT

We present the Code Documentation and Analysis Tool (CoDAT). CoDAT is a tool designed to maintain consistency between the various levels of code documentation, e.g. if a line in a code sketch is changed, the comment that documents the corresponding code is also changed. That is, comments are linked and updated so as to remain internally consistent and also consistent with the code. By flagging "out of date" comments, CoDAT alerts the developer to maintain up-to-date documentation. We use a large language model to check the semantic consistency between a fragment of code and the comments that describe it. Thus we also flag semantic inconsistency as well as out of date comments. This helps programers write code that correctly implements a code sketch, and so provides machine support for a step-wise refinement approach, starting with a code sketch and proceeding down to code through one or more refinement iterations. CoDAT is implemented in the Intellij IDEA IDE where we use the Code Insight daemon package alongside a custom regular expression algorithm to mark tagged comments whose corresponding code blocks have changed. CoDAT's backend is structurally decentralized to allow a distributed ledger framework for code consistency and architectural compilation tracking.

# Table of Contents 

1. [Publications](#publications)
2. [Vulnerabilities Discovered](#discoveries)

# Publications

1. [Bypassing Array Canaries via Autonomous Function Call Resolution](https://arxiv.org/abs/2501.13256)
2. [Code Documentation and Analysis to Secure Software Development](https://arxiv.org/abs/2407.11934)

# Discoveries

| Product | Vulnerability Category | Vulnerability Impact | Severity | CVSS Base Score | CVSS Vector | CVE Number |
| --- | --- | --- | --- | --- | --- | 
| Adobe Acrobat Reader | Use After Free (CWE-416) | Arbitrary code execution | Important | 5.5 | CVSS:3.1/AV:L/AC:L/PR:N/UI:R/S:U/C:N/I:N/A:H | [CVE-2025-43577](https://helpx.adobe.com/security/products/acrobat/apsb25-57.html) | 
| WordPress Plugin | XSS (CWE-79) | Reflected Cross-Site Scripting | Medium | 6.1 | CVSS:3.1/AV:N/AC:L/PR:N/UI:R/S:C/C:L/I:L/A:N | [CVE-2024-13334](https://www.cve.org/CVERecord?id=CVE-2024-13334) |
| WordPress Plugin | Missing Authorization (CWE-862) | Information Exposure | Medium | 5.3 | CVSS:3.1/AV:N/AC:L/PR:N/UI:N/S:U/C:L/I:N/A:N | [CVE-2024-10813](https://www.cve.org/CVERecord?id=CVE-2024-10813) |
| WordPress Plugin | XSS (CWE-79) | Reflected Cross-Site Scripting | Medium | 6.1 | CVSS:3.1/AV:N/AC:L/PR:N/UI:R/S:C/C:L/I:L/A:N | [CVE-2024-10792](https://www.cve.org/CVERecord?id=CVE-2024-10792) | 
| WordPress Plugin | XSS (CWE-79) | Reflected Cross-Site Scripting | Medium | 6.1 | CVSS:3.1/AV:N/AC:L/PR:N/UI:R/S:C/C:L/I:L/A:N | [CVE-2024-1782](https://www.cve.org/CVERecord?id=CVE-2024-1782) |
| WordPress Plugin | XSS (CWE-79) | Reflected Cross-Site Scripting | Medium | 6.1 | CVSS:3.1/AV:N/AC:L/PR:N/UI:R/S:C/C:L/I:L/A:N | [CVE-2024-1780](https://www.cve.org/CVERecord?id=CVE-2024-1780) |
| WordPress Plugin | CSRF (CWE-352) | Cross-Site Request Forgery | Medium | 4.3 | CVSS:3.1/AV:N/AC:L/PR:N/UI:R/S:U/C:N/I:L/A:N | [CVE-2024-0859](https://www.cve.org/CVERecord?id=CVE-2024-0859) |
| WordPress Plugin | XSS (CWE-79) | Reflected Cross-Site Scripting | Medium | 6.1 | CVSS:3.1/AV:N/AC:L/PR:N/UI:R/S:C/C:L/I:L/A:N | [CVE-2024-0848](https://www.cve.org/CVERecord?id=CVE-2024-0848) |
| WordPress Plugin | CSRF (CWE-352) | Cross-Site Request Forgery | Medium | 4.3 | CVSS:3.1/AV:N/AC:L/PR:N/UI:R/S:U/C:N/I:L/A:N | [CVE-2024-0847](https://www.cve.org/CVERecord?id=CVE-2024-0847) |
| WordPress Plugin | Missing Authorization (CWE-862) | Information Exposure | Medium | 5.3 | CVSS:3.1/AV:N/AC:L/PR:N/UI:N/S:U/C:L/I:N/A:N | [CVE-2024-0708](https://www.cve.org/CVERecord?id=CVE-2024-0708) |