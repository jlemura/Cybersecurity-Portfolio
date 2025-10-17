# 01_Log_Analysis

**Source:** TryHackMe SOC Level 2 – Module: Log Analysis  
**Room:** Log Operations

**Objective:**  
Collect, analyze, and interpret system and application logs to detect anomalies and potential threats.

---

## Methodology

1. Collected lab logs from system, application, and security sources.  
2. Parsed and filtered logs to detect suspicious patterns.  
3. Documented anomalous events for SOC reporting.  
4. Validated findings against lab scenarios and known threat indicators.

---

## Key Findings / Indicators of Compromise (IOCs)

| Tool | Example IOC | Description |
|------|-------------|-------------|
| Syslog | Multiple failed logins from unknown IP | Detected brute force attempts |
| App Logs | Service crashes outside normal operations | Potential compromise or misconfiguration |

---

## Response and Mitigation Recommendations

- Escalate incidents for investigation.  
- Block malicious IPs and monitor for repeated activity.  
- Configure alerts for anomalous events in SIEM.  
- Retain and correlate logs for future detection.

---

## Screenshots


---

## Summary

Demonstrates ability to:

- Collect, parse, and analyze logs.  
- Identify suspicious events and IOCs.  
- Document and escalate incidents within SOC workflows.
