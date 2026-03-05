# Vulnerabilities

## What is a Vulnerability

- A weakness, flaw, or error in an information system, security procedure, internal control, or implementation that can be exploited by a threat actor to gain unauthorized access, steal data, or disrupt operations.
- Examples:
  - Software bugs, weak passwords, misconfigured firewalls, or lack of user training.

## Common Vulnerabilites and Exposures (CVE)

- Led by MITRE
- Every new CVE is assigned a CVE ID
  - Format:
    - `CVE-yyy-xxx`
- Includes a vulnerability description, data sources and vendor announcement.
- [CVE Website](https://www.cve.org/)
- [CVE Example](https://www.cve.org/CVERecord?id=CVE-2026-3523)

## Common Vulnerability Scoring System (CVSS)

- Evalutes the severity of tha vulnerability from 0 to 10
- Considers the CIA triad and other factors

- **CVSSv2**
  - Scoring
    - High
      - 7.0 - 10.0
    - Medium
      - 4.0 - 6.9
    - Low
      - 0.0 - 3.9

- **CVSSv3** 
  - Scoring
    - Critical
      - 9.0 - 10.0
    - High
      - 7.0 - 8.9
    - Medium
      - 4.0 - 6.9
    - Low
      - 0.1 - 3.9
    - None
      - 0.0
