# EDR / Endpoint Investigation

**Source:** TryHackMe SOC Level 2 — EDR & Endpoint module

**Objective:** Investigate suspicious process chain and determine persistence & lateral movement indicators.

**Tools used:** EDR console (process tree), Sysmon, Windows event logs

**Steps performed:**
1. Viewed process tree and identified suspicious parent-child relationships.
2. Exported file hashes, checked hashes against VirusTotal / sandbox.
3. Collected additional host telemetry for lateral movement evidence.

**Findings / IOCs:**
- Process tree screenshot: `Screenshots/edr_process_tree.png`
- Artifact: `C:\Windows\Temp\evil.dll` (hash: abc123...)

**Response / Mitigation:**
- Quarantine endpoint, collect forensic images, roll credentials, run AV sweep.

**Screenshots:**  
- `Screenshots/edr_process_tree.png`  
- `Screenshots/edr_artifact.png`
