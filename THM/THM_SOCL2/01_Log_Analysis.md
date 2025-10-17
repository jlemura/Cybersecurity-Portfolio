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
Log Analysis Dashboard
<img width="1999" height="1125" alt="caeace06b70e4c6920d32ae0bf22e8f4" src="https://github.com/user-attachments/assets/290c36e2-0c5f-49ed-b389-d9ac4053c7b2" />

Common Log File Locations
<img width="878" height="908" alt="image" src="https://github.com/user-attachments/assets/f704a13a-7cf2-4d74-b869-1980e4fd9684" />

Seraching through logs examples
<img width="2508" height="1252" alt="image" src="https://github.com/user-attachments/assets/ada9f242-18ce-4d02-bf7e-76f62ed9a679" />
<img width="2484" height="1230" alt="image" src="https://github.com/user-attachments/assets/e00e5a37-fd10-4c10-8027-b49d27f83170" />



---

## Summary

Demonstrates ability to:

- Collect, parse, and analyze logs.  
- Identify suspicious events and IOCs.  
