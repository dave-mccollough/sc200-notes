# MITRE ATT&CK

## What is MITRE ATT&CK Framework

- Adveserial Tactics and Techniques & Common Knowledge
- Funded by US Homeland Security
- Tactics, Techniques and Procedures (TTPs)
- TTPs help cybersecurity teams catagorize, describe, and defend against known attack methods
- Globally accessible knowledge base of adversarial tactics and techniques based on real world observations
- Used as a foundation for the development of specific threat models and methodologies
- [URL](https://attack.mitre.org/)

## ATT&CK Matrices

- [Enterprise](https://attack.mitre.org/matrices/enterprise/)
  - Windows
  - Linux
  - MacOS
  - Cloud
    - Google Workspace
    - Entra ID
    - Microsoft 365
    - SaaS
    - IaaS
  - Network Devices
  - Containers
  - VMWare ESXi
- [Mobile](https://attack.mitre.org/matrices/mobile/)
  - Android 
  - iOS
- [Industrial Control Systems (ICS)](https://attack.mitre.org/matrices/ics/)

## ATT&CK Tactics

- Tactics represent the "why" of an ATT&CK technique or sub-technique. 
- It is the adversary's tactical goal: the reason for performing an action. 
  - For example, an adversary may want to achieve credential access.
- [Enterprise](https://attack.mitre.org/tactics/enterprise/)
- [Mobile](https://attack.mitre.org/tactics/mobile/)
- [ICS](https://attack.mitre.org/tactics/ics/)

## ATT&CK Techniques

- Techniques represent 'how' an adversary achieves a tactical goal by performing an action. 
  - For example, an adversary may dump credentials to achieve credential access.
- [Enterprise](https://attack.mitre.org/techniques/enterprise/)
- [Mobile](https://attack.mitre.org/techniques/mobile/)
- [ICS](https://attack.mitre.org/techniques/ics/)

## ATT&CK Sub Techniques

- MITRE ATT&CK sub-techniques are more specific versions of a technique.
- A technique is a broad attacker behavior, like Phishing or Command and Scripting Interpreter.
- A sub-technique breaks that into a more precise method, like:
  - Phishing: Spearphishing Attachment
  - Phishing: Spearphishing Link
  - Command and Scripting Interpreter: PowerShell
  - Command and Scripting Interpreter: Windows Command Shell
- The main technique is often too broad to be useful by itself.
- That helps with detection engineering, threat hunting, reporting, and control mapping.

## ATT&CK Data Sources

- Provide the source for the collected telemetry
  - Tactic
    - Reconnaissance
  - Technique
    - Active Scanning
  - Sub Technique
    - Vulnerability Scanning
  - Data Source
    - Network Traffic

## ATT&CK Detections

- High level detection strategies for TTPs
- Focused on techniques and sub techniques
- Guidelines on what to do with collected data

- Tactic
  - Reconnaissance
- Technique
  - Active Scanning
- Sub Technique
  - Vulnerability Scanning
- Detection
  - Network traffic content and flow

## ATT&CK Mitigations

- Preventative configuration to reduce attack surface
- Enables orgs to modify configurations to avoid TTPs
- Not always possible to implement

- [Enterprise](https://attack.mitre.org/mitigations/enterprise/)
- [Mobile](https://attack.mitre.org/mitigations/mobile/)
- [ICS](https://attack.mitre.org/mitigations/ics/)

- Tactic
  - Priviledge Escalation
- Technique
  - Scheduled Task/Job
- Sub Technique
  - Scheduled Task
- Mitigations
  - Priviledged account management

## ATT&CK Groups

- [URL](https://attack.mitre.org/groups/)
- Groups are ATT&CK’s way of organizing “who is doing this” by tying actor clusters to their known tactics and techniques.
- A Group represents an adversary set MITRE tracks, such as an APT, cybercriminal operation, or other intrusion cluster.
  - Each Group entry summarizes:
    - who they are known as
    - aliases
    - suspected origin or motivation
    - campaigns or targeting patterns
    - the ATT&CK techniques/sub-techniques they use

## ATT&CK Software

- [URL](https://attack.mitre.org/software/)
- Tools or malware used by advesaries
- Software is linked to groups, techniques, or campaigns
- Tools can be commercial, open source, publicly availale software
- Malware can be commercial, custom, closed source, open source intended to be used for malicious puroposes

## ATT&CK Campaigns

- [URL](https://attack.mitre.org/campaigns/)
- ATT&CK Campaigns are specific intrusion operations or waves of activity conducted over a period of time.
- A Campaign is a particular set of operations that group carried out.

## ATT&CK Relations

- ATT&CK relations are the links between ATT&CK objects.
- They show how things connect, for example:
  - Groups use Techniques
  - Software uses Techniques
  - Campaigns use Techniques
  - Groups use Software
  - Campaigns are associated with Groups
  - Techniques are mitigated by Mitigations
  - Techniques are detected by Data Sources / Data Components