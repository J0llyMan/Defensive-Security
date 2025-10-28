# MITRE ATT&CK

The **ATT&CK** framework is a curated knowledge base of adversary **Tactics, Techniques, and Procedures (TTPs)**.  
I used ATT&CK extensively to research APT groups, identify common tools and techniques, and build Navigator maps that supported both CTF challenges and defensive planning.

---

## 🧭 Overview
ATT&CK provides a structured vocabulary for describing adversary behavior and mapping observable telemetry to known techniques.  
It is effective for threat hunting, red-team planning, and validating detection coverage.

---

## 🔎 What I Learned
- How to **search ATT&CK** for APT groups, aliases, and their associated techniques and tooling.  
- How to interpret technique matrices and link observed telemetry to likely adversary behaviours.  
- How to use **ATT&CK Navigator** to build layered maps highlighting relevant techniques for a scenario or engagement.  
- How to convert ATT&CK mappings into **hypotheses** for detection and hunting.

---

## 🛠 Practical Applications
- **CTFs / Red Teaming:** Selected realistic TTPs from ATT&CK to model adversary emulation during challenges.  
- **Threat Hunting:** Mapped suspicious alerts to ATT&CK techniques to prioritize which telemetry to investigate first.  
- **Detection Planning:** Used Navigator layers to identify technique coverage gaps and inform what telemetry or logging to collect.  
- **Playbook Development:** Translated ATT&CK techniques into SIEM queries and stepwise investigation/checklists.

---

## 📌 Key Takeaways
- ATT&CK is the go-to reference for translating raw telemetry into meaningful adversary behavior.  
- Building Navigator layers accelerates both offensive scenario design and defensive gap analysis.  
- Pairing ATT&CK with DEFEND (controls) helps turn detection hypotheses into concrete defensive actions.

---

## 🔧 Tools & Resources Used
- **ATT&CK Navigator** — created technique layers and coverage maps  
- **MITRE ATT&CK website** — canonical technique and group references  
- **TryHackMe / CTFs** — practiced mapping observed activity to ATT&CK techniques  
- **SIEM (Splunk / ELK)** — implemented searches based on ATT&CK-derived hypotheses

---
