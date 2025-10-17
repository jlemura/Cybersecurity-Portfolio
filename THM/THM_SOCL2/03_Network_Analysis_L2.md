# 03_Network_Analysis_L2

**Source:** TryHackMe SOC Level 2 – Module: Network Traffic Analysis  
**Room:** Advanced Wireshark & TShark

**Objective:**  
Analyze network traffic to detect anomalies and potential threats using advanced packet inspection techniques.

---

## Methodology

1. Captured network traffic with Wireshark and TShark.  
2. Filtered traffic to highlight suspicious domains, protocols, or endpoints.  
3. Correlated network events with lab attack scenarios.  
4. Documented indicators for SOC response and mitigation.

---

## Key Findings / Indicators of Compromise (IOCs)

| Tool | Example IOC | Description |
|------|-------------|-------------|
| Wireshark | Suspicious HTTP POST to bad-domain.lab | Data exfiltration simulation |
| TShark | DNS queries for malicious domains | Identified C2 communication patterns |

---

## Response and Mitigation Recommendations

- Block malicious domains and isolate affected hosts.  
- Escalate incidents to SOC analyst for further investigation.  
- Monitor network traffic for repeated suspicious patterns.  
- Update firewall and IDS/IPS rules based on findings.

---

## Screenshots

`Screenshots/network_analysis_1.png`  
`Screenshots/network_analysis_2.png`

---

## Summary

Demonstrates ability to:

- Capture and analyze network traffic.  
- Detect and document anomalies or threats.  
- Integrate findings into SOC monitoring workflows.
