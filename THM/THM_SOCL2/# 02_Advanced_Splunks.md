# 02_Advanced_Splunk

**Source:** TryHackMe SOC Level 2 – Module: Advanced Splunk  
**Rooms:** Splunk: Exploring SPL, Splunk: Setting up a SOC Lab, Splunk: Dashboards and Reports, Splunk: Data Manipulation, Fixit

**Objective:**  
Develop advanced Splunk skills for SOC investigations — writing SPL queries, building dashboards, transforming and enriching data, and troubleshooting ingestion/pipeline issues.

---

## Methodology

1. Ingested diverse log types into Splunk and mapped sourcetypes and indexes.  
2. Developed SPL queries to detect anomalies (failed logins, lateral movement, suspicious command lines).  
3. Built dashboards and reports to visualise key security metrics (top source IPs, alert counts, user anomalies).  
4. Performed data manipulation (field extraction, lookups, eventstats/transaction) and fixed ingestion errors.

---

## Key Findings / Indicators of Compromise (IOCs)

> Replace with actual Splunk query outputs and artifacts.

| Tool | Example IOC | Description |
|------|-------------|-------------|
| Splunk SPL | `index=security | stats count by src_ip` shows `10.10.10.10` with high fail count | Indicative of brute-force |
| Saved Search / Dashboard | Spike in failed login rate at 2025-XX-XX | Correlates with suspicious events in endpoint logs |

---

## Response & Mitigation Recommendations

- Configure saved searches and alert throttling for high-fidelity alerts.  
- Implement scheduled lookups/enrichment for IP reputation and user context.  
- Document dashboards for SOC on-call and shift handover.  
- Troubleshoot and fix ingest pipeline issues to ensure full visibility.

---

## Screenshots

`Screenshots/splunk_spl_query.png`  
`Screenshots/splunk_dashboard_report.png`  
`Screenshots/splunk_data_manipulation.png`

---

## Summary

This module demonstrates advanced Splunk capability: creating detection queries, building dashboards for SOC operations, and maintaining reliable ingestion and data quality for investigations.
