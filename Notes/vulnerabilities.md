# 🔐 Cybersecurity Notes – Internship (Redynox)

## 📌 Overview
This document contains my learning notes and practical understanding of common web application vulnerabilities explored during my cybersecurity internship.

---

# 🛑 1. SQL Injection (SQLi)

## 🔍 What is it?
SQL Injection is a vulnerability where attackers manipulate database queries by injecting malicious SQL code into input fields.

## ⚙️ How it Works
- Application takes user input
- Input is directly used in SQL query
- No validation → attacker controls query

## 🧪 Example Payload
' OR '1'='1

## 🎯 Impact
- Bypass login authentication  
- Access sensitive data  
- Modify or delete database  

## 🛡️ Prevention
- Use prepared statements  
- Input validation  
- Parameterized queries  

---

# ⚠️ 2. Cross-Site Scripting (XSS)

## 🔍 What is it?
XSS allows attackers to inject malicious JavaScript into web pages.

## ⚙️ How it Works
- User input is not sanitized  
- Script gets executed in browser  

## 🧪 Example Payload
<script>alert("XSS")</script>

## 🎯 Impact
- Steal cookies  
- Session hijacking  
- Redirect users  

## 🛡️ Prevention
- Input sanitization  
- Output encoding  
- Use secure headers  

---

# 🔁 3. Cross-Site Request Forgery (CSRF)

## 🔍 What is it?
CSRF tricks users into performing unwanted actions on a web application.

## ⚙️ How it Works
- User is authenticated  
- Attacker sends malicious request  
- Action executed without consent  

## 🎯 Impact
- Unauthorized transactions  
- Account changes  

## 🛡️ Prevention
- CSRF tokens  
- SameSite cookies  
- User verification  

---

# 🛠️ Tools Used

## 🔧 Wireshark
- Network traffic analysis  
- Packet inspection  

## 🔧 OWASP ZAP
- Vulnerability scanning  
- Security testing  

## 🔧 WebGoat
- Practice vulnerable application  
- Hands-on learning  

---

# 🚀 Key Takeaways

- Understanding vulnerabilities is more important than tools  
- Practical testing improves learning  
- Security requires proper validation and awareness  

---

📌 This document represents my practical learning and understanding of cybersecurity fundamentals.
