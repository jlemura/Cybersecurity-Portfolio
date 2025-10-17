# SIEM Analysis – Splunk

**Source:** TryHackMe SOC Level 1 – Module: SIEM  
**Rooms Completed:** Splunk: Basics (46), Investigating with Splunk (48)  

**Objective:**  
Identify suspicious events and potential security incidents by leveraging Splunk queries, dashboards, and log analysis.

---

## Methodology

1. Ingested lab logs into **Splunk** for centralized analysis.  
2. Ran targeted search queries to detect anomalies such as failed logins and brute-force attempts.  
3. Built dashboards to visualize top source IPs, user account activity, and suspicious events.  
4. Documented IOCs and escalated relevant findings for SOC monitoring and response.  

---

## Key Findings / Indicators of Compromise (IOCs)

| IOC Type | Value | Description |
|----------|-------|-------------|
| Source IP | `1.2.3.4` | Detected multiple failed login attempts indicating brute-force behavior. |
| User Accounts | `user1`, `user2` | Accounts impacted by repeated failed logins; potential compromise. |

---

## Response and Mitigation

- Block malicious IP addresses at network or firewall level.  
- Force password reset for affected user accounts.  
- Configure Splunk alerts for repeated failed logins or abnormal activity patterns.  
- Integrate findings into SOC workflows for ongoing monitoring and threat detection.  

---

## Screenshots

**Splunk Search – Failed Logins**  
<img width="1268" height="1304" alt="Splunk Search" src="https://github.com/user-attachments/assets/706204e5-650e-4b3c-a5ee-10d2a9742f81" />

**Dashboard – Top Source IPs and Failed Logins**  
<img width="1595" height="1289" alt="Splunk Dashboard" src="https://github.com/user-attachments/assets/4fdc4453-3ca3-4dd2-a27c-e9dc9b5edb51" />

**Event Analysis – Brute Force Attempts**  
<img width="1580" height="1260" alt="Brute Force Events" src="https://github.com/user-attachments/assets/6e68cf6e-a3ae-4fed-8b34-e9da3eb2fbbc" />

**User Account Login Failures**  
<img width="1570" height="1264" alt="User Login Failures" src="https://github.com/user-attachments/assets/bcd605c0-fc82-4516-9a09-bf80fd2e5189" />

**Dashboard Overview**  
<img width="1597" height="1294" alt="Dashboard Overview" src="https://github.com/user-attachments/assets/fc02d199-ad83-438d-8f04-f90b9a17ecd8" />

**Detailed Event Log Analysis**  
<img width="1597" height="1294" alt="Event Log Details" src="https://github.com/user-attachments/assets/c4e838ab-620d-422d-829d-21f42621bb65" />

---

## Summary

This module demonstrates the ability to:

- Ingest and analyze security logs using Splunk.  
- Detect suspicious activity including brute-force attempts and account compromise.  
- Visualize security events via dashboards for SOC monitoring.  
- Translate log analysis into actionable mitigation and alerting strategies.
