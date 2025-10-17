# 04_Threat_Hunting

**Source:** TryHackMe SOC Level 2 – Module: Threat Hunting  
**Room:** Hunt Me I: Payment Collectors

**Objective:**  
Perform proactive threat hunts to detect latent compromise and identify attacker footholds.

---

## Methodology

1. Developed hypotheses based on lab TTPs.  
2. Executed hunts in logs and endpoints to identify suspicious patterns.  
3. Pivoted on findings to uncover impacted hosts or accounts.

---

## Key Findings / Indicators of Compromise (IOCs)

| Technique | Example IOC | Description |
|-----------|-------------|-------------|
| Hunt Query | Suspicious login patterns across multiple hosts | Potential attacker foothold |

---

## Response & Mitigation Recommendations

- Convert validated hunt queries to detections.  
- Contain impacted hosts.  
- Schedule recurring hunts for high-risk TTPs.

---

## Screenshots

The following shows example queries on using elastic to answer practice scenarios and questions in the lab.
<img width="2434" height="1251" alt="image" src="https://github.com/user-attachments/assets/1b455b2c-9a7f-4157-a537-5ba59b8b6f84" />
<img width="1765" height="1175" alt="image" src="https://github.com/user-attachments/assets/d0fbf52d-430e-47f2-9d4b-38045d879d2a" />
<img width="2539" height="1257" alt="image" src="https://github.com/user-attachments/assets/5210eee6-856b-42d5-bff7-eabc884a7b38" />
<img width="2534" height="1236" alt="image" src="https://github.com/user-attachments/assets/6ff834fc-9e9a-476b-9d84-af4632eb1af7" />
<img width="2540" height="1259" alt="image" src="https://github.com/user-attachments/assets/3ff4c2e8-b7cc-4a44-bb16-d640761e164e" />
I determined that this was the directory due to the Robocopy command above. Which also gives the name of the file extracted.
<img width="2533" height="1246" alt="image" src="https://github.com/user-attachments/assets/bb16c321-5a5c-4870-aac1-f17781c8e3bc" />

<img width="2546" height="1249" alt="image" src="https://github.com/user-attachments/assets/192ae7a3-37b3-446a-b34c-79b5538105d5" />
Using CberChef to convert the text to the rooms flag
<img width="2547" height="1261" alt="image" src="https://github.com/user-attachments/assets/1e8a78e6-c41d-4ad0-8ffc-f2d625be4124" />



---

## Summary

Demonstrates ability to:

- Develop hypotheses and proactively hunt for threats.  
- Identify compromised hosts or accounts.  
- Convert threat hunting insights into actionable SOC detections.
