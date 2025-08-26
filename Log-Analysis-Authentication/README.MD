# Log Analysis – Authentication Events

##  Project Overview
This project focuses on analyzing **authentication logs** to detect normal user behavior versus potential malicious activity.  
The dataset (`auth_logs.json`) contains login attempts with details such as timestamps, usernames, source IPs, and outcomes.

---

##  Skills Demonstrated
- Log parsing and JSON data analysis  
- Authentication event tracking (success vs failed attempts)  
- Identifying anomalies in login behavior  
- Documenting findings in a professional format  

---

##  Files in This Project
- **auth_logs.json** → Sample log file with authentication events  
- **log_analysis_documentation.pdf** → Full project report with methodology, analysis, and findings  
- **README.md** → (this file) Project summary for quick reference  

## 🔍 Key Findings
- Normal behavior: Repeated failed login attempts from the **same IP** followed by a successful login can be considered user error.  
- Suspicious behavior: Failed logins from **multiple IPs** before success may indicate brute force or compromise attempts.  
- In this dataset, a case of suspicious activity was observed where multiple failed logins came from different IPs before success.  



## 📖 How I Approached It
1. Reviewed raw logs in `auth_logs.json`  
2. Counted failed vs successful logins per user  
3. Tracked login attempts by IP addresses  
4. Classified whether activity was **normal user behavior** or **potential attack**  
5. Documented everything in the PDF report  


## ✅ Outcome
This project demonstrates the ability to:
- Work with raw log data  
- Spot suspicious patterns in authentication events  
- Communicate findings clearly for security teams or stakeholders  
