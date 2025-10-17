# 07_Endpoint_Detection_Response

**Source:** TryHackMe SOC Level 2 – Module: Endpoint Detection & Response  
**Room:** EDR Fundamentals

**Objective:**  
Detect, investigate, and respond to endpoint threats using EDR tools to support SOC operations.

---

## Methodology

1. Deployed EDR agent on lab endpoints.  
2. Monitored EventID logs and process activity for suspicious behavior.  
3. Investigated flagged endpoints for potential compromise.  
4. Documented findings and correlated with lab threat scenarios.

---

## Key Findings / Indicators of Compromise (IOCs)

| Tool | Example IOC | Description |
|------|-------------|-------------|
| EDR Console | `powershell.exe` executing encoded command | Indicates potential malicious activity |
| Endpoint Logs | Unusual process spawned by `explorer.exe` | Possible persistence technique or compromise |

---

## Response & Mitigation Recommendations

- Isolate affected endpoints immediately.  
- Collect forensic logs and snapshots for further investigation.  
- Reset impacted accounts and enforce MFA where applicable.  
- Update detection rules to catch similar behavior in future.

---

## Screenshots

- `Screenshots/edr_alert_console.png`  
- `Screenshots/endpoint_process_investigation.png`

---

## Summary

Demonstrates ability to:

- Detect and investigate endpoint anomalies.  
- Correlate EDR alerts with threat scenarios.  
- Execute containment and remediation procedures in a SOC environment.
