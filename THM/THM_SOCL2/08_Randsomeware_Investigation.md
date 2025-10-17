# 08_Ransomware_Investigation

**Source:** TryHackMe SOC Level 2 – Module: Ransomware Response  
**Room:** Ransomware Analysis & Mitigation

**Objective:**  
Detect, investigate, and respond to ransomware infections in lab environments.

---

## Methodology

1. Identified ransomware activity on endpoints.  
2. Analyzed file changes, encryption events, and process behavior.  
3. Documented IOCs and mitigation strategies.  
4. Recommended SOC response actions for containment.

---

## Key Findings / Indicators of Compromise (IOCs)

| Tool | Example IOC | Description |
|------|-------------|-------------|
| Endpoint | CryptoLocker.exe | Malicious ransomware process |
| File Changes | Encrypted .docx files | Lab simulation of ransomware encryption |

---

## Response and Mitigation Recommendations

- Isolate infected endpoints.  
- Restore from clean backups.  
- Update SOC alerts and detection rules.  
- Educate users on ransomware mitigation.

---

## Screenshots

`Screenshots/ransomware_1.png`  
`Screenshots/ransomware_2.png`

---

## Summary

Demonstrates ability to:

- Detect and investigate ransomware activity.  
- Document IOCs and escalation paths.  
- Feed findings into SOC monitoring and mitigation.
