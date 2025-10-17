# 05_SIEM_Analysis_L2

**Source:** TryHackMe SOC Level 2 – Module: SIEM Analysis  
**Room:** Splunk Advanced

**Objective:**  
Identify suspicious events using advanced Splunk queries and dashboards for SOC investigations.

---

## Methodology

1. Ingested lab logs into Splunk.  
2. Ran advanced searches for anomalies (failed logins, brute force).  
3. Built dashboards visualizing top source IPs and alert triggers.  
4. Documented IOCs and correlated them with lab events.

---

## Key Findings / Indicators of Compromise (IOCs)

| Tool | Example IOC | Description |
|------|-------------|-------------|
| Splunk | IP 10.10.10.10 repeated failed logins | Brute force attempt simulation |
| User Accounts | userA, userB | Compromised in lab scenario |

---

## Response and Mitigation Recommendations

- Block malicious IPs and enforce password resets.  
- Configure alerts for repeated failed logins.  
- Document dashboards for ongoing SOC monitoring.  
- Feed IOC data into incident response playbooks.

---

## Screenshots

`Screenshots/splunk_analysis_1.png`  
`Screenshots/splunk_analysis_2.png`

---

## Summary

Demonstrates ability to:

- Query and visualize SIEM data.  
- Detect suspicious events and IOCs.  
- Feed intelligence into SOC monitoring and response.
