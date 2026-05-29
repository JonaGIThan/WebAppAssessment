# WebAppAssessment
# Web Application Vulnerability Assessment

This project demonstrates a web application security assessment performed using OWASP ZAP in an authorized training environment against the intentionally vulnerable target `http://testphp.vulnweb.com`. The objective of the assessment was to identify common web application vulnerabilities, analyze security weaknesses, and understand the methodology used in Dynamic Application Security Testing (DAST).

The assessment identified multiple web security issues related to input validation, insecure configurations, and missing security protections. Findings included vulnerabilities such as Cross-Site Scripting (XSS), SQL Injection indicators, missing security headers, and insecure cookie configurations. The project also included analysis of vulnerability severity levels, potential impact, and realistic remediation strategies.

Recommendations focused on strengthening web application security through:

* Server-side input validation
* Parameterized SQL queries
* Secure HTTP headers
* HTTPS/TLS implementation
* Secure cookie settings (`HttpOnly`, `Secure`, and `SameSite`)
* Reducing inline JavaScript usage

This project highlights practical experience with vulnerability assessment, web application security concepts, risk analysis, and remediation planning using industry-standard security tools.
