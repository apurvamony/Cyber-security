# 🛡️ MITRE-Mapped Alert Reports

---

## 🔔 Alert 1 – Phishing Email with Malicious Attachment

- **Source:** Email Gateway (Proofpoint)
- **Summary:** A user received an email with a `.doc` attachment containing a malicious macro. The attachment was flagged for malware upon sandbox analysis.
- **Investigation Notes:**
  - Verified the sender's domain was spoofed.
  - Checked VirusTotal hash: flagged by 20+ vendors.
  - User did not open the file.
  - Contained via email quarantine.
- **Mapped Tactic:** Initial Access
- **Mapped Technique (ID):** T1566.001 – Phishing: Spearphishing Attachment
- **References:** [MITRE T1566.001](https://attack.mitre.org/techniques/T1566/001/)

---

## 🔔 Alert 2 – Suspicious PowerShell Execution

- **Source:** EDR (CrowdStrike)
- **Summary:** Endpoint triggered alert for PowerShell spawned by `winword.exe` with a base64-encoded command.
- **Investigation Notes:**
  - Lateral movement attempt suspected.
  - PowerShell used `Invoke-Expression`.
  - Quarantined endpoint.
- **Mapped Tactic:** Execution
- **Mapped Technique (ID):** T1059.001 – Command and Scripting Interpreter: PowerShell
- **References:** [MITRE T1059.001](https://attack.mitre.org/techniques/T1059/001/)

---

## ✅ Takeaways

- Mapping alerts to MITRE helps normalize alert language across tools.
- It provides a common language for red/blue teams to communicate.
- Helps identify gaps in detection for broader TTP coverage.
