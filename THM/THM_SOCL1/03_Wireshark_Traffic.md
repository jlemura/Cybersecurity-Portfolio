# Network Traffic Analysis – Wireshark

**Source:** TryHackMe SOC Level 1 – Module: Network Security  
**Rooms Completed:** Wireshark: The Basics (27), Wireshark: Traffic Analysis (29), TShark (31)  

**Objective:**  
Capture and analyze network traffic to identify anomalies, potential threats, and indicators of compromise using Wireshark and TShark.

---

## Methodology

1. Captured live network traffic using **Wireshark** on lab endpoints.  
2. Applied filters to isolate suspicious HTTP and DNS traffic.  
3. Used **TShark CLI** to automate packet filtering and log extraction.  
4. Documented suspicious domains, IPs, and packet behaviors for SOC monitoring.  

---

## Key Findings / Indicators of Compromise (IOCs)

| IOC Type | Value | Description |
|----------|-------|-------------|
| Suspicious Domain | `bad-domain.example.com` | Observed DNS queries and responses indicating potential C2 communication or malicious activity. |
| Endpoint | `10.0.0.5` | Sent multiple POST requests to the suspicious domain, indicating potential data exfiltration or malware activity. |

---

## Response and Mitigation

- Block malicious domain at the network perimeter or firewall.  
- Isolate affected host for further investigation and remediation.  
- Correlate captured network activity with other SOC alerts and logs.  
- Review endpoint for malware or unauthorized processes based on captured traffic.  

---

## Screenshots

**Network Traffic Capture Overview**  
<img width="2462" height="1237" alt="Wireshark Capture Overview" src="https://github.com/user-attachments/assets/c761f81a-6755-4faf-b20f-2542f30249e2" />

**Suspicious HTTP POST Requests**  
<img width="2495" height="1261" alt="Suspicious HTTP POST" src="https://github.com/user-attachments/assets/22d97386-2c7a-449f-aa0f-c08225779087" />

**DNS Traffic Analysis**  
<img width="2461" height="1256" alt="DNS Traffic" src="https://github.com/user-attachments/assets/7f3fa0fc-d155-43bf-ab35-ed84960c34d1" />

**TShark Packet Filtering CLI**  
<img width="2487" height="1266" alt="TShark CLI Filtering" src="https://github.com/user-attachments/assets/88595384-07db-4bd3-9ef0-c4c2e7175e30" />

**Suspicious Traffic Timeline**  
<img width="2487" height="1242" alt="Traffic Timeline" src="https://github.com/user-attachments/assets/3d01f52f-7b02-46f4-bf4e-7ad01e927e08" />

**Endpoint-Host Communication Analysis**  
<img width="2485" height="1238" alt="Endpoint Communication" src="https://github.com/user-attachments/assets/b9ff6beb-f991-4db0-bdea-9f2c17fb2ce3" />

**Packet Details – Malicious POST Payloads**  
<img width="2486" height="1235" alt="POST Payloads" src="https://github.com/user-attachments/assets/e26f4ae2-9eaa-4cf0-9628-4062845be232" />

**Protocol Hierarchy and Statistics**  
<img width="2480" height="1253" alt="Protocol Stats" src="https://github.com/user-attachments/assets/35493afc-258c-4648-b0c3-c907ead0dda7" />

**Filtered Suspicious Packets**  
<img width="2477" height="1211" alt="Filtered Packets" src="https://github.com/user-attachments/assets/69e822ed-1e9f-4026-b263-f097f7668752" />

**Final Traffic Summary and Findings**  
<img width="2479" height="1273" alt="Traffic Summary" src="https://github.com/user-attachments/assets/34ca474c-5652-49fd-b356-c27c7969e7cf" />

---

## Summary

This module demonstrates the ability to:

- Capture and analyze network traffic for anomalies and suspicious activity.  
- Identify indicators of compromise such as malicious domains and endpoint behaviors.  
- Use Wireshark and TShark effectively for SOC monitoring and incident response.  
- Translate network analysis into actionable mitigation steps for SOC operations.
