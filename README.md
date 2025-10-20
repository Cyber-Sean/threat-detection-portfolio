Hi! I'm Sean — a cybersecurity professional with 6+ years in SIEM, IAM, and MDR sales, now transitioning into hands-on detection engineering.

This portfolio highlights my practical experience building detection logic, using SIEM tools, and mapping threats to the MITRE ATT&CK framework.

---

## Projects

### Splunk Detection Queries
- Use case: Suspicious PowerShell activity
- Logic: Searches `powershell.exe` events with encoded commands or bypass flags
- Mapped to: MITRE T1059.001
- Tools: Splunk, Windows Event Logs
- [View query](link-to-your-file)

---

### MITRE ATT&CK Mapping
- Technique: T1078 (Valid Accounts)
- Detection Idea: Multiple failed logins followed by successful login from unusual location
- Tool: Sigma Rule + Splunk Query
- [View Sigma Rule](link)

---

### Custom SOAR Playbook (Pseudocode)
- Scenario: Alert on unusual logon → auto-send to Slack → enrich with VirusTotal → tag user
- Tool: Cortex XSOAR
- [View Playbook Design](link or image)

---

## Labs Completed
| Lab/Platform | Description |
|--------------|-------------|
| Cisco ECSS | Splunk + Cisco integration for threat detection |
| TryHackMe SOC Level 1 | Blue team basics and log analysis |
| DetectionLab | Built local lab for testing detection rules |

---

## Skills
- Splunk, Sigma, Elastic Stack
- MITRE ATT&CK Mapping
- Python (basic scripting)
- Log analysis, Detection Engineering, SOAR

#cybersecurity #infosec #detection #detection-engineer #engineer #splunk #blue-team #mitre-attack
