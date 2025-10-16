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
