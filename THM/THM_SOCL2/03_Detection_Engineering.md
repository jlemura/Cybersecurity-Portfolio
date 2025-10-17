# 03_Detection_Engineering

**Source:** TryHackMe SOC Level 2 – Module: Detection Engineering  
**Room:** Sigma

**Objective:**  
Translate attacker TTPs into Sigma detection rules to enhance SOC detection capabilities.

---

## Methodology

1. Selected lab TTPs and wrote Sigma rules.  
2. Tested rules against lab datasets to validate true positives.  
3. Documented rules and potential false positives for SOC triage.

---

## Key Findings / Indicators of Compromise (IOCs)

| Tool | Example IOC | Description |
|------|-------------|-------------|
| Sigma Rule | Encoded PowerShell command detection | Flags potential malicious script execution |

---

## Response & Mitigation Recommendations

- Deploy validated Sigma rules in production SIEM/EDR.  
- Periodically review and tune rules to reduce false positives.  
- Integrate findings into SOC playbooks.

---

## Screenshots
Sigma Rule YAML example that is converted using Uncoder IO
<img width="2538" height="1288" alt="image" src="https://github.com/user-attachments/assets/644443d8-98cf-45be-afe9-d9f56a1d5330" />

Converted using Elastic
<img width="2548" height="1290" alt="image" src="https://github.com/user-attachments/assets/8eef332b-8984-4d66-9300-016d225c35bb" />

Creating custom sigma rule for task
<img width="2512" height="1210" alt="image" src="https://github.com/user-attachments/assets/7adff28c-aafc-41c4-8da3-66a5c3bd6aee" />


---

## Summary

Demonstrates ability to:

- Translate lab TTPs into detection rules.  
- Validate Sigma rules against datasets.  
- Enhance SOC detection capabilities and reduce alert fatigue.
