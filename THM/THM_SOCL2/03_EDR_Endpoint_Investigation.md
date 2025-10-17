## 03_SIEM_Investigations

**Source:** TryHackMe SOC Level 2 – Module: SIEM Investigations  
**Room:** Investigating with Splunk

**Objective:** Use SIEM tools to detect suspicious activity.

**Steps Performed:**
1. Ingested lab logs into Splunk.
2. Ran queries to identify failed logins, brute force attempts, and anomalies.
3. Built dashboards to visualize threat patterns.

**Findings / IOCs:**
- Suspicious IPs performing multiple failed logins
- Unusual account activity

**Response / Mitigation Recommendations:**
- Block IPs and force password resets.
- Create alerts for repeated anomalous activity.

**Screenshots:**  
- `Screenshots/splunk_query.png`  
- `Screenshots/splunk_dashboard.png`
