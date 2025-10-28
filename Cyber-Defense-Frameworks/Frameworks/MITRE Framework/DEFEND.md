# MITRE DEFEND

**DEFEND** is MITRE’s defensive complement to ATT&CK and it focuses on **controls and mitigations** that defenders can implement to detect, deny, disrupt, degrade, or deceive adversary activity. It is explicitly designed with blue-team use cases in mind.

---

## 🧭 Overview
DEFEND translates ATT&CK techniques into **practical defensive guidance**, helping defenders choose controls and detection strategies that map to specific adversary behaviors. It’s useful for designing coverage, constructing playbooks, and prioritizing defensive investments.

---

## 🔎 What I Learned
- DEFEND provides a clear mapping from **ATT&CK techniques** to **defensive controls** (detect, deny, disrupt, degrade, deceive).  
- The framework is intentionally practical for blue teams by helping convert threat intelligence into measurable defensive actions.  
- Example concept explored: **Decoy Files** which uses deceptive or honeyfiles to detect lateral movement and data access attempts.

---

## 🛠 Practical Applications
- **Control Mapping:** Use DEFEND to map existing SIEM alerts and endpoint protections to ATT&CK techniques, identifying where controls are missing.  
- **Playbook Design:** Translate DEFEND guidance into step-by-step playbook actions (what to monitor, how to contain, and which controls to apply).  
- **Detection Validation:** Design tests (red-team/CTF style) to validate that DEFEND-prescribed controls actually generate detectable telemetry.  
- **Deception:** Implement decoy files or honeytokens to create early detection opportunities for credential theft or lateral movement.

---

## 📌 Key Takeaways
- DEFEND is highly actionable for blue teams — it reduces the gap between intel (ATT&CK) and operational security controls.  
- Pairing **ATT&CK (what adversaries do)** with **DEFEND (what defenders should do)** creates a powerful cycle of identify → protect → validate.  
- Small, targeted controls (like decoy files or specific logging rules) can offer high defensive value when mapped correctly.

---

## 🔧 Tools & Resources Used
- **DEFEND documentation (MITRE)** — primary mapping resource  
- **SIEM platforms (Splunk / ELK)** — implementing detection rules informed by DEFEND  
- **Deception tools / honeytokens** — lab testing for decoy file detection  
- **ATT&CK Navigator** — cross-referencing ATT&CK techniques with DEFEND controls

---
