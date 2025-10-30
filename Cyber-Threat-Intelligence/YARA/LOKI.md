# 🧩 LOKI 

**LOKI** is a lightweight, open-source tool designed for **scanning local systems for malware, suspicious indicators, and IOCs (Indicators of Compromise)**. It’s a go-to tool for quick and effective threat hunting on endpoints, perfect for blue teamers and incident responders.  

---

## 🧠 Overview

LOKI allows you to scan your system for:

- Malicious files and processes  
- Indicators such as suspicious registry entries, hidden files, or unusual scripts  
- IOC matches against publicly shared malware signatures  
- Suspicious behaviors that could indicate a compromise  

What I found particularly exciting was how **LOKI’s detection capabilities could be augmented with custom YARA rules**. By writing my own YARA rules, I could create tailored signatures for specific malware families or suspicious patterns I wanted to monitor on my endpoints.

---

## 📊 User Experience

When I ran LOKI for the first time, it immediately generated a **structured report** (Check CTFs & Projects for further details). The report included:

- A list of suspicious files with explanations  
- Indicators flagged as high, medium, or low risk  
- File hashes for further analysis or cross-referencing in threat intelligence platforms  
- Contextual notes to help understand why something was flagged  

I could then **export hashes or file paths flagged by LOKI** and create YARA rules to monitor or detect these patterns in other systems. This created a **feedback loop between automated scanning and signature development**, which is essential for proactive threat hunting.

---

### Key Features I Noticed

| Feature | Description |
|---------|-------------|
| IOC Matching | Matches local files and processes against known IOCs from public sources |
| Threat Classification | Provides risk levels (high, medium, low) for suspicious items |
| Contextual Analysis | Offers reasoning behind why an item is flagged, useful when writing YARA rules |
| Easy Reporting | Produces clean output that can be exported or shared for further analysis |

---

## 💡 Practical Usage & Findings

- Ran LOKI on a test VM and discovered a few suspicious files flagged as medium risk  
- Exported file hashes from LOKI and wrote custom **YARA rules** to detect similar files on other endpoints  
- Cross-checked flagged items in **VirusTotal and MalwareBazaar** to validate LOKI’s findings  
- Noticed how LOKI’s output could help guide **more precise YARA rule creation** for signature-based detections  

By combining LOKI with YARA, I was able to **move from detection to custom signature creation**, which is a core skill for advanced malware analysis and blue teaming.

---

## 🧠 Reflection

LOKI is an excellent **starting point for endpoint threat hunting**, and when paired with **YARA rules**, it becomes a powerful system for creating **custom, targeted detections**.  

This combination allows analysts to:

- Quickly identify suspicious activity locally  
- Translate findings into reusable detection rules  
- Share these rules with the wider community or across an organization  

For blue teamers, LOKI and YARA together are **a must-have duo** for both reactive detection and proactive hunting.

---

## 🧰 Tools / Platforms I Used While Learning

- LOKI for local scanning and IOC detection  
- YARA CLI for writing custom detection rules  
- MalwareBazaar and VirusTotal for verification  
- TryHackMe labs for hands-on practice  
- Markdown & Screenshot documentation  
