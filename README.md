# Elevate-Labs-Task-3
🔍 Vulnerability Scan using Nessus Essentials
📌 Overview
This repository contains details of a basic vulnerability assessment performed on a local machine using Nessus Essentials, as part of a Cyber Security Internship Task. The goal was to identify security vulnerabilities and explore their severity and recommended fixes.

🛠️ Tools Used
Nessus Essentials – Free vulnerability scanner by Tenable

Operating System – Local PC

Target IP – 192.168.109.25

✅ Steps Performed
Installed Nessus Essentials and launched it via browser.

Configured a new scan:

Type: Basic Network Scan

Target: localhost / 192.168.109.25

Executed a full scan (~30–60 mins).

Analyzed the vulnerability report generated.

📋 Scan Summary
Date of Scan: 26 June 2025

Total Vulnerabilities Found: 59

Critical: 1

High: 2

Medium: 5

Info/Low: 51

⚠️ Critical & High Vulnerabilities
1. Oracle Database Unsupported Version Detection
Severity: Critical (CVSS 10.0)

Plugin ID: 55786

Fix: Upgrade Oracle DB to a supported version.

Oracle Upgrade Guide

2. Splunk Enterprise - Multiple Version Vulnerabilities
Severity: High (CVSS 8.0)

Plugin ID: 233660

Fix: Update to Splunk 9.1.8 or later.

Splunk Update

3. Oracle TNS Listener Remote Poisoning
Severity: High (CVSS 7.3)

Plugin ID: 69552

Fix: Apply patches and configure VALIDNODE_CHECKING in sqlnet.ora.

Tenable Plugin Info

ℹ️ Informational & Low Severity Issues
Service/software version detections

SSL/TLS warnings

HTTP header disclosures

NetBIOS/SMB banners

Oracle & Splunk presence

System fingerprinting

These are not critical, but useful during attacker reconnaissance.
