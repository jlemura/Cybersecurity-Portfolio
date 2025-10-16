# SOAR / Automation & Playbooks

**Source:** TryHackMe SOC Level 2 — SOAR / Automation

**Objective:** Build or review a playbook that automates containment and enrichment.

**Tools used:** Cortex XSOAR / Demisto / Phantom (or pseudocode)

**Playbook steps (example):**
1. Alert enrichment (resolve IP/domain, VT lookup)
2. Decision: if severity >= high -> isolate host, block IOC on firewall
3. Create incident ticket, notify stakeholders

**Testing results:** Playbook executed on sample alert and completed containment steps automatically.

**Screenshots:**  
- `Screenshots/soar_playbook.png`
