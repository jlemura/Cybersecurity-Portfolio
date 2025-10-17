# 06_DFIR_Analysis

**Source:** TryHackMe SOC Level 2 – Module: Digital Forensics & Incident Response (DFIR)  
**Room:** Autopsy Advanced

**Objective:**  
Investigate endpoints and incidents to identify compromise and construct a timeline for SOC reporting.

---

## Methodology

1. Loaded disk images into Autopsy.  
2. Analyzed artifacts (files, processes, registry) for suspicious activity.  
3. Constructed incident timeline mapping download, execution, and network activity.  
4. Documented findings for SOC incident management.

---

## Key Findings / Indicators of Compromise (IOCs)

| Tool | Example IOC | Description |
|------|-------------|-------------|
| Autopsy | evil.exe | Malicious executable found on disk image |
| Timeline | Download → Execution → C2 | Sequence of lab attack events |

---

## Response and Mitigation Recommendations

- Contain and isolate compromised endpoint.  
- Preserve forensic evidence for analysis.  
- Remediate affected systems and update SOC alerts.  
- Feed timeline and artifacts into incident response workflow.

---

## Screenshots

`Screenshots/dfir_autopsy_1.png`  
`Screenshots/dfir_autopsy_2.png`

---

## Summary

Demonstrates ability to:

- Analyze endpoint artifacts.  
- Construct incident timelines.  
- Feed findings into SOC incident response.
