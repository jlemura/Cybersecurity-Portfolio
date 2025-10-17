# Endpoint Monitoring – Sysmon & Wazuh

**Source:** TryHackMe SOC Level 1 – Module: Endpoint Monitoring  
**Rooms Completed:** Windows Event Logs (37), Sysmon (38), Wazuh (40)  

**Objective:**  
Detect suspicious activity on endpoints and leverage endpoint monitoring tools to identify indicators of compromise (IOCs) and escalate incidents within SOC workflows.

---

## Methodology

1. Monitored **Sysmon Event ID 1** (process creation) for abnormal or unexpected processes.  
2. Checked **Wazuh alerts** for suspicious activity patterns, including unusual command-line arguments and process behavior.  
3. Documented findings for review and correlation in SOC dashboards.  
4. Escalated confirmed suspicious activity according to incident response procedures.  

---

## Key Findings / Indicators of Compromise (IOCs)

| IOC Type | Value | Description |
|----------|-------|-------------|
| Suspicious Process | `powershell.exe` with encoded command | Potential malicious script execution for lateral movement or data exfiltration. |
| Host | `HOST-01` | Endpoint exhibiting suspicious process execution flagged by Wazuh. |

---

## Response and Mitigation

- Isolate the affected host to prevent further spread of potential malware.  
- Collect logs and system artifacts for forensic analysis.  
- Reset compromised credentials and monitor for further suspicious activity.  
- Update SOC rules and alerts to detect similar patterns across other endpoints.  

---

## Screenshots

**Sysmon Event – Process Creation**  
<img width="1470" height="956" alt="Sysmon Event" src="https://github.com/user-attachments/assets/34525d84-8783-437f-9a24-935115a315bf" />

**Wazuh Alert – Suspicious Activity**  
<img width="1470" height="956" alt="Wazuh Alert" src="https://github.com/user-attachments/assets/508bd91f-c8fc-478d-8cd6-9b4bfc7657d6" />

**Suspicious Process Details**  
<img width="1470" height="956" alt="Suspicious Process" src="https://github.com/user-attachments/assets/f979b5a1-8314-4ecc-b49e-7070c05a626b" />

**Endpoint Monitoring Overview**  
<img width="1470" height="956" alt="Endpoint Monitoring" src="https://github.com/user-attachments/assets/c12245d8-f1cc-4dc7-b50b-0ba0221f2476" />

**Additional Sysmon/Wazuh Findings**  
<img width="1470" height="956" alt="Sysmon/Wazuh Additional Findings" src="https://github.com/user-attachments/assets/d4356f36-2b2e-4875-ba6d-cfb972bcefd2" />

**Final Endpoint Assessment**  
<img width="1470" height="956" alt="Final Endpoint Assessment" src="https://github.com/user-attachments/assets/e07dbf7a-373d-47ab-baa1-018e66918cb3" />

---

## Summary

This module demonstrates the ability to:

- Monitor and analyze endpoint activity using Sysmon and Wazuh.  
- Identify suspicious processes and other IOCs for SOC triage.  
- Escalate confirmed incidents following SOC incident response procedures.  
- Apply endpoint monitoring insights to improve detection and mitigation strategies across the environment.
