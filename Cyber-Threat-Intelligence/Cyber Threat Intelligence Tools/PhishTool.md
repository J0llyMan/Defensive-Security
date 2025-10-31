# 📨 PhishTool

**PhishTool** is a specialized tool for **email analysis and phishing investigation**, designed to help cybersecurity analysts detect, triage, and respond to phishing attacks efficiently.  
It combines built-in OSINT with automated analysis to provide detailed insights into email threats.

![PhishTool Dashboard (TryHackMe Screenshot)](screenshots/PTool1.png)

---

## 🧠 Overview

Phishing emails are a common attack vector, used by adversaries to:

- Deliver malware
- Harvest credentials
- Perform financial fraud or ransomware attacks

PhishTool elevates phishing awareness by **analyzing emails, uncovering IOCs, and providing forensic reporting**, enabling proactive containment and training exercises.

---

## 📊 Core Features

| Feature | Description |
|---------|-------------|
| **Email Analysis** | Retrieves metadata from emails to track actions, attachments, and URLs for triage |
| **Heuristic Intelligence** | Built-in OSINT helps understand TTPs used to evade security controls |
| **Classification & Reporting** | Classifies phishing emails and generates forensic reports for sharing and documentation |
| **Enterprise Features** | Manage user-reported phishing events, integrate email stacks with Microsoft 365 / Google Workspace, report findings to users |

---

## 🧪 Example Scenario (TryHackMe Exercise)

During the Room, I explored PhishTool’s capabilities by doing exploring its the Images and GIF files shown inside the rooms. I have not posted the resources due to its premium room status.

---


## 💡 Practical Usage & Findings

- Quickly identify **malicious links and attachments** in phishing emails  
- Understand the **routing and header details** to trace sender origin  
- Generate reports for forensic analysis or phishing awareness exercises  
- Useful for both community (free) and enterprise environments  

---

## 🧠 Reflection

PhishTool is particularly valuable because OSINT is already integrated, providing **actionable intelligence directly from the tool**.  
It complements traditional CLI-based analysis workflows, making it a versatile addition to an email analyst’s toolkit. In my own experience investigating phishing emails, I often prefer **command-line tools** like `olevba`, `cat`, `grep`, `md5sum`, combined with uploading files to malware analysis sites.
PhishTool’s built-in OSINT, however, makes it extremely useful for rapid investigations.

---

## 🧰 Tools / Platforms Used While Learning

- PhishTool (Community version)  
- TryHackMe lab environment for guided exercises  
- Command-line utilities: `olevba`, `cat`, `grep`, `md5sum`  
- Malware analysis platforms for additional context  
- Markdown & Screenshot documentation
