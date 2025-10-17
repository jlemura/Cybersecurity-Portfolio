# 04_Endpoint_Monitoring

**Source:** TryHackMe SOC Level 2 – Module: Endpoint Monitoring  
**Room:** Sysmon & Wazuh Advanced

**Objective:**  
Detect suspicious endpoint activity using Sysmon and Wazuh for threat detection and SOC monitoring.

---

## Methodology

1. Monitored Sysmon events (process creation, network connections).  
2. Reviewed Wazuh alerts for anomalous activity.  
3. Validated suspicious activity against lab scenarios.  
4. Documented findings for SOC reporting.

---

## Key Findings / Indicators of Compromise (IOCs)

| Tool | Example IOC | Description |
|------|-------------|-------------|
| Sysmon | powershell.exe with encoded command | Detected suspicious process execution |
| Wazuh | HOST-02 alert | Host exhibiting anomalous behavior |

---

## Response and Mitigation Recommendations

- Isolate affected endpoints.  
- Reset credentials and perform forensic data collection.  
- Update detection rules and alerts.  
- Integrate endpoint IOCs into SOC response workflows.

---

## Screenshots

`Screenshots/endpoint_monitoring_1.png`  
`Screenshots/endpoint_monitoring_2.png`

---

## Summary

Demonstrates ability to:

- Monitor endpoints for malicious behavior.  
- Detect and document suspicious processes and alerts.  
- Feed findings into SOC triage and mitigation.
