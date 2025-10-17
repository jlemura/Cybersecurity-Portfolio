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

- `Screenshots/splunk_dashboard.png`

---

## Summary

Demonstrates ability to:

- Build and customise advanced Splunk dashboards.  
- Detect anomalous user and login activity.  
- Integrate Splunk visualisations into SOC monitoring and reporting workflows.
