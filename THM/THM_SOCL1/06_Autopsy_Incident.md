# DFIR – Autopsy & Incident Response

**Source:** TryHackMe SOC Level 1 – Module: DFIR  
**Room(s):** Windows Forensics 1 (52), Autopsy (55)

**Objective:** Investigate endpoints and incidents to identify compromise.

**Steps Performed:**
1. Loaded disk images into Autopsy.
2. Analyzed artifacts for suspicious files/processes.
3. Constructed incident timeline.

**Findings / IOCs:**
- Malicious executable: evil.exe
- Timeline: user download → execution → suspicious network activity

**Response / Mitigation:**
- Contain endpoint, preserve evidence.
- Remediate and update SOC alerts.

**Screenshots:**  
- `Screenshots/autopsy_artifact.png`  
- `Screenshots/incident_timeline.png`
