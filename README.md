# FUTURE_CS_01
Vulnerability Assessment Report
Project Overview

This repository contains a vulnerability assessment conducted on a publicly accessible web application as part of the Cyber Security Internship Task.

The objective of this assessment was to identify common security weaknesses through passive analysis techniques and provide recommendations to improve the website's security posture.

Website Tested:
https://juice-shop.herokuapp.com

Scope of the Assessment
The assessment was conducted within strict ethical boundaries.

Allowed Activities:
-Passive vulnerability scanning
-Public page analysis
-HTTP header inspection
-Network exposure checks

Restricted Activities:
-Exploiting vulnerabilities
-Brute force attacks
-Denial-of-Service attacks
-Any activity that could harm the system

Tools Used
Security analysis was performed using the following tools:

-Nmap: network scanning and service detection
-OWASP ZAP: passive vulnerability scanning
-Browser Developer Tools: HTTP header inspection
-Canva: vulnerability report design

Key Findings

The following vulnerabilities were identified during the assessment.

| Vulnerability                             | Risk Level |
|-------------------------------------------|------------|
| Content Security Policy Header Not Set    |  Medium    |
| Cross-Domain Misconfiguration             |  Medium    |
| Timestamp Disclosure                      |    Low     |

These vulnerabilities are primarily configuration-related and can be mitigated by implementing proper security headers and improving server configuration.

Evidence

Screenshots and scan results supporting the findings are included in the evidence folder within this repository.

Evidence includes:
-Website homepage screenshot
-Nmap network scan results
-OWASP ZAP vulnerability scan alerts
-HTTP response header inspection

Conclusion

The assessment identified several configuration-related vulnerabilities that could potentially expose the application to security risks. Implementing recommended remediation steps such as security headers and stricter configuration policies would significantly improve the website's security posture.
