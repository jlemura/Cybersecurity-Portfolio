# Endpoint Monitoring – Sysmon & Wazuh

**Source:** TryHackMe SOC Level 1 – Module: Endpoint Monitoring  
**Rooms Completed:** Windows Event Logs (37), Sysmon (38), Wazuh (40)  

**Objective:**  
Detect suspicious activity on endpoints and use monitoring tools to identify indicators of compromise (IOCs) for SOC analysis.

---

## Methodology

1. Monitored **Sysmon Event ID 1** (process creation) to detect abnormal processes.  
2. Reviewed **Wazuh alerts** for suspicious activity patterns.  
3. Documented findings for SOC review and escalation.  

---

## Key Findings / Indicators of Compromise (IOCs)

| IOC Type | Value | Description |
|----------|-------|-------------|
| Suspicious Process | `powershell.exe` with encoded command | Potential malicious execution or script-based attack. |
| Host | `HOST-01` | Endpoint exhibiting unusual process creation flagged by Wazuh. |

---

## Response and Mitigation

- Isolate the affected host to prevent lateral movement.  
- Collect system logs and artifacts for forensic analysis.  
- Reset affected user credentials and monitor for further suspicious activity.  
- Update SOC monitoring rules to detect similar patterns.

---

## Screenshots

**Sysmon Event Log – Process Creation**  
<img width="1470" height="956" alt="Sysmon Event ID 1 showing powershell.exe process creation with encoded command" src="https://github.com/user-attachments/assets/34525d84-8783-437f-9a24-935115a315bf" />

**Wazuh Alert Dashboard – Suspicious Activity Detected**  
<img width="1470" height="956" alt="Wazuh dashboard highlighting alerts for powershell.exe suspicious process on HOST-01" src="https://github.com/user-attachments/assets/508bd91f-c8fc-478d-8cd6-9b4bfc7657d6" />

**Detailed Sysmon Event Analysis**  
<img width="1470" height="956" alt="Expanded Sysmon event details showing command line, user, and process hashes" src="https://github.com/user-attachments/assets/f979b5a1-8314-4ecc-b49e-7070c05a626b" />

**Endpoint Monitoring Summary**  
<img width="1470" height="956" alt="Wazuh monitoring overview showing HOST-01 activity and alerts timeline" src="https://github.com/user-attachments/assets/c12245d8-f1cc-4dc7-b50b-0ba0221f2476" />

**Additional Wazuh Findings – Correlated Alerts**  
<img width="1470" height="956" alt="Correlated Wazuh alerts for powershell.exe across multiple endpoints in lab environment" src="https://github.com/user-attachments/assets/d4356f36-2b2e-4875-ba6d-cfb972bcefd2" />

**Final Endpoint Assessment**  
<img width="1470" height="956" alt="Summary of HOST-01 endpoint assessment showing all flagged events and recommended actions" src="https://github.com/user-attachments/assets/e07dbf7a-373d-47ab-baa1-018e66918cb3" />
