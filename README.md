# Full Web Application Penetration Testing

## 📌 Project Overview

This project presents a web application penetration testing assessment using the **Damn Vulnerable Web Application (DVWA)** in a controlled laboratory environment.

The main purpose of this project is to identify, test, and analyze common web application vulnerabilities and understand their security impact and mitigation techniques.

The testing environment was configured using **Kali Linux**, with DVWA running at a low security level. The project was performed for educational and ethical hacking purposes only.

## 🎯 Objectives

* To understand the fundamentals of web application penetration testing.
* To identify common security vulnerabilities in DVWA.
* To perform ethical penetration testing in a controlled environment.
* To analyze the impact of different web attacks.
* To understand appropriate security mitigation techniques.
* To gain practical experience with penetration testing tools.

## 🛠️ Tools & Technologies

* Kali Linux
* DVWA (Damn Vulnerable Web Application)
* Burp Suite Community Edition
* Mozilla Firefox
* Apache2
* MySQL/MariaDB
* PHP

## 🔍 Vulnerabilities Tested

The project covers the following ten web application vulnerabilities:

1. SQL Injection (SQLi)
2. Blind SQL Injection
3. Brute Force Attack
4. Command Injection
5. Cross-Site Request Forgery (CSRF)
6. File Inclusion
7. File Upload Vulnerability
8. DOM-Based Cross-Site Scripting (DOM XSS)
9. Reflected Cross-Site Scripting (Reflected XSS)
10. Stored Cross-Site Scripting (Stored XSS)

## 🔬 Methodology

The penetration testing process followed these major phases:

1. **Planning and Environment Setup**
2. **Information Gathering**
3. **Vulnerability Assessment**
4. **Exploitation**
5. **Documentation and Analysis**

All testing was conducted within the controlled DVWA laboratory environment.

## 📊 Results

The assessment successfully demonstrated the presence of multiple vulnerabilities in the DVWA application at the Low Security Level.

The results showed security weaknesses related to:

* Input validation
* Authentication controls
* Database query handling
* File handling
* Output encoding
* Session and request security
* Client-side security

Each vulnerability was analyzed along with its security impact and recommended mitigation techniques.

## 📁 Project Structure

```text
Full-Web-Application-Penetration-Testing/
│
├── README.md
├── Project-Report.pdf
│
└── screenshots/
    ├── dvwa-setup.png
    ├── sql-injection.png
    ├── blind-sql-injection.png
    ├── brute-force.png
    ├── command-injection.png
    ├── csrf.png
    ├── file-inclusion.png
    ├── file-upload.png
    ├── dom-xss.png
    ├── reflected-xss.png
    └── stored-xss.png
```

## 📄 Project Report

The complete project report is included in this repository as:

**Project-Report.pdf**

The report contains the methodology, testing procedures, screenshots, results, security impacts, and mitigation techniques.

## ⚠️ Ethical Use

This project was performed strictly for educational purposes in a controlled laboratory environment using DVWA, an intentionally vulnerable web application.

The techniques demonstrated in this project should only be used on systems where you have explicit permission to perform security testing.

## 👩‍💻 Author

**Sabrina Afroz Nitu**
ID: **C223241**
Department of Computer Science and Engineering
International Islamic University Chittagong

## 📚 Course Information

**Course:** Computer Security Lab
**Course Code:** CSE-4744
