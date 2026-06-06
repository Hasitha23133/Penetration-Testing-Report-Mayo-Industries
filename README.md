# Penetration-Testing-Report-Mayo-Industries
Penetration Testing Assessment of Mayo Industries using Red Team, Blue Team, and Purple Team methodologies for the SLIIT Applied Information Assurance Module.
# 🔐 Penetration Testing Report for Mayo Industries

![License](https://img.shields.io/badge/License-MIT-green.svg)
![Status](https://img.shields.io/badge/Status-Completed-success)
![Security](https://img.shields.io/badge/Security-Penetration%20Testing-blue)

## 📌 Project Overview

This project was completed for the **Applied Information Assurance (AIA)** module at the Sri Lanka Institute of Information Technology (SLIIT).

The assessment evaluates the security posture of a simulated **Mayo Industries** environment through a structured penetration testing exercise using **Red Team**, **Blue Team**, and **Purple Team** methodologies.

The assessment was conducted in a controlled laboratory environment using **Kali Linux** and the **Damn Vulnerable Web Application (DVWA)**.

---

## 🎯 Objectives

* Perform network reconnaissance and host discovery.
* Identify exposed services and potential attack vectors.
* Assess application-level vulnerabilities.
* Evaluate defensive capabilities of the environment.
* Analyze business impact of discovered vulnerabilities.
* Recommend mitigation and remediation strategies.

---

## 🛠️ Tools & Environment

### Attacker Environment

* Kali Linux

### Victim Environment

* Kali Linux
* Apache Web Server
* MariaDB
* DVWA (Damn Vulnerable Web Application)

### Security Testing Tools

* Nmap
* Ping (ICMP Testing)
* Web Browser
* DVWA Security Modules

---

## 🔴 Red Team Assessment

The offensive assessment included:

* Host Discovery
* Network Reconnaissance
* Service Enumeration
* Web Application Testing
* Authentication Testing
* SQL Injection Testing
* Cross-Site Scripting (XSS) Testing

### Identified Services

| Port | Service |
| ---- | ------- |
| 22   | SSH     |
| 80   | HTTP    |

---

## 🔵 Blue Team Assessment

The defensive analysis focused on:

* Service Exposure
* Monitoring Capabilities
* Logging Mechanisms
* Authentication Controls
* Attack Detection Readiness

Key findings showed limited defensive monitoring and insufficient protection against common attack techniques.

---

## 🟣 Purple Team Assessment

The Purple Team compared offensive findings against defensive capabilities and provided recommendations for:

* Improved Authentication Controls
* Service Hardening
* Secure Coding Practices
* Enhanced Monitoring & Alerting
* Continuous Security Validation

---

## 🚨 Key Vulnerabilities Identified

### 1. Exposed SSH Service

**Severity:** Low

### 2. Exposed HTTP Service

**Severity:** Low

### 3. Weak Authentication Controls

**Severity:** Medium

### 4. SQL Injection Vulnerability

**Severity:** High

### 5. Reflected Cross-Site Scripting (XSS)

**Severity:** Medium

---

## 🛡️ Recommendations

* Restrict SSH Access
* Implement Account Lockout Policies
* Apply Rate Limiting
* Use Parameterized SQL Queries
* Perform Input Validation
* Implement Output Encoding
* Improve Logging and Monitoring
* Conduct Regular Security Assessments

---

## 📸 Screenshots

Include screenshots from:

* Attacker Machine Configuration
* Victim Machine Configuration
* ICMP Connectivity Test
* Nmap Scan Results
* DVWA Login Page
* SQL Injection Testing
* XSS Testing
* Access Log Evidence

---

## 📄 Project Report

[View Full Report](./IT23659230%20AIA%20Assignment.pdf)

---

## 👨‍🎓 Author

**Lakshan W.M.H.C**

**Registration Number:** IT23659230

Sri Lanka Institute of Information Technology (SLIIT)

---

## 📄 License

This project is licensed under the MIT License.
