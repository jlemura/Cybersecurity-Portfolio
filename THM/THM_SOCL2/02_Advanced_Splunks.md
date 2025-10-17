# 02_Advanced_Splunk

**Source:** TryHackMe SOC Level 2 – Module: Advanced Splunk  
**Room:** Splunk: Dashboards and Reports

**Objective:**  
Demonstrate advanced Splunk dashboard creation to visualise security telemetry and support SOC operations.

---

## Methodology

1. Loaded lab logs into Splunk.  
2. Created dashboards showing top failed login sources and user anomalies.  
3. Applied filters and visualisations to highlight critical events.  
4. Validated dashboard metrics against lab findings.

---

## Key Findings / Indicators of Compromise (IOCs)

| Tool | Example IOC | Description |
|------|-------------|-------------|
| Splunk Dashboard | Spike in failed logins from IP `10.10.10.10` | Possible brute force attempt |
| Splunk Dashboard | Admin user account anomalies | Indicates potential compromise or misuse |

---

## Response & Mitigation Recommendations

- Configure alerts on critical spikes (failed logins, anomalous accounts).  
- Share dashboards with SOC team for monitoring.  
- Ensure logging is complete and dashboards refreshed regularly.

---

## Screenshots
Creating a Report
<img width="2520" height="1196" alt="image" src="https://github.com/user-attachments/assets/0c14ed3f-8665-4bcd-91f6-767186a9e84d" />

Network Report
<img width="2530" height="1235" alt="image" src="https://github.com/user-attachments/assets/c18a8600-11e4-46b7-9797-e957b3b561ec" />

Custom Dashboard
<img width="2541" height="952" alt="image" src="https://github.com/user-attachments/assets/4dbb5885-cf84-41e9-ab92-d955151a62d5" />

Creatign an alert
<img width="992" height="750" alt="9960a9f78306e77c708469cf9f4ff582" src="https://github.com/user-attachments/assets/08d8023c-b455-430a-ba47-f43da0c46dec" />


---

## Summary

Demonstrates ability to:

- Build and customise advanced Splunk dashboards.  
- Detect anomalous user and login activity.  
- Integrate Splunk visualisations into SOC monitoring and reporting workflows.
