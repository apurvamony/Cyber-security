
# MITRE ATT&CK Basics – Apurva Tiwari

## 🎯 Objective
Understand the structure and purpose of the MITRE ATT&CK framework, including Tactics, Techniques, and Procedures (TTPs), and document real-world examples.

---

## 📘 What is MITRE ATT&CK?

MITRE ATT&CK is a globally accessible knowledge base of adversary tactics and techniques based on real-world observations. It's used by security teams for detection, defense, threat intelligence, and incident response.

---

## 🔍 Key Concepts

- **Tactics:** The adversary’s tactical goals — the “why” of an attack.
- **Techniques:** How the adversary achieves the tactic — the “how.”
- **Procedures:** Specific implementation of a technique in a real-world scenario.

---

## 🧠 Selected Tactics & Techniques

### Tactic: Initial Access  
- **T1566: Phishing** – Example: Attacker sends a fake invoice with a malicious link.  
- **T1190: Exploit Public-Facing Application** – Example: Log4j exploit on Apache server.

### Tactic: Execution  
- **T1059: Command and Scripting Interpreter** – Example: PowerShell used to execute a reverse shell.  
- **T1203: Exploitation for Client Execution** – Example: Malicious Word macro executed on user open.

### Tactic: Persistence  
- **T1547: Boot or Logon Autostart Execution** – Example: Registry run key modified to auto-start malware.  
- **T1053: Scheduled Task/Job** – Example: Malware sets task to re-execute every reboot.

### Tactic: Defense Evasion  
- **T1562: Impair Defenses** – Example: Disabling Windows Defender via script.  
- **T1027: Obfuscated Files or Information** – Example: Base64-encoded payload to evade detection.

### Tactic: Exfiltration  
- **T1041: Exfiltration Over C2 Channel** – Example: Data sent to attacker via HTTPS beacon.  
- **T1056: Input Capture** – Example: Keylogger collects credentials before sending out.

---

## ✍️ Key Takeaways

- MITRE ATT&CK helps standardize how threats are described.
- Knowing TTPs enables faster and more accurate alert triage.
- Mapping alerts to tactics and techniques boosts your investigation confidence.

---

## ✅ Next Step

- Save this file as `MITRE_TTP_Basics_ApurvaTiwari.md`
- Push it to:
  ```
  CyberSec-Portfolio/
  └── MITRE-TTPs/
      └── MITRE_TTP_Basics_ApurvaTiwari.md
  ```
