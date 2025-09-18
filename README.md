# Incident Handler’s Journal

In this activity, I documented multiple security incident response scenarios in my **Incident Handler’s Journal**.  
Each entry reflects my ability to follow structured incident response practices, apply the **5 W’s method** (Who, What, When, Where, Why), and use tools such as **Wireshark**, **tcpdump**, and **VirusTotal** for detection and analysis.  

This document demonstrates my growth in understanding the incident response lifecycle, the use of technical tools, and the importance of accurate documentation for learning and professional practice.  

📄 [View Full Incident Handler’s Journal](doc/Incident_handler's_journal.pdf)

---

## Journal Entries

### Entry 1 — Ransomware Attack on U.S. Healthcare Clinic
**Date:** 29-08-2025  
**Description:** Documented a ransomware attack targeting a healthcare clinic. The ransomware spread through phishing emails and encrypted critical patient data.  
**Tool(s) used:** None  

**The 5 W’s**  
- **Who:** Organized group of unethical hackers targeting healthcare and transportation sectors.  
- **What:** Ransomware deployed via malicious email attachment, encrypting patient files and software.  
- **When:** Tuesday, 9:00 AM.  
- **Where:** The clinic’s IT systems.  
- **Why:** Financial exploitation through ransom demands.  

**Additional Notes:**  
- Immediate quarantine of infected systems is essential to stop lateral spread.  
- Restoration should come from **clean backups** prior to the compromise.  
- Preventive measures: MFA, advanced email filtering, phishing awareness training, patch management, and endpoint protection.  

---

### Entry 2 — Phishing Attack on Financial Services Company
**Date:** 02-09-2025  
**Description:** Investigated phishing attempt against a financial company. Attackers used a spoofed email and malicious link to deliver malware.  
**Tool(s) used:** VirusTotal  

**The 5 W’s**  
- **Who:** Malicious actor using spoofed identity: *Def communications* (email: `76tguy6hh6tgftrt7tg.su`).  
- **What:** Phishing email with malicious link, leading to malware infection.  
- **When:** 20th July 2022, 09:30:14 AM.  
- **Where:** Employee workstation.  
- **Why:** Attempt to compromise financial services systems and extract sensitive data.  

**Additional Notes:**  
- VirusTotal was used to verify the malicious nature of the file hash.  
- Preventive measures: MFA, phishing simulations, email filtering, and endpoint protection.  

---

### Entry 3 — Analyzing a Packet Capture File
**Date:** 07-09-2025  
**Description:** Used Wireshark to analyze a packet capture (PCAP) file for the first time. Learned to navigate the GUI and interpret captured network traffic.  
**Tool(s) used:** Wireshark  

**The 5 W’s**  
- **Who:** N/A  
- **What:** Packet capture review.  
- **When:** N/A  
- **Where:** Local system using Wireshark.  
- **Why:** Training exercise for network analysis.  

**Additional Notes:**  
- Initial GUI complexity felt overwhelming.  
- Realized Wireshark’s power for identifying malicious patterns in traffic.  
- A valuable first step toward network forensics.  

---

### Entry 4 — Capturing My First Packet
**Date:** 07-09-2025  
**Description:** Used tcpdump on the command line to capture and filter network packets. Practiced writing correct syntax and filtering traffic.  
**Tool(s) used:** tcpdump  

**The 5 W’s**  
- **Who:** N/A  
- **What:** Packet capture via CLI.  
- **When:** N/A  
- **Where:** Local system using tcpdump.  
- **Why:** Training exercise in packet capture and CLI proficiency.  

**Additional Notes:**  
- Faced challenges with **syntax errors** when entering commands.  
- Repetition and reviewing instructions improved accuracy.  
- Gained confidence with command-line tools for traffic analysis.  

---

## Reflection & Notes

- **Challenges faced:**  
  The **tcpdump activity** was the most difficult due to my limited experience with CLI. Errors in syntax led to frustration, but repeating the exercise taught me the importance of patience and precision.  

- **Growth in understanding:**  
  My perspective on **incident detection and response** has expanded greatly. I now understand the importance of incident documentation, structured response processes, and the roles different tools play in containment, eradication, and recovery.  

- **Favorite tool:**  
  **VirusTotal** stood out as the most practical and insightful tool. It provided a wealth of threat intelligence, from file hashes to malware behavior. While the data volume was initially overwhelming, I learned how to filter the most relevant details, a valuable skill for real-world security analysis.  

---

## Conclusion

This **Incident Handler’s Journal** demonstrates my applied learning in:  
- Documenting incidents using the **5 W’s method**  
- Analyzing network traffic with **Wireshark** and **tcpdump**  
- Investigating phishing and malware with **VirusTotal**  
- Reflecting on personal challenges and growth in the incident response process  

📄 [View Full Incident Handler’s Journal](doc/Incident_handler's_journal.pdf)


