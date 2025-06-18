# TrickBot Malware Analysis

This research paper investigates TrickBot malware—originally a banking trojan and now a sophisticated, modular cyber threat often used by groups like Wizard Spider and UNC1878. TrickBot has evolved to support ransomware delivery (e.g., Ryuk, Conti), data theft, and network propagation via SMB.

---

FULL PAPER: [TrickBot_MichaelTwining.pdf](https://github.com/user-attachments/files/20796185/TrickBot_MichaelTwining.pdf)

---
## 📌 Key Topics Covered

- 👥 Threat Actor Attribution: Wizard Spider, UNC1878, Gold Blackburn
- 💣 Capabilities: Banking trojan, credential theft, ransomware delivery, C2 infrastructure
- 🔁 Propagation: Exploits SMB protocol (worm-like behavior)
- 🧰 MITRE ATT&CK Mapping: Initial access, execution, persistence, evasion
- 🧬 Modular Architecture: Adaptable for use by other ransomware gangs
- 🔐 Detection & Defense: Network indicators, phishing training, SMB hardening

---

## 🔧 Techniques & Tools Discussed

| Tactic                | Technique                                 |
|-----------------------|--------------------------------------------|
| Initial Access        | Spear phishing with attachments/links      |
| Execution             | Macros, JS files, Windows API abuse        |
| Persistence           | Autostart services, scheduled tasks        |
| Defense Evasion       | Process hollowing, registry modification   |
| Credential Access     | Enumeration of stored passwords            |
| Command & Control     | Encrypted HTTP traffic, C2 rotation        |

---

## 🧠 Key Insight

TrickBot’s strength lies in its **modularity** and **evasion**—allowing attackers to revisit and reinfect targets even after incident response efforts. The paper emphasizes hardening endpoints, proactive detection, and layered defenses.

---

## 📎 References

- CISA (2021): [TrickBot Malware Fact Sheet](https://www.cisa.gov/sites/default/files/publications/TrickBot_Fact_Sheet_508.pdf)
- MS-ISAC (2021): [Blog - TrickBot: Not Your Average Hat Trick](https://www.cisecurity.org/insights/blog/trickbot-not-your-average-hat-trick-a-malware-with-multiple-hats)

---

> 📘 Written by Michael Twining | [LinkedIn](https://linkedin.com/in/michael-twining)  
> Part of my [Cybersecurity Portfolio](https://github.com/usrtem/MichaelTwining-Portfolio)
