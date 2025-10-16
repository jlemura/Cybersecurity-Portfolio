# Endpoint Monitoring – Sysmon & Wazuh

**Source:** TryHackMe SOC Level 1 – Module: Endpoint Monitoring  
**Room(s):** Windows Event Logs (37), Sysmon (38), Wazuh (40)

**Objective:** Detect suspicious activity on endpoints.

**Steps Performed:**
1. Monitored Sysmon EventID=1 for process creation.
2. Checked Wazuh alerts for suspicious activity.
3. Documented findings for SOC review.

**Findings / IOCs:**
- Suspicious process: powershell.exe with encoded command
- Host: HOST-01

**Response / Mitigation:**
- Isolate host and collect logs.
- Reset credentials and monitor.

**Screenshots:**  
- `Screenshots/sysmon_event.png`  
- `Screenshots/wazuh_alert.png`
