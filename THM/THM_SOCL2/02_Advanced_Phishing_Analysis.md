# 02_Advanced_Phishing_Analysis

**Source:** TryHackMe SOC Level 2 – Module: Advanced Phishing Analysis  
**Room:** Phishing Investigations

**Objective:**  
Deep-dive into phishing campaigns and attacks, analyzing headers, URLs, and attachments to identify indicators of compromise.

---

## Methodology

1. Examined phishing emails for spoofed headers and sender anomalies.  
2. Analyzed malicious URLs and attachments for IOC extraction.  
3. Cross-referenced lab IOCs against threat feeds.  
4. Documented incidents and recommended SOC actions.

---

## Key Findings / Indicators of Compromise (IOCs)

| Tool | Example IOC | Description |
|------|-------------|-------------|
| Email Headers | spoofed@phishingsite.com | Identified as malicious sender |
| URL | http://malicious-link.lab | Phishing payload link |
| Attachment | hash: 1234abcd | Malicious attachment detected |

---

## Response and Mitigation Recommendations

- Quarantine emails and block senders.  
- Update SOC phishing detection rules.  
- Educate users on phishing tactics.  
- Record IOCs for SOC intelligence feeds.

---

## Screenshots



---

## Summary

Demonstrates ability to:

- Identify phishing campaigns and IOC extraction.  
- Analyze headers, links, and attachments.  
- Integrate findings into SOC incident response.
