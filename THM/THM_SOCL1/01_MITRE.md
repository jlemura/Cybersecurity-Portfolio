# MITRE & Cyber Defence Frameworks

**Source:** TryHackMe SOC Level 1 – Module: Cyber Defence Frameworks  
**Rooms Completed:** MITRE (9), Cyber Kill Chain (6)  

**Objective:**  
To develop a practical understanding of how adversarial tactics and techniques align with the MITRE ATT&CK and Cyber Kill Chain frameworks, and to apply this knowledge to improve SOC detection, triage, and response procedures.

---

## Methodology

1. Reviewed the MITRE ATT&CK Enterprise Matrix to identify relevant adversarial tactics and techniques.  
2. Analysed simulated attack data within the TryHackMe environment to identify mapped ATT&CK techniques.  
3. Correlated each phase of the Cyber Kill Chain with corresponding ATT&CK tactics.  
4. Documented Indicators of Compromise (IOCs), detection rules, and mitigation steps.  
5. Mapped findings to SOC workflows for incident triage and escalation.

---

## Key Findings

| Technique ID | Technique Name | Description | Relevant Tactic |
|---------------|----------------|--------------|----------------|
| **T1110** | Brute Force | Multiple consecutive failed logins from the same source, indicating possible credential-stuffing or brute-force activity. | Credential Access |
| **T1059** | Command and Scripting Interpreter | Evidence of encoded PowerShell commands suggesting script-based execution or lateral movement attempts. | Execution |

---

## Response and Mitigation Recommendations

- Monitor and correlate Windows `Event ID 4625` (failed logons) and `Event ID 4104` (PowerShell script block logging) for early brute-force and execution detection.  
- Implement detection logic for repeated login failures followed by successful authentication from the same IP.  
- Enforce PowerShell script signing and restrict execution policies via Group Policy.  
- Map these detections into the SIEM to enable Tier 1 analysts to escalate incidents aligned with MITRE and internal SOC playbooks.

---

## MITRE Mapping

| Tactic | Example Techniques | Detection Focus |
|--------|--------------------|----------------|
| **Credential Access** | T1110 – Brute Force | Login attempts from same IP across multiple accounts. |
| **Execution** | T1059 – Command and Scripting Interpreter | Encoded or obfuscated PowerShell command usage. |
| **Persistence** | T1547 – Boot or Logon Autostart Execution | Registry and startup location monitoring. |
| **Privilege Escalation** | T1068 – Exploitation for Privilege Escalation | Privilege change event correlation. |
| **Defense Evasion** | T1070 – Indicator Removal on Host | Detection of log deletions or tampering attempts. |

---

## Screenshots

**MITRE ATT&CK Matrix Exploration**  
<img width="2474" height="1280" alt="MITRE Matrix" src="https://github.com/user-attachments/assets/9c0fad72-bc37-4d63-8450-759ba7332fb8" />

**Technique Identification**  
<img width="2475" height="1223" alt="Technique Identification" src="https://github.com/user-attachments/assets/e6b013d9-9524-464b-b91a-71062b05aafe" />

**Mapping Techniques to Tactics**  
<img width="2476" height="1221" alt="Mapping Techniques" src="https://github.com/user-attachments/assets/b125f1fd-18be-406f-ade5-c28d9dd8c34d" />

**Cyber Kill Chain Correlation**  
<img width="2484" height="1269" alt="Kill Chain Correlation" src="https://github.com/user-attachments/assets/e0ade41f-efd9-442b-9e7a-0166a29206c1" />

**Detection Logic Notes**  
<img width="2459" height="1290" alt="Detection Rules" src="https://github.com/user-attachments/assets/66cddffa-b822-4289-ab39-5b5d9d7bea9a" />

**Final Framework Overview**  
<img width="2480" height="1161" alt="Framework Overview" src="https://github.com/user-attachments/assets/30a0accb-bb59-4beb-a6be-f4ac71e3ef43" />

---

## Summary

This module demonstrates the ability to:
- Correlate adversarial behaviours with the MITRE ATT&CK and Cyber Kill Chain frameworks.  
- Identify, map, and document techniques in a structured format suitable for SOC operations.  
- Translate theoretical frameworks into actionable detection and mitigation strategies used in real-world security operations.  
