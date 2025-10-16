# Threat Intelligence

**Source:** TryHackMe SOC Level 1 – Module: Cyber Threat Intelligence  

**Objective:** Detect threats using Yara rules and analyze intelligence in MISP.

**Steps Performed:**
1. Created a Yara rule to detect suspicious binaries.
2. Imported threat events into MISP.
3. Cross-referenced IOCs against lab datasets.

**Findings / IOCs:**
- Yara rule example: detects ransomware hash pattern
- MISP event: IP 10.0.0.5 flagged

**Response / Mitigation Recommendations:**
- Deploy Yara rules on endpoints.
- Update SOC alerts from MISP intelligence.

**Screenshots:**  
- `Screenshots/yara_rule.png`  
- `Screenshots/misp_event.png`



<img width="2487" height="1272" alt="image" src="https://github.com/user-attachments/assets/6d6e7b06-957b-4a6e-99f1-c761626f8876" />
<img width="2488" height="1262" alt="image" src="https://github.com/user-attachments/assets/298525bd-f286-4024-87fc-d32fc56f781c" />

<img width="740" height="440" alt="image" src="https://github.com/user-attachments/assets/03a7e5fb-a261-497a-b57d-10283f617299" />

<img width="567" height="171" alt="image" src="https://github.com/user-attachments/assets/8e26ed05-7215-467f-80a4-009d066e3d1d" />
<img width="1259" height="1306" alt="image" src="https://github.com/user-attachments/assets/f47602e2-35d9-41fa-a285-30343214f61b" />
<img width="1100" height="296" alt="image" src="https://github.com/user-attachments/assets/11c62d76-aa32-4607-8ca7-73d9266dd17c" />

<img width="1248" height="1080" alt="image" src="https://github.com/user-attachments/assets/8bd8ae8b-472d-4fb5-96cd-df561dc5f2ea" />
<img width="1147" height="917" alt="image" src="https://github.com/user-attachments/assets/a5046ff8-a523-4127-822d-cf8dec799d09" />

<img width="1086" height="721" alt="image" src="https://github.com/user-attachments/assets/81b33a15-36af-4b8d-8e35-5681f1bd1505" />

<img width="1265" height="1103" alt="image" src="https://github.com/user-attachments/assets/982cd13b-8a9d-4552-b046-cff056c86d4f" />
