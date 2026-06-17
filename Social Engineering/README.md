
# Social Engineering

## Overview

This lab explores the fundamentals of **Social Engineering** in a controlled cybersecurity environment. The exercises demonstrate how attackers manipulate human behavior to obtain sensitive information and how defenders can detect and prevent such attacks.

The lab covers:

- Credential Harvesting using Social-Engineer Toolkit (SET)
- Phishing Detection using Netcraft Browser Extension
- AI-Generated Phishing Awareness using ChatGPT/Qwen

---

## Objectives

- Understand how credential harvesting attacks work.
- Learn to identify phishing websites and suspicious domains.
- Explore the role of AI in generating convincing phishing content.
- Recognize common social engineering tactics.
- Apply defensive measures against phishing and impersonation attacks.

---

## Lab Environment

| Role | Platform | IP Address |
|--------|----------|------------|
| Attacker | Kali Linux | 20.20.11.32 |
| Target | Windows 10 | 20.20.11.42 |
| AI Platform | ChatGPT / Qwen | Web-Based |

---

## Tools Used

| Tool | Purpose |
|--------|---------|
| SET (Social-Engineer Toolkit) | Credential harvesting demonstration |
| Netcraft Extension | Phishing detection and analysis |
| ChatGPT / Qwen | AI-generated phishing examples |
| Python HTTP Server | Alternative payload hosting |
| xfreerdp | Remote desktop access |

---

## Tasks Performed

### Task 1: Credential Harvesting with SET

Demonstrated how attackers can clone websites and capture credentials entered by unsuspecting users.

**Concepts Covered:**

- Website cloning
- Fake login portals
- Credential collection
- User deception techniques

**Learning Outcome:**

Users should always verify website authenticity before entering credentials.

---

### Task 2: Phishing Detection with Netcraft

Used the Netcraft Browser Extension to analyze websites and identify phishing indicators.

**Concepts Covered:**

- Domain reputation
- Website age verification
- Hosting provider analysis
- Phishing detection

**Learning Outcome:**

Browser security tools can help identify suspicious websites before sensitive information is disclosed.

---

### Task 3: AI-Assisted Phishing Awareness

Explored how AI can generate realistic phishing emails and impersonation attempts.

**Scenarios Demonstrated:**

- Fake security alerts
- IT administrator requests
- Emergency financial scams
- Writing-style impersonation

**Learning Outcome:**

AI significantly increases the realism and effectiveness of phishing campaigns, making user awareness more important than ever.

---

## Social Engineering Techniques Demonstrated

| Technique | Description |
|------------|-------------|
| Urgency | Pressuring victims to act immediately |
| Fear | Triggering concern about account security |
| Authority | Impersonating trusted personnel |
| Sympathy | Exploiting emotions and empathy |
| Impersonation | Mimicking a known individual's communication style |

---

## Key Findings

- Credential harvesting remains one of the most effective social engineering techniques.
- Phishing sites can often be detected using reputation and domain analysis tools.
- AI can rapidly generate highly convincing phishing content.
- Human awareness remains one of the strongest defenses against social engineering attacks.

---

## Defensive Recommendations

- Verify website URLs before entering credentials.
- Enable Multi-Factor Authentication (MFA).
- Use password managers.
- Verify urgent requests through trusted channels.
- Be cautious of unexpected emails and attachments.
- Use browser security extensions such as Netcraft.
- Report suspicious communications immediately.

---

## Skills Gained

- Social Engineering Fundamentals
- Credential Harvesting Analysis
- Phishing Detection Techniques
- Security Awareness Assessment
- AI-Generated Threat Analysis
- Cybersecurity Defensive Practices

---

## Conclusion

This lab demonstrates that social engineering attacks primarily target human behavior rather than technical vulnerabilities. Understanding attacker tactics and implementing strong security awareness practices are essential for defending against credential theft, phishing campaigns, and impersonation attacks.

---

## Disclaimer

This project is intended solely for **educational, ethical hacking, and cybersecurity awareness purposes**.

All activities were performed in a controlled lab environment. Do not use these techniques against systems, networks, or individuals without proper authorization.

---

**Author:** KAIF Tarasgar  
**Topic:** Social Engineering  
**Focus Areas:** Credential Harvesting, Phishing Detection, AI Phishing Awareness
