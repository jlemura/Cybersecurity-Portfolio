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

- `Screenshots/sigma_rule_example.png`

---

## Summary

Demonstrates ability to:

- Translate lab TTPs into detection rules.  
- Validate Sigma rules against datasets.  
- Enhance SOC detection capabilities and reduce alert fatigue.
