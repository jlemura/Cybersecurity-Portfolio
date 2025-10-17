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
<img width="595" height="740" alt="f3091f38f680b418f89cf79128d1933c" src="https://github.com/user-attachments/assets/76a2fff5-145f-443b-b14e-b394639ab3b2" />
<img width="1920" height="1020" alt="48b9656c4037d0537bf517d6084517a8" src="https://github.com/user-attachments/assets/c33c3fc1-036b-4cce-a1e8-4be901be5c59" />
<img width="1166" height="736" alt="6aa5e6825bb003dc803106d5f70e155c" src="https://github.com/user-attachments/assets/10048e88-b43a-44fe-a3a1-79aa357e4214" />
<img width="1202" height="714" alt="414dee2639b9456334c9580aacdc2be1" src="https://github.com/user-attachments/assets/a7e0e54e-14b5-42c0-8edd-f0fd4039dba9" />
<img width="1244" height="1357" alt="image" src="https://github.com/user-attachments/assets/499e00b9-99e8-4ada-9887-25882ad54833" />
