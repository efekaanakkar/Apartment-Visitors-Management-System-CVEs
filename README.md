🛡️ Apartment Visitors Management System CVEs

This repository contains multiple security vulnerabilities discovered in Apartment Visitors Management System v1.1, including publicly assigned CVEs.

📌 CVE List
CVE ID	Vulnerability	Component	Impact
CVE-2026-39109	SQL Injection	Login (index.php)	Database Disclosure
CVE-2026-39110	SQL Injection	Forgot Password (contactno)	Data Extraction
CVE-2026-39111	SQL Injection	Forgot Password (email)	Sensitive Data Exposure
CVE-2026-39112	Stored XSS	Visitor Form (visname)	Session Hijacking / Privilege Abuse
🧠 Technical Summary

The identified vulnerabilities include multiple SQL Injection points and a Stored Cross-Site Scripting (XSS) flaw.

These issues allow attackers to:

Access sensitive database contents
Execute arbitrary JavaScript
Potentially compromise user sessions
⚙️ Affected Version
Apartment Visitors Management System v1.1
🔬 Proof of Concept

Detailed PoC and reproduction steps are provided in each CVE folder.

🛠️ Tools Used
Burp Suite
SQLmap
Manual Testing
🛡️ Mitigation
Use prepared statements (parameterized queries)
Implement proper input validation
Apply output encoding for user-controlled data
Follow secure coding practices
🔗 References
https://phpgurukul.com/apartment-visitors-management-system-using-php-and-mysql/
👤 Discoverer

Efe Kaan Akkar

⚠️ Disclaimer

This repository is for educational and security research purposes only. All testing was conducted in a controlled environment.
