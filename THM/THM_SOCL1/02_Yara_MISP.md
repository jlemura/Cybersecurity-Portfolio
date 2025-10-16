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
