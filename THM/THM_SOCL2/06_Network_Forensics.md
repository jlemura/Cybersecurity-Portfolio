# Network Forensics & PCAP Analysis

**Source:** TryHackMe SOC Level 2 — Network Forensics

**Objective:** Analyse PCAPs and network logs to identify data exfiltration and C2 channels.

**Tools used:** Wireshark, Zeek/Suricata logs, netflow

**Steps performed:**
1. Loaded PCAP and filtered for suspicious IPs / protocols.
2. Extracted full HTTP POST payload revealing possible exfil.
3. Correlated with DNS logs to identify domain generation patterns.

**Findings / IOCs:**
- PCAP shows regular POSTs to `bad-domain.example.com` on port 8080.
- Netflow patterns indicate beaconing behaviour.

**Response / Mitigation:**
- Block C2, sinkhole domain, investigate hosts for data loss.

**Screenshots:**  
- `Screenshots/pcap_flow.png`  
- `Screenshots/wireshark_team.png`
