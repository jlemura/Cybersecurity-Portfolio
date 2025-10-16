# Network Traffic Analysis – Wireshark

**Source:** TryHackMe SOC Level 1 – Module: Network Security  
**Room(s):** Wireshark: The Basics (27), Wireshark: Traffic Analysis (29), TShark (31)

**Objective:** Analyze network traffic for anomalies and potential threats.

**Steps Performed:**
1. Captured network traffic using Wireshark.
2. Filtered packets for suspicious HTTP/DNS traffic.
3. Used TShark CLI for automated filtering.

**Findings / IOCs:**
- Suspicious domain: bad-domain.example.com
- Endpoint: 10.0.0.5 sending POST requests

**Response / Mitigation:**
- Block malicious domain at firewall.
- Isolate affected host and investigate further.

**Screenshots:**  
- `Screenshots/wireshark_capture.png`  
- `Screenshots/tshark_command.png`
