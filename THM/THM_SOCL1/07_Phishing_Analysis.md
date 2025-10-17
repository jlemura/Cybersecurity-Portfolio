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
<img width="775" height="525" alt="email-network-flow-4" src="https://github.com/user-attachments/assets/899d6178-c8f9-4924-943a-0471582866f4" />
<img width="948" height="622" alt="email-html-code" src="https://github.com/user-attachments/assets/da10cd97-f3dd-4b68-a659-cefee7969d0a" />
<img width="581" height="259" alt="email-with-attachment-2" src="https://github.com/user-attachments/assets/fbe3fb8b-abd5-4c12-afb4-4c12883cf9b5" />
