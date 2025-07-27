# 🛡️ Basic Vulnerability Scan using OpenVAS

This project documents the process and results of a basic vulnerability scan performed on a local machine using **OpenVAS Community Edition**.

## 📌 Objective
Perform a full vulnerability assessment on the local machine to identify potential security weaknesses and understand how vulnerability scanners work.

---

## 🧰 Tools Used
- **OpenVAS (GVM)**
- **Kali Linux (2023.4)**
- Browser (to access GVM Dashboard)

---

## 📝 Steps Followed
1. Installed OpenVAS:
   ```bash
   sudo apt update && sudo apt install openvas -y
   sudo gvm-setup
   sudo gvm-start
Accessed GVM at https://127.0.0.1:9392

Created a new scan target (192.168.29.96)

Configured a full and fast scan task

Ran the scan and waited for completion

Exported and analyzed the report

📊 Scan Summary
Target: 192.168.29.96

Start Time: May 29, 2025, 07:45 UTC

End Time: May 29, 2025, 07:46 UTC

Total Issues Found: 0

Severity Levels: None detected

📂 Files Included
report.pdf - Full OpenVAS vulnerability scan report

Screenshot.png - Dashboard and report screenshot

✅ Outcome
The system had no critical, high, medium, or low vulnerabilities. This suggests the system is in a good security posture, at least for the common vulnerabilities checked by OpenVAS.

📚 Learnings
Hands-on experience with OpenVAS setup and usage

Understanding of automated vulnerability scanning

Familiarity with scan configurations and interpreting reports

