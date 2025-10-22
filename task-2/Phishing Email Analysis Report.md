Phishing Email Analysis Report

Name: Satvic  
Task2 — Analyze a Phishing Email Sample  
Date: 22 October 2025  
Program: Cybersecurity Virtual Internship  

 1. Objective
The purpose of this task was to study how phishing emails are structured and identify warning signs such as spoofed addresses, fake links, and social engineering tactics used to deceive users.

2. Summary of the Email Sample
Subject: Security Alert — Verify Account Activity  
Sender: alerts@netflix-secure-support.com  
Return-Path: bounce@mail-fraud.ru  
Attachment: billing_statement.zip  
Displayed Link: https://www.netflix.com/login  
Actual Link: http://netflix-update-info.ru/login?refid=923abc  
Date: 22 Oct 2025  

3. Tools and Methods Used
| Tool / Method | Purpose |
|----------------|----------|
| MXToolbox Email Header Analyzer | Checked SPF and DKIM results |
| VirusTotal | Scanned URLs for malicious indicators |
| PhishTank | Compared sample domains with known phishing sites |
| Text editor (VS Code) | Examined .eml content safely |
| Manual link hover test | Verified mismatched URLs |

4. Indicators of Phishing

| Indicator | Observation | Explanation |
|------------|--------------|--------------|
| *Spoofed Sender Address* | Domain looks like Netflix but has extra words (netflix-secure-support.com) | Not the official domain; shows brand impersonation |
| *Header Authentication* | SPF failed, DKIM missing | Indicates forged sender details |
| *Fake Link* | Text shows Netflix link but redirects to .ru domain | Common phishing redirection trick |
| *Urgent Message Tone* | “Your account will be deactivated within 24 hours” | Creates fear to force immediate action |
| *Attachment* | ZIP file containing “billing_statement.zip” | Suspicious file type used to hide malware |
| *Grammar Errors* | Minor errors in body like “your acount has been suspend” | Typical of mass phishing templates |

 5. Findings
The email exhibits all key phishing characteristics — mismatched sender domains, suspicious links, attachment lure, and emotional manipulation through urgency.  
Both SPF and DKIM checks failed, confirming the message origin was forged.

6. Conclusion
This is a *phishing email* designed to steal user login credentials by mimicking Netflix.  
Users receiving such messages should avoid clicking any links, delete the message, and report it to the organization’s security team.

#7. Recommendations
1. Always hover over links before clicking.  
2. Verify the sender’s actual domain name.  
3. Avoid opening ZIP or executable attachments.  
4. Enable two-factor authentication for online accounts.  
5. Report any suspicious emails to IT or a trusted security contact.

8. Appendix
*Files:*  
- netflix_phish_sample.eml — sample phishing email  
- header_result.png — header analysis showing SPF/DKIM failure  
- phishing_mail_preview.png — sample email view  

 Author Information
Name: Satvic  
Program: B.Tech CSE (Cybersecurity)  
Task: Phishing Email Analysis  
Date: 22 October 2025