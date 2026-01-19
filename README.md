# DVWA Brute Force Attack – Burp Suite

## Overview
This project demonstrates a brute-force login attack against the Damn Vulnerable Web Application (DVWA) using Burp Suite Intruder.

## Tools Used
- Burp Suite
- DVWA
- Kali Linux

## Attack Methodology
- Intercepted login request using Burp Proxy
- Configured Intruder with username and password payloads
- Identified valid credentials based on response length and success message

## Evidence
![DVWA Brute Force](images/dvwa-bruteforce-burp-intruder.png)

**Result:** Successful authentication detected when the response returned  
`Welcome to the password protected area admin`

