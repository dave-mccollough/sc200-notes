# Security Operations Center

## Cybersecurity Challenges

- Lack of skilled cybersecurity people
- Lack of automation
- Disconnected products
- Noisy alerts and false positives
- Sophisticated Threats
- Access to data
- Changing regulatory landscape
- Most alerts never get investigated

## What is a Security Operations Center (SOC)

- The following activities are carried out by a SOC and typically fall under the SOC Analyst role
  - Threat Intelligence
  - Threat Hunting
  - Log Management
  - Reducing Attack Surface
  - Threat Detection
  - Root Cause Investigation
  - Recovery and Remidiation
  - Incident Response

## SOC Model

- Automation
  - Commodity Malware
  - Repetitive Tasks
  - Automates analyst actions
- Tier 1
  - 70% of alerts
  - Commodity Malware
  - Easier tasks that should not be automated
- Tier 2
  - 25% of alerts
  - Advanced Malware
  - Hard tasks
- Tier 3
  - 5% of alerts
  - Proactive Threat Hunting
  - Advanced Forensics

## Security Incident Response Handling

- [NIST 800-61: Computer Security Incident Handling Guide](https://nvlpubs.nist.gov/nistpubs/specialpublications/nist.sp.800-61r2.pdf)

- Preperation
  - Develop processes
- Detection and Analysis
  - When incident occurs
  - How severe is the incident 
  - Triaging
- Containment, Eradication and Recovery
  - Contain incident
    - Isolate devices
    - Disabling users
  - Eradication
  - Recovery
- Post incident Activity
  - Lessons learned

## EDR, XDR, SIEM, SOAR

- EDR
  - Defender for Endpoint
    - Endpoint Detection and Response
    - Behavior Monitoring for Endpoints

- XDR
  - Defender XDR
  - Defender for Cloud
    - Extended Detection and Response
    - Behavior monitoring beyond the endpoint

- SIEM
  - Microsoft Sentinel
    - Security Information and Event Management
    - Centralized collection, correlation, and log analysis

- SOAR
  - Microsoft Sentinel and Logic Apps
    - Security Orchestration, Automation and Response
    - Automates incident response procedures

## Blue, Red and Purple Teaming

- Blue and Red Teaming
  - Security Monitoring
  - Incident Response
  - Forensics
  - Threat Hunting
  - Vulnerability Assessments
  - Penetration Testing
  - Social Engineering
  - Simulate Advesary TTPs

- Purple Teaming
  - Blue and Red collaborate to improve security posture
  - Collaborative simulation of advesary TTPs
  - Drastic upskilling of both teams
