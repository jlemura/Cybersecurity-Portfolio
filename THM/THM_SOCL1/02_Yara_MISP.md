# YARA & MISP Threat Intelligence

**Source:** TryHackMe SOC Level 1 – Module: Cyber Threat Intelligence  

**Objective:**  
Develop the ability to detect threats using YARA rules and analyze threat intelligence in MISP, integrating findings into SOC detection workflows.

---

## Methodology

1. Created custom YARA rules to identify suspicious binaries and malware patterns.  
2. Imported threat events and IOCs into MISP for centralised threat intelligence management.  
3. Cross-referenced IOCs against lab datasets to validate malicious activity and verify detection.  
4. Documented findings for SOC monitoring and mitigation planning.  

---

## Key Findings / Indicators of Compromise (IOCs)

| Tool | Example IOC | Description |
|------|-------------|-------------|
| YARA | Custom rule detecting ransomware hash patterns | Successfully flagged test binaries exhibiting malicious characteristics. |
| MISP | IP `10.0.0.5` | Identified as malicious within lab threat feed; linked to simulated attack scenario. |

---

## Response and Mitigation Recommendations

- Deploy verified YARA rules across endpoints to detect suspicious files in real-time.  
- Continuously update SOC alerts and detection rules using MISP threat intelligence feeds.  
- Incorporate cross-referenced IOCs into incident response playbooks for triage and escalation.  
- Regularly validate YARA rules and MISP events against new threat datasets to ensure accuracy.

---

## Screenshots

**YARA Rule Example**  
<img width="740" height="440" alt="YARA Rule" src="https://github.com/user-attachments/assets/03a7e5fb-a261-497a-b57d-10283f617299" />

**MISP Event Analysis**  
<img width="567" height="171" alt="MISP Event" src="https://github.com/user-attachments/assets/8e26ed05-7215-467f-80a4-009d066e3d1d" />

**YARA Rule Testing / Execution Logs**  
<img width="1259" height="1306" alt="YARA Execution" src="https://github.com/user-attachments/assets/f47602e2-35d9-41fa-a285-30343214f61b" />

**Threat Intelligence Correlation in MISP**  
<img width="1100" height="296" alt="MISP Correlation" src="https://github.com/user-attachments/assets/11c62d76-aa32-4607-8ca7-73d9266dd17c" />

**IOC Cross-Referencing and Verification**  
<img width="1248" height="1080" alt="IOC Verification" src="https://github.com/user-attachments/assets/8bd8ae8b-472d-4fb5-96cd-df561dc5f2ea" />

**YARA Rule Detection Output**  
<img width="1147" height="917" alt="YARA Detection" src="https://github.com/user-attachments/assets/a5046ff8-a523-4127-822d-cf8dec799d09" />

**MISP Event Details**  
<img width="1086" height="721" alt="MISP Event Details" src="https://github.com/user-attachments/assets/81b33a15-36af-4b8d-8e35-5681f1bd1505" />

**Final Threat Intelligence Summary**  
<img width="1265" height="1103" alt="Threat Intelligence Summary" src="https://github.com/user-attachments/assets/982cd13b-8a9d-4552-b046-cff056c86d4f" />

---

## Summary

This module demonstrates the ability to:

- Create and apply YARA rules for malware detection.  
- Import, analyze, and correlate threat intelligence using MISP.  
- Identify, validate, and document IOCs to enhance SOC monitoring and response.  
- Translate threat intelligence into actionable SOC detection rules and incident response workflows.
