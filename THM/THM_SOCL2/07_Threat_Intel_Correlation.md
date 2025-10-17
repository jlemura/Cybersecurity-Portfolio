# 07_Threat_Intel_Correlation

**Source:** TryHackMe SOC Level 2 – Module: Threat Intelligence Correlation  
**Room:** MISP Advanced & Open Threat Exchange

**Objective:**  
Correlate multiple threat intelligence sources to identify patterns and enhance SOC detection.

---

## Methodology

1. Imported multiple threat feeds into MISP.  
2. Cross-referenced IOCs with lab events.  
3. Validated intelligence against known threat datasets.  
4. Documented correlations for SOC alert tuning.

---

## Key Findings / Indicators of Compromise (IOCs)

| Tool | Example IOC | Description |
|------|-------------|-------------|
| MISP | IP 192.168.1.50 | Linked to malicious lab scenario |
| OTX | Domain bad-lab-domain.com | Part of simulated attack feed |

---

## Response and Mitigation Recommendations

- Integrate correlated IOCs into SOC monitoring.  
- Update detection rules based on threat feeds.  
- Document correlations for future incidents.  
- Monitor recurring IOC patterns in real-time.

---

## Screenshots

`Screenshots/threatintel_1.png`  
`Screenshots/threatintel_2.png`

---

## Summary

Demonstrates ability to:

- Correlate threat intelligence from multiple sources.  
- Identify and validate IOC patterns.  
- Feed intelligence into SOC detection and response.
