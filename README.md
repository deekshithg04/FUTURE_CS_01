# 🔐 Vulnerability Assessment Report  
### Cyber Security Task 1 (2026) – Future Interns

---

## 📄 Quick Access

👉 **View Full Report:**  
[Open Vulnerability Report](./VulnerabilityReport.pdf)

---

## 📌 Overview

This repository contains a **Vulnerability Assessment Report** conducted as part of **Cyber Security Task 1 by Future Interns**.

The objective of this task was to analyze a live website using **passive, non-intrusive techniques**, identify security weaknesses, and present findings in a **clear, business-friendly format**.

This assessment strictly follows ethical guidelines and does **not involve exploitation or active attacks**.

---

## 🎯 Target Website

https://prasadtechintelugu.com/

---

## ⚠️ Scope & Ethics

This assessment follows a **read-only (passive) approach**.

### ✅ Allowed
- Public-facing pages analysis  
- HTTP header inspection  
- Cookie analysis  
- Port scanning (non-intrusive)  
- Configuration review  

### ❌ Not Allowed
- Exploitation of vulnerabilities  
- Login bypass or authentication testing  
- Brute force attacks  
- Denial-of-Service (DoS)  
- Any activity that may harm the website  

This project demonstrates **security auditing, not hacking**.

---

## 🛠️ Tools Used

- Nmap – Port scanning & service detection  
- Browser Developer Tools – Header & cookie analysis  
- Canva – Report design  

---

## 🔍 Methodology

The assessment was conducted using passive techniques:

- Nmap scan to identify open ports and services  
- Browser DevTools to inspect headers and cookies  
- Manual observation of public endpoints  

No intrusive testing or exploitation was performed.

---

## 🚨 Key Findings Summary

| Risk Level | Count |
|-----------|------|
| High Risk | 2 |
| Medium Risk | 4 |
| Low Risk | 4 |
| Low–Medium | 1 |

---

## 📋 Major Vulnerabilities Identified

### 🔴 High Risk
- FTP service exposed on port 21  
- MySQL database exposed on port 3306  

### 🟠 Medium Risk
- Multiple exposed services  
- Weak Content Security Policy  
- Missing security headers  
- Insecure cookie configuration  

### 🟡 Low–Medium Risk
- WordPress REST API exposure  

### 🟢 Low Risk
- Server information disclosure  
- PHP version disclosure  
- Sitemap exposure  
- HTTP service enabled  

---

## 📄 Report Preview

[![Vulnerability Report Preview](preview.png)](./VulnerabilityReport.pdf)

📥 Click the image above to view the full report

---

## 📸 Evidence

### Nmap Scan
![Nmap Scan](nmap_scan.png)

### Header Analysis
![Header Analysis](headers_analysis.png)

---

## 📂 Repository Contents

- VulnerabilityReport.pdf  
- preview.png  
- nmap_scan.png  
- headers_analysis.png  
- README.md  

---

## 💡 Learning Outcome

- Learned how to perform ethical vulnerability assessment  
- Identified real-world security weaknesses  
- Practiced risk classification and reporting  
- Developed a security consultant mindset  

---

## 🌟 About the Task

Cyber Security Task 1 (2026)  
By Future Interns  

https://www.linkedin.com/company/future-interns

---

## 👨‍💻 Author

Deekshith G  

---

## ⚠️ Disclaimer

This project is for educational purposes only.  
No exploitation or harmful activity was performed.

---
