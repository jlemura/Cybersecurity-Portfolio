# Phishing Analysis

**Source:** TryHackMe SOC Level 1 – Module: Phishing  
**Room(s):** Phishing Analysis Fundamentals (66), Phishing Emails in Action (67)

**Objective:** Detect and analyze phishing emails.

**Steps Performed:**
1. Reviewed email headers for spoofing signs.
2. Analyzed malicious URLs and attachments.
3. Recorded indicators in lab.

**Findings / IOCs:**
- Sender: spoofed@badsender.com
- Malicious URL: http://malicious.example
- Attachment hash: abcd1234

**Response / Mitigation:**
- Quarantine email, block sender, notify users.

**Screenshots:**  
- `Screenshots/phishing_email.png`  
- `Screenshots/malicious_url.png`
