# Cyber Threat Intelligence

## What is a threat

- Any circumstance or event with the potential to adversely impact organizational operations, assests or individuals using and information system by unauthorized access, destruction, disclosure, modification of information and/or denial of service

## Intelligence, Threat Intelligence, Cyber Threat Intelligence

- Intelligence
  - May not be related to cybersecurity
- Threat Intelligence
  - Specific threat actors or adversaries
  - May not be directly related to cybersecurity
- Cyber Threat Intelligence
  - Threat actors that leverage tactics, techniques and procedures related to cybersecurity
    - Nation state sponsored hacking group

## Cyber Threat Intelligence

- Knowledge about adversaries and their motivations, intetions and methods that is collected and analyzed and disseminated in ways to help business and security teams protect assets.

## Threats, Vulnerabilities and Risk

- Threat Actor intiates threat
- Threat exploits vulnerability
- Vulnerability causes adverse impact
- Producing risk likelihood and impact

## Theat Informed Defense

- What is the mission of my organization?
- What threat actors are interested in my organization's industry?
- What are the motivations of those threat actors?
- What TTPs are those threat actors using?
- How can I detect and protect my organization against those TTPs?

## Tactics, Techniques and Procedures (TTPs)

- Tactics
  - The why
  - The high-level, strategic objectives of an attacker, such as initial access, lateral movement, or data exfiltration.
- Techniques
  - The how
  - The specific methods or intermediate steps used to achieve a tactical goal, such as using phishing to gain access or SQL injection to steal data.
- Procedures 
  - The Step-by-Step
  - Detailed, actionable steps or "playbooks" that attackers follow to execute a technique, including specific commands, tools, or scripts used.

- [NIST Definition](https://csrc.nist.gov/glossary/term/tactics_techniques_and_procedures)

## IOC and IOA

- IOC
  - Indicator of Compromise
  - Evidence that the security of system or network has been breached
  - Example
    - Known malware hash, a specific malicious IP address, or a modified registry key.
- IOA
  - Indicators of Attack
  - Focuses on behaviors and identifes suscpcious activity that indicate an attack is in progress or about to happen.
  - Example 
    - Unusual PowerShell execution, unexpected lateral movement, or multiple failed login attempts followed by a successful one.

## Pyramid of Pain

- The Six Layers (Low to High Pain for Attackers):
  - Hash Values (Trivial): Easily changed, e.g., changing a single bit in a file.
  - IP Addresses (Easy): Quickly changed or rotated.
  - Domain Names (Simple): Requires registration, but still easy to replace.
  - Network/Host Artifacts (Annoying): Specific patterns like User-Agents or registry keys.
  - Tools (Challenging): Software used, such as Pwdump or Mimikatz; changing these forces them to adapt.
  - Tactics, Techniques, & Procedures (TTPs) (Tough): The top level; detecting attacker behavior forces them to re-learn their craft.

## CTI Sources

- Enterprise Sources
  - Microsoft Defender Threat Intelligence
  - Crowdstrike
  - Cisco
- OSINT
  - Virus Total
  - Pulse Check
  - Shodan
- Social Media
  - X(Twitter)
  - LinkedIn
