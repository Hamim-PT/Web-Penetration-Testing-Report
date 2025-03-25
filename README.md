# Web Penetration Testing Report

## 📌 Project Overview
This repository contains the **Web Penetration Testing Report** conducted by **ShadowSec Solutions** for **Creative IT Institute** in **February 2025**. The assessment focused on **Cross-Site Scripting (XSS), Cross-Site Request Forgery (CSRF), and Cross-Site Requests.**

## 🔍 Objectives
- Identify security flaws related to **XSS, CSRF, and Cross-Site Requests**.
- Assess potential risks and their impact on user accounts and sensitive data.
- Exploit identified vulnerabilities to understand real-world implications.
- Provide actionable recommendations for mitigation.

## 🛠️ Tools & Methodologies
- **Tools Used:** Burp Suite, OWASP ZAP, Nessus
- **Testing Frameworks:** OWASP Testing Guide, PTES
- **Assessment Duration:** **10/01/2025 - 28/02/2025**

## 🖥️ Target Environment
- **Target:** Creative IT Institute's **BeeBox Web Application**
- **IP Address:** `192.168.1.108`

## 📊 Findings
### 1️⃣ **XSS (Cross-Site Scripting)**
- Vulnerability found in **bWAPP’s** input fields.
- Exploited using payload: 
  ```html
  <script>alert(document.cookie)</script>
  ```
- Result: Session hijacking was possible.

### 2️⃣ **CSRF (Cross-Site Request Forgery)**
- Bypassed CSRF protection at **Medium Security Level**.
- Used **Burp Suite** to capture and modify requests.
- Impact: Attackers could change user secrets without authentication.

## 🛡️ Recommendations
- Implement **input validation & sanitization**.
- Enforce **CSRF tokens** for request validation.
- Use **Content Security Policy (CSP)** to mitigate script injection.
- Implement **Multi-Factor Authentication (MFA)** for enhanced security.

## 📂 Repository Structure
```
📁 Web-Pentest-Report
 ├── PRO.pdf  # Full pentest report
 ├── README.md  # Project documentation
 ├── POCs/  # Exploits & proof of concept
 ├── Screenshots/  # Evidence of findings
 └── BurpSuiteLogs/  # Captured HTTP requests
```

## 📞 Contact
👤 **MD. Joynal Abedin Hamim**  
**Junior Penetration Tester | ShadowSec Solutions**  
📧 hamim.cybersec@gmail.com  
🌐 [LinkedIn](https://www.linkedin.com/in/hamim-pt/)  

## 📁 Full Report  
For the complete penetration testing report, access the PDF here:  
[📄 View Full Report](https://drive.google.com/file/d/1NWxHV0_80tFBG8XU3tpTEE6UVX7pZ4FT/view?usp=sharing)  

---
**Disclaimer:** This report is confidential and intended solely for Creative IT Institute. Unauthorized distribution is strictly prohibited. 🚨
