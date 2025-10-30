# 🧩 YARA Rules — My Journey into Writing Detection Logic

**YARA** is a powerful tool for detecting files based on **binary or textual patterns**, often called *signatures*.  
Every YARA rule must have **two key elements**: a **name** and a **condition**. Once you understand that, the rest starts to click.

---

## 🧠 Overview

When I first started, I wanted to learn how to write rules from scratch.  
I focused on understanding **how rules are structured**, how to **match strings**, and how to use **conditions** to refine detections.

A YARA rule typically consists of three main sections:

| Section   | Description                                                                 |
|-----------|-----------------------------------------------------------------------------|
| Meta      | Descriptive info like author name, description, or references (doesn’t affect detection) |
| Strings   | Defines the actual text or binary patterns YARA searches for               |
| Condition | Logical criteria that determine whether a match occurs                     |

---

## 🧩 My First YARA Rule Journey

### Step 1: Creating a Test File

touch somefile.txt

### Step 2: Creating the Rule File

touch myfirstrule.yar

### Step 3: Writing My First Rule

rule examplerule {
    condition: true
}

I tested the rule against my file and observed the output:

yara myfirstrule.yar somefile.txt
# Output:
# examplerule somefile.txt

yara myfirstrule.yar nonexistentfile.txt
# Output:
# error scanning nonexistentfile.txt: could not open file


This exercise gave me confidence to explore more **advanced rules**, including string matching, logical conditions, and file attributes.

---

## 🔍 Expanding Rules with Strings and Conditions

I experimented with **matching strings inside files** and **combining conditions** like file size or count checks:

*(placeholder for code example)*

This allowed me to detect specific content or patterns with precision.

---

## 🧩 Combining Multiple Conditions

I explored **logical operators** like and, or, and not.  
For example, checking for a string **and** a file attribute together:

*(placeholder for code example)*

The results showed how flexible YARA rules can be for real-world detection scenarios.

---

## 🧬 Example of a Complete YARA Rule

After experimenting, I created a more structured and realistic rule:

*(placeholder for code example)*

This rule would detect files containing critical indicators, such as ransomware patterns or wallet addresses.

---

## 🖼️ Reference

A **YARA Rule Cheatsheet** by researcher fr0gger_ helped me understand the components and structure of YARA rules.

---

## 💡 My Reflection

Writing YARA rules was one of the most enjoyable parts of my malware analysis journey.  
I noticed that **YARA and Suricata IDS share conceptual similarities** — both rely on signatures and conditions to detect malicious behavior.  
For anyone pursuing **Blue Teaming or Threat Hunting**, YARA is an absolute must-learn tool.

---

## 🧰 Tools / Platforms I Used

- **YARA CLI** for testing and execution  
- **TryHackMe – YARA Room** for guided learning  
- **VS Code / Nano** for rule creation  
- **Suricata IDS** for comparative understanding  
- Markdown & Screenshot documentation
