# 01_Splunk_Failed_Logins

**Source:** TryHackMe SOC Level 2 – Mini-Project  
**Room:** Splunk: Dashboards and Reports

**Objective:**  
Visualize and analyze failed login attempts to detect brute force attempts and account anomalies.

---

## Methodology

1. Loaded lab or sample logs into Splunk.  
2. Created searches for failed login attempts.  
3. Built dashboard panels to show top source IPs and accounts with the most failed logins.  
4. Validated dashboard metrics against lab findings.

---

## Key Findings / Indicators of Compromise (IOCs)

| Tool | Example IOC | Description |
|------|-------------|-------------|
| Splunk Dashboard | Multiple failed logins from IP `10.10.10.10` | Potential brute force attempt |
| Splunk Dashboard | Admin user anomaly | Account showing unusual login behaviour |

---

## Response & Mitigation Recommendations

- Configure alerts for repeated failed logins.  
- Monitor and block suspicious IPs.  
- Share dashboards with SOC team for real-time monitoring.

---

## Screenshots

- `Screenshots/splunk_failed_logins_dashboard.png`

---

## Summary

Demonstrates ability to:

- Ingest logs into Splunk.  
- Create searches and dashboards.  
- Identify anomalous login behaviour.  
- Produce actionable visualizations for SOC monitoring.
