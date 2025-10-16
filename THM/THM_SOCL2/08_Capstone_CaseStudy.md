# Capstone Case Study — [Challenge Name]

**Source:** TryHackMe SOC Level 2 — Capstone

**Objective:** Full incident response case study combining hunting, analysis, containment, and lessons learned.

**Timeline / Key events:**
- T0: Initial SIEM alert triggered: repeated failed logins + suspicious network
- T1: Threat hunting uncovered C2 beacons
- T2: EDR shows persistence and lateral movement
- T3: Containment and remediation actions performed

**IOCs:** domain, hashes, IPs

**Outcome / Lessons learned:**
- Detection gaps: missing DNS monitoring
- Action items: add detection for encoded PowerShell & MFA policy review

**Screenshots:**  
- `Screenshots/capstone_timeline.png`
