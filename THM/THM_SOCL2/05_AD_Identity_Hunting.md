# Active Directory & Identity Hunting

**Source:** TryHackMe SOC Level 2 — AD / Identity module

**Objective:** Detect suspicious AD activity (credential dumping, privilege escalation, unconstrained delegation).

**Tools used:** BloodHound, PowerView, AD logs, Azure AD sign-in logs

**Steps performed:**
1. Ran AD enum and BloodHound query to identify abnormal trusts and high access.
2. Checked authentication logs for unusual time-of-day, legacy protocol usage, or unusual source IPs.

**Findings / IOCs:**
- Unusual Kerberos ticket requests from `HOST-03`
- Suspicious service account with delegated rights

**Response / Mitigation:**
- Remove delegated rights, require MFA for sensitive accounts, monitor for lateral movement.

**Screenshots:**  
- `Screenshots/ad_enum.png`  
- `Screenshots/bloodhound_query.png`
