# Phishing Simulation Lab (GoPhish and MailHog)

## Overview
This lab demonstrates how I engineered a **controlled phishing simulation** using GoPhish and MailHog.  
The goal: test user behaviour against phishing emails, capture interactions safely, and map results to **ISO27001 controls**.

## Objectives
- Deploy a local phishing platform safely (GoPhish + MailHog).
- Send and track phishing emails end-to-end.
- Capture evidence of user clicks and credential submissions.
- Produce compliance-ready reporting.

## Tools Used
- **GoPhish**: phishing campaign engine  
- **MailHog**: secure SMTP capture  
- **Isolated Lab Environment**: no risk to production systems  

## Evidence of Work
1. `1, Terminal running.png`: GoPhish service running  
2. `2 gophish admin panel.png`: Admin dashboard  
3. `3.1 MailHog UI inbox.png`: Captured phishing emails  
4. `3.2 Gophish sending profile.png`: SMTP config  
5. `5.1 Email template.png`: Fake password reset email  
6. `5.2 Landing Page capture and redirect.png`: Credential capture page  
7. `6.1 Campaign dashboard.png`: Campaign success overview  
8. `6.2 MailHog Phising email.png`: Delivered phishing emails  
9. `7.1 Victim flow and credential submission.png`: Victim timeline showing clicks and submissions  
10. `8 Results.png`: **Full credential capture (email + password)**  

## Security Engineer Impact
- Designed a **phishing simulation workflow** from email delivery to credential submission.  
- Proved ability to **build offensive simulations** while keeping results safe.  
- Delivered **evidence reporting** for SOC teams and compliance audits.  

## ISO27001 Mapping
- **A.7.2.2 Awareness Training**: Employees tested against phishing.  
- **A.12.6.1 Vulnerability Management**: Simulated exploitation of human weakness.  
- **A.16.1.4 Event Assessment**: Logged all interactions.  
- **A.18.1.3 Protection of Records**: Controlled, isolated environment.  

---
