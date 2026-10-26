# Arin Aeruva

I’m a UC Santa Cruz Computer Science graduate focused on security operations and security engineering. I like investigating suspicious behavior, building tools that make the evidence easier to follow, and fixing security issues in existing projects.

[Portfolio](https://arin30.github.io/) · [Open source work](https://arin30.github.io/open-source.html) · [All my pull requests](https://github.com/search?q=author%3Aarin30+is%3Apr&type=pullrequests) · [LinkedIn](https://www.linkedin.com/in/arin-aeruva)

## My open source contributions

A few merged changes, with links to the actual work:

| Project | Contribution |
| --- | --- |
| **Apache Magpie** | [Fixed ASF CVE bookkeeping sender configuration](https://github.com/apache/magpie/pull/1745), with setup guidance and regression tests so automated messages are filtered before normal security triage. |
| **OpenPulse** | [Added a safer token-file option](https://github.com/IkarusAILabs/OpenPulse/pull/122) and deprecated passing GitHub tokens directly in command-line arguments. |
| **Autentico** | [Kept query-string secrets out of request logs](https://github.com/eugenioenko/autentico/pull/490), with regression coverage for reset tokens, authorization codes, and other sensitive values. |
| **Guardian Protocol** | [Gave an AI-agent exfiltration test its own attack scenario](https://github.com/guardianprotocol-ai/registry/pull/182), including a separate canary, judge, and regression test to keep it distinct from another scenario. |

## What I’m building

**[SignalF0rge](https://github.com/arin30/SignalF0rge)**  
A Python security automation pipeline for log analysis, threat detection, MITRE ATT&CK mapping, event correlation, and incident reporting.

**[CinderProxy](https://github.com/arin30/CinderProxy)**  
A reverse proxy in C, with HTTP parsing, rate limiting, request validation, backend routing, and defensive handling of untrusted input.

## Background

At **Johnson & Johnson MedTech / Shockwave Medical**, my cybersecurity internship involved SIEM alert triage, CrowdStrike endpoint monitoring, Rapid7 vulnerability assessments, phishing investigations, and incident-response documentation.

At **CloudDefense.AI**, I worked on cloud security tooling, APIs and OAuth2, testing and debugging, and helped with customer demos.

I work with Python, C, Linux, networking, AWS, Docker, SQL, Bash, and PowerShell. I’m interested in both hands-on security roles and technical customer-facing work involving troubleshooting, integrations, and explaining how systems work.
