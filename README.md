# DVWA XSS Lab

## 🎯 Objective
To identify and exploit Cross-Site Scripting (XSS) vulnerability using DVWA.

## 🛠 Tools Used
- DVWA (Damn Vulnerable Web Application)
- Burp Suite
- Browser

## 🧪 Steps Performed
1. Opened DVWA XSS module
2. Intercepted request using Burp Suite
3. Injected payload in input field

## 💣 Payload Used
<script>alert('XSS')</script>

## ✅ Result
- JavaScript executed successfully
- Alert popup confirmed vulnerability

## ⚠ Impact
- Session hijacking
- Cookie theft
- Malicious redirection

## 🔐 Prevention
- Input validation
- Output encoding
- Use of secure frameworks
