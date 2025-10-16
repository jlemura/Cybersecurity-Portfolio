<img width="2485" height="1238" alt="image" src="https://github.com/user-attachments/assets/451bb389-b195-45a8-8039-98f9da683c34" /># Network Traffic Analysis – Wireshark

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
<img width="2462" height="1237" alt="image" src="https://github.com/user-attachments/assets/c761f81a-6755-4faf-b20f-2542f30249e2" />
<img width="2495" height="1261" alt="image" src="https://github.com/user-attachments/assets/22d97386-2c7a-449f-aa0f-c08225779087" />
<img width="2461" height="1256" alt="image" src="https://github.com/user-attachments/assets/7f3fa0fc-d155-43bf-ab35-ed84960c34d1" />
<img width="2487" height="1266" alt="image" src="https://github.com/user-attachments/assets/88595384-07db-4bd3-9ef0-c4c2e7175e30" />
<img width="2487" height="1242" alt="image" src="https://github.com/user-attachments/assets/3d01f52f-7b02-46f4-bf4e-7ad01e927e08" />
<img width="2485" height="1238" alt="image" src="https://github.com/user-attachments/assets/b9ff6beb-f991-4db0-bdea-9f2c17fb2ce3" />
<img width="2486" height="1235" alt="image" src="https://github.com/user-attachments/assets/e26f4ae2-9eaa-4cf0-9628-4062845be232" />
<img width="2480" height="1253" alt="image" src="https://github.com/user-attachments/assets/35493afc-258c-4648-b0c3-c907ead0dda7" />
<img width="2477" height="1211" alt="image" src="https://github.com/user-attachments/assets/69e822ed-1e9f-4026-b263-f097f7668752" />
<img width="2479" height="1273" alt="image" src="https://github.com/user-attachments/assets/34ca474c-5652-49fd-b356-c27c7969e7cf" />

