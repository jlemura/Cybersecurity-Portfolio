# SIEM Analysis – Splunk

**Source:** TryHackMe SOC Level 1 – Module: SIEM  
**Room(s):** Splunk: Basics (46), Investigating with Splunk (48)

**Objective:** Identify suspicious events using Splunk queries and dashboards.

**Steps Performed:**
1. Ingested lab logs into Splunk.
2. Ran search queries to identify anomalies (failed logins, brute force).
3. Built dashboard showing top source IPs and failed logins.

**Findings / IOCs:**
- IP 1.2.3.4 – multiple failed logins
- User accounts compromised: user1, user2

**Response / Mitigation:**
- Block IP and force password reset.
- Configure alert for repeated failed logins.

**Screenshots:**  
- `Screenshots/splunk_search.png`  
- `Screenshots/splunk_dashboard.png`
<img width="1268" height="1304" alt="image" src="https://github.com/user-attachments/assets/706204e5-650e-4b3c-a5ee-10d2a9742f81" />
<img width="1595" height="1289" alt="image" src="https://github.com/user-attachments/assets/4fdc4453-3ca3-4dd2-a27c-e9dc9b5edb51" />
<img width="1580" height="1260" alt="image" src="https://github.com/user-attachments/assets/6e68cf6e-a3ae-4fed-8b34-e9da3eb2fbbc" />
<img width="1570" height="1264" alt="image" src="https://github.com/user-attachments/assets/bcd605c0-fc82-4516-9a09-bf80fd2e5189" />
<img width="1597" height="1294" alt="image" src="https://github.com/user-attachments/assets/fc02d199-ad83-438d-8f04-f90b9a17ecd8" />
<img width="1597" height="1294" alt="image" src="https://github.com/user-attachments/assets/c4e838ab-620d-422d-829d-21f42621bb65" />
