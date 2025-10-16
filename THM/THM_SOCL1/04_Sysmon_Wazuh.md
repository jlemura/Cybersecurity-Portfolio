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
<img width="1470" height="956" alt="Screenshot 2025-10-17 at 9 23 43 AM" src="https://github.com/user-attachments/assets/34525d84-8783-437f-9a24-935115a315bf" />
<img width="1470" height="956" alt="Screenshot 2025-10-17 at 9 25 41 AM" src="https://github.com/user-attachments/assets/508bd91f-c8fc-478d-8cd6-9b4bfc7657d6" />
<img width="1470" height="956" alt="Screenshot 2025-10-17 at 9 29 39 AM" src="https://github.com/user-attachments/assets/f979b5a1-8314-4ecc-b49e-7070c05a626b" />
<img width="1470" height="956" alt="Screenshot 2025-10-17 at 9 33 31 AM" src="https://github.com/user-attachments/assets/c12245d8-f1cc-4dc7-b50b-0ba0221f2476" />

