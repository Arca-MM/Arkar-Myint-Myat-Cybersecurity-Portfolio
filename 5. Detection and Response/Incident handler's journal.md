> # Incident Handler's Journal

> ### Entry: 001  
**Date:** Mar 26, 2025  

**Description:** Recording a security incident at a health care clinic.  

**Tool(s) used:** none  

**The 5 W's:** 
- An organization of unethical hackers caused the incident.  
- Ransomware security event.  
- Tuesday morning, approximately 9 AM.  
- The incident took place at a small U.S. health care clinic.  
- The attackers sent targeted phishing emails which contain malicious file attachment and it encrypt all the organization data once it is downloaded. Business operations shut down because employees were unable to access the files and software needed to do their job.  

**Additional notes**

To prevent similar ransomware incidents, the healthcare company could implement security awareness training for employees to identify phishing emails, deploy email filtering to block malicious attachments, and perform regular firewall maintenance.  It is generally not recommended to pay the ransom as it encourages further criminal activity and there is no guarantee that the attackers will provide a working decryption key or not leak the stolen data anyway. Instead, the focus should be on restoring from backups and improving security measures to prevent future attacks. 
 
---

> ### Entry: 002  
**Date:** Apr 06, 2025  

**Description:** Analyzing packets using packet capture software.  

**Tool(s) used:** Wireshark  

**The 5 W's:** none

**Additional notes**  

Using wireshark to analyze the components of  a packet capture file.

---

> ### Entry: 003  
**Date:** Apr 08, 2025  

**Description:** Recording a security incident at a financial company.  

**Tool(s) used:** virustotal.com  

**The 5 W's:**
- A malicious actor caused the incident.
- A malicious payload was executed on one of the employees’ computers.
- Time is 1.11 pm .
- The incident took place at financial service company.
- The employee received an email with a password encrypted spreadsheet file containing malicious payload. After opening the file with the password, multiple unauthorized exe files are created on the computer. 

**Additional notes**  

After getting the alert about the incident, hashing the spreadsheet file is processed and checked the information on the Virustotal website. Almost 60 vendors reported that file as malicious. Patterns and techniques have been inspected. After learning from this experience, the company should prepare to defend against this kind of threats by using the pyramid of pain scheme.

---

> ### Entry: 004  
**Date:** Apr 10, 2025 

**Description:** Using a playbook to response to a phishing incident at a financial service company.  

**Tool(s) used:** Phishing playbook 

**The 5 W's:** 
- Unknown attacket caused the incident.
- A suspicious file being downloaded on an employee computer.
- Wednesday, July 20, 2022 
- The incident took place at a financial service company.
- One of the employees have opened a malicious email and clicked a malicious attachment. Afterwards, the malicious file was downloaded and executed on the employee’s computer.  

**Additional notes**

After evaluating that the file is malicious, the status of the ticket is escalated and notified to the Level 2 SOC analyst.
 
---

> ### Entry: 005  
**Date:** Apr 11, 2025  

**Description:** Reviewing the final report of the recent incident at a retail company.  

**Tool(s) used:** none  

**The 5 W's:** 
- An attacker caused the incident.
- Over 50,000 customer PII were exposed.
- December 22,2022 3:13pm
- The incident took place at a retail company.
- The attacker performed a force browsing attack and access customer transaction data by modifying the order number included in the URL string of a purchase confirmation page. This vulnerability allowed the attacker to access customer purchase confirmation pages, exposing customer data, which the attacker then collected and exfiltrated.

**Additional notes**

Recommendations for future similar incidents are included in the final report.
 
---