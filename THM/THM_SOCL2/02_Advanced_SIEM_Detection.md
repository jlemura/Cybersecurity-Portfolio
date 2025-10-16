# Advanced SIEM / Detection Engineering

**Source:** TryHackMe SOC Level 2 — Detection & Analytics

**Objective:** Build an analytic/correlation rule to detect multi-stage attacks and reduce false positives.

**Tools used:** Splunk/ELK, Sigma syntax (optional)

**Detection rule description:** [Short overview of logic]

**Example detection (pseudo):**
index=sysmon (EventCode=1 OR EventCode=3) | transaction host maxspan=5m | where count(process="powershell.exe") > 3 AND network_connections>5


**Testing & Results:**
- Ran detection on historical dataset; triggered on 3 known test incidents and 0 false positives in baseline.

**Response / Integration:**
- Created alert with severity mapping, auto-enrich IOC via threat intel, and linked to SOAR playbook.

**Screenshots:**  
- `Screenshots/detection_rule_example.png`
