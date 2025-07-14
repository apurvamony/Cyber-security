# SOC Alert Lifecycle – Apurva Tiwari

## 📌 Alert Lifecycle Diagram (Text-based)

1. Detection  
2. Triage  
3. Investigation  
4. Containment  
5. Eradication & Recovery  
6. Reporting & Feedback

(*You can also include a diagram link from draw.io or Lucidchart*)

---

## 🔍 Real Alerts I Have Handled

### Alert 1: Suspicious Login from Unknown IP  
- Detection: Microsoft Sentinel triggered sign-in alert  
- Triage: Verified geo-location and timestamp  
- Investigation: Checked user behavior, IP reputation  
- Containment: Forced password reset  
- Recovery: Alerted user and documented case  
- Reporting: Escalated to L2 and logged RCA

### Alert 2: Email with Malicious Link  
- Detection: Defender for Office365 flagged phishing link  
- Triage: Email headers analyzed  
- Investigation: Link sandboxed in VirusTotal  
- Containment: Blocked sender domain  
- Recovery: Trained user and removed mail from inbox  
- Reporting: Updated phishing IOC list

---

## 📘 Key Takeaways from Learning

1. SOC works in shifts: Tier 1 → Tier 2 → IR team  
2. Each alert should follow a documented lifecycle  
3. Quick triage + smart containment = lower risk  
4. Documentation is part of response, not post-step  
5. MITRE helps enrich SOC alert context