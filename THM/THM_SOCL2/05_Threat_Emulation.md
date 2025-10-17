# 05_Threat_Emulation

##**COMING SOON**

**Source:** TryHackMe SOC Level 2 – Module: Threat Emulation  
**Room:** Atomic Red Team

**Objective:**  
Emulate attacker techniques to validate SOC detection coverage and identify gaps.

---

## Methodology

1. Selected relevant Atomic Red Team tests.  
2. Executed safe emulation runs in lab.  
3. Recorded which telemetry or detections triggered.  
4. Documented gaps for SOC improvement.

---

## Key Findings / Indicators of Compromise (IOCs)

| Emulation | Detected? | Notes |
|-----------|-----------|-------|
| Credential Dump | Partial | Some EDR detections triggered; SIEM correlation missing |

---

## Response & Mitigation Recommendations

- Tune detection rules based on emulation gaps.  
- Add telemetry sources to cover blind spots.  
- Document emulation evidence for SOC.

---

## Screenshots

- `Screenshots/atomic_red_team_run.png`

---

## Summary

Demonstrates ability to:

- Safely emulate attacker techniques.  
- Identify SOC detection gaps and blind spots.  
- Improve SOC detection coverage based on emulation results.
