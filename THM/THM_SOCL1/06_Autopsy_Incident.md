# DFIR – Autopsy & Incident Response

**Source:** TryHackMe SOC Level 1 – Module: DFIR  
**Rooms Completed:** Windows Forensics 1 (52), Autopsy (55)  

**Objective:**  
Investigate endpoint disk images and incidents to identify compromise and construct an incident timeline.

---

## Methodology

1. Loaded **disk images** into Autopsy for forensic analysis.  
2. Examined artifacts including executable files, user downloads, and system logs.  
3. Constructed a **timeline of events** from download to execution and subsequent suspicious network activity.  
4. Documented all IOCs and correlated with SOC monitoring procedures.

---

## Key Findings / Indicators of Compromise (IOCs)

| IOC Type | Value | Description |
|----------|-------|-------------|
| Malicious Executable | `evil.exe` | Identified as primary malware file executed by user. |
| Timeline | User download → Execution → Suspicious network activity | Event sequence detailing compromise progression. |

---

## Response and Mitigation

- Contain the affected endpoint to prevent lateral movement.  
- Preserve all forensic evidence for further analysis.  
- Remediate compromised hosts and reset credentials as required.  
- Update SOC alerts and procedures to detect similar future incidents.

---

## Screenshots

**Autopsy – Disk Image Overview**  
<img width="595" height="740" alt="Autopsy interface showing loaded disk image for forensic analysis" src="https://github.com/user-attachments/assets/76a2fff5-145f-443b-b14e-b394639ab3b2" />

**Artifact Analysis – Malicious File**  
<img width="1920" height="1020" alt="Autopsy highlighting malicious executable evil.exe within user downloads folder" src="https://github.com/user-attachments/assets/c33c3fc1-036b-4cce-a1e8-4be901be5c59" />

**File Properties – evil.exe**  
<img width="1166" height="736" alt="Properties view of malicious executable evil.exe showing hash and timestamps" src="https://github.com/user-attachments/assets/10048e88-b43a-44fe-a3a1-79aa357e4214" />

**File Metadata Analysis**  
<img width="1202" height="714" alt="Metadata of malicious executable including file creation and modification details" src="https://github.com/user-attachments/assets/a7e0e54e-14b5-42c0-8edd-f0fd4039dba9" />

**Event Timeline Overview**  
<img width="2550" height="1385" alt="Autopsy timeline displaying sequence of user download, file execution, and suspicious network activity" src="https://github.com/user-attachments/assets/125dc55a-ab28-415b-bc48-e92523a58b18" />

**Endpoint Activity Timeline**  
<img width="2556" height="1395" alt="Detailed timeline of endpoint activity highlighting suspicious events post-malware execution" src="https://github.com/user-attachments/assets/bcbb5a4c-4089-4c19-86e7-96a24c5f0c09" />

**User Download Activity**  
<img width="2528" height="1309" alt="Autopsy showing downloaded files including evil.exe with timestamps" src="https://github.com/user-attachments/assets/37884d49-258c-4260-8aae-81d5f270d46c" />

**Suspicious Network Connections**  
<img width="2550" height="1396" alt="Network connections initiated by malicious executable highlighted in Autopsy network analysis" src="https://github.com/user-attachments/assets/eb02b5c0-5a81-42cc-98eb-d2bac0cce804" />

**Execution Events Correlation**  
<img width="2552" height="1396" alt="Autopsy correlating malicious executable execution with endpoint events and user actions" src="https://github.com/user-attachments/assets/63f3a654-0a14-408f-ae32-5d51fd0fa6e8" />

**Timeline – Event Details**  
<img width="2556" height="1397" alt="Detailed timeline showing sequential event execution including malware run and system changes" src="https://github.com/user-attachments/assets/73958182-537a-48cc-87b9-6744d24b45d1" />

**File System Changes**  
<img width="2557" height="1379" alt="Autopsy showing file system modifications and artifact creation related to malware" src="https://github.com/user-attachments/assets/36c24d68-7080-4edb-ace3-0fdd62d099e4" />

**Final Incident Timeline**  
<img width="2555" height="1385" alt="Complete incident timeline summarizing user download, malware execution, and suspicious network activity" src="https://github.com/user-attachments/assets/2d48af89-11c4-46e9-8f27-fd4f28bd3110" />

**Incident Summary Report**  
<img width="2534" height="1339" alt="Autopsy final report summarizing all forensic findings and indicators of compromise" src="https://github.com/user-attachments/assets/efb587ab-b841-4443-bbbb-d4600af04bf2" />

---

## Summary

This module demonstrates the ability to:

- Conduct endpoint forensic analysis using Autopsy.  
- Identify malicious artifacts and construct incident timelines.  
- Extract actionable IOCs and correlate with SOC monitoring workflows.  
- Support incident response and containment procedures professionally.
