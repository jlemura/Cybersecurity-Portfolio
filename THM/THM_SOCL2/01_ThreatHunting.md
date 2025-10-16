# Threat Hunting — [Room / Lab Name]

**Source:** TryHackMe SOC Level 2 — Threat Hunting module  
**Objective:** Proactively hunt for anomalous behaviour across endpoint, network and log sources.

**Tools used:** Splunk/ELK, Sysmon, EDR, network logs

**Hunt hypothesis:** [e.g., "Unusual outbound HTTP POSTs from workstations may indicate C2 exfiltration."]

**Steps performed:**
1. Formed hypothesis and created search across index=windows, index=sysmon, index=network.
2. Ran query (see below) to identify hosts showing > n connections to rare hostnames.
3. Investigated top hosts, inspected process trees, correlated with EDR telemetry.

**Hunt query (example):**
index=network dest_host!=internal.example.com | stats count by src_ip,dest_host | where count > 20


**Findings / IOCs:**
- Host: HOST-02 — repeated POSTs to `bad-domain.example.com`
- Process: `powershell.exe` launching `rundll32.exe` with suspicious arguments

**Response / Mitigation:**
- Isolated HOST-02, pulled memory image, blocked domain at proxy, added detection to SIEM.

**MITRE mapping:** T1071 (Application Layer Protocol), T1059 (Command and Scripting Interpreter)

**Screenshots:**  
- `Screenshots/threat_hunt_query.png`  
- `Screenshots/threat_hunt_results.png`
