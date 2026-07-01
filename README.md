🔎 Detection Engineering Rules

Overview

This project focuses on developing, testing, and documenting security detection rules used in Security Operations Center (SOC) environments.

The objective is to transform security events and threat intelligence into actionable detections that help identify malicious activities, suspicious behavior, and potential security incidents.

---

🎯 Objectives

- Develop security detection logic
- Create reusable detection rules
- Map detections to MITRE ATT&CK techniques
- Improve threat visibility
- Test detection effectiveness
- Document detection engineering processes

---

📂 Project Structure

Detection-Engineering-Rules

├── Sigma-Rules
├── YARA-Rules
├── Custom-Detections
└── Test-Cases

---

1. Sigma Rules

Folder:

Sigma-Rules

Description

Sigma rules are platform-independent detection rules designed for identifying suspicious activity across different SIEM platforms.

Detection Categories

Examples:

- Suspicious PowerShell Execution
- Brute Force Authentication Attempts
- Unusual User Account Creation
- Privilege Escalation Activity
- Malware Execution Patterns

Skills Demonstrated

- Log Analysis
- Detection Logic Development
- SIEM Rule Creation
- Threat Detection

---

2. YARA Rules

Folder:

YARA-Rules

Description

YARA rules developed for identifying suspicious files, malware indicators, and threat artifacts.

Detection Focus

- Malware Identification
- File Pattern Matching
- Threat Research
- IOC Detection

Skills Demonstrated

- Malware Analysis
- Threat Intelligence
- Security Automation

---

3. Custom Detections

Folder:

Custom-Detections

Description

Custom security detections created for specific attack scenarios and enterprise monitoring requirements.

Detection Examples

Authentication Monitoring

Detect:

- Multiple failed login attempts
- Abnormal login locations
- Suspicious authentication patterns

Process Monitoring

Detect:

- Suspicious command execution
- Unusual parent-child processes
- Malicious scripting activity

Network Monitoring

Detect:

- Suspicious connections
- Abnormal communication patterns
- Potential command-and-control activity

---

4. Test Cases

Folder:

Test-Cases

Description

Validation scenarios used to test detection accuracy and reduce false positives.

Testing Includes

- Simulated attack activity
- Log generation
- Detection verification
- Rule improvement

---

🧩 MITRE ATT&CK Mapping

Detection rules are mapped to relevant ATT&CK techniques:

Technique| Detection Area
T1059| Command and Scripting Interpreter
T1003| Credential Dumping
T1078| Valid Accounts
T1562| Impair Defenses
T1547| Boot or Logon Autostart

---

🛠️ Tools & Technologies

- Sigma
- YARA
- Wazuh
- Windows Event Logs
- Sysmon
- MITRE ATT&CK Framework
- Python

---

🧠 Skills Demonstrated

✅ Detection Engineering
✅ SIEM Rule Development
✅ Threat Hunting
✅ Malware Detection
✅ MITRE ATT&CK Mapping
✅ Security Monitoring

---

📌 Author

Josiah Danbinta

Cybersecurity Analyst | Detection Engineer

GitHub:
https://github.com/josiahdanbinta
