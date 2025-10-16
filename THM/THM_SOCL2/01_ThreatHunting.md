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
