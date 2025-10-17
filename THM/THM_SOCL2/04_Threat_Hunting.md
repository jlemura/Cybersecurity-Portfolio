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

- `Screenshots/threat_hunt_results.png`

---

## Summary

Demonstrates ability to:

- Develop hypotheses and proactively hunt for threats.  
- Identify compromised hosts or accounts.  
- Convert threat hunting insights into actionable SOC detections.
