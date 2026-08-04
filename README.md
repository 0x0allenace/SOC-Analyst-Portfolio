<p align="center">
  <img src="assets/banner.png" alt="Allen Ace Banner" width="100%">
</p>

<br>

# 🛡️ Allen Ace

### SOC Analyst | Threat Hunter | Detection Engineer

> Detect • Investigate • Respond • Defend

## Welcome

This portfolio documents my hands-on cybersecurity journey through practical investigations, enterprise lab environments, detection engineering, digital forensics, and security analytics.

Each project is designed to demonstrate the investigative methodology, tooling, and defensive thinking expected within a modern Security Operations Center (SOC).

<p align="center">

![Splunk](https://img.shields.io/badge/Splunk-000000?style=for-the-badge&logo=splunk&logoColor=white)
![Elastic](https://img.shields.io/badge/Elastic-005571?style=for-the-badge&logo=elastic&logoColor=white)
![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![Windows](https://img.shields.io/badge/Windows-0078D4?style=for-the-badge&logo=windows&logoColor=white)

</p>

<p align="center">

![MITRE ATT&CK](https://img.shields.io/badge/MITRE%20ATT%26CK-red?style=for-the-badge)
![Threat Hunting](https://img.shields.io/badge/Threat%20Hunting-0A66C2?style=for-the-badge)
![DFIR](https://img.shields.io/badge/DFIR-8A2BE2?style=for-the-badge)
![Digital Forensics](https://img.shields.io/badge/Digital%20Forensics-4B0082?style=for-the-badge)
![Active Directory](https://img.shields.io/badge/Active%20Directory-003366?style=for-the-badge)
![PowerShell](https://img.shields.io/badge/PowerShell-5391FE?style=for-the-badge&logo=powershell&logoColor=white)

</p>


## 📚 Table of Contents

- [About Me](#-about-me)
- [Technical Skills](#technical-skills)
- [Investigations](#-investigations)
- [Threat Hunting](#-threat-hunting)
- [Malware Analysis](#-malware-analysis)
- [Email Security](#-email-security)
- [Engineering](#-engineering)
- [Security Analytics & Machine Learning](#-security-analytics--machine-learning)
- [Security Tool Development](#️-security-tool-development)
- [Detection Engineering](#️-detection-engineering-planned)
- [Community](#-community)
- [Cybersecurity Journey](#️-my-cybersecurity-journey)
- [Technical Articles](#-technical-articles)
- [Video Walkthroughs](#-video-walkthroughs)
- [Portfolio Statistics](#-portfolio-statistics)
- [Contact](#-contact)



## 👋 About Me

SOC Analyst with hands-on experience in Threat Hunting, Digital
Forensics & Incident Response (DFIR), Detection Engineering, Security
Analytics, and Python-based security tooling. My work focuses on
enterprise-style investigations aligned with the MITRE ATT&CK framework.

Replace with

```markdown

## Portfolio Highlights

- 8+ Enterprise Security Investigations
- Static & Dynamic Malware Analysis
- Digital Forensics & Incident Response (DFIR)
- Threat Hunting with Splunk & Elastic
- Security Analytics & Machine Learning
- Python Security Automation
- Technical Writing & Community Education

```
---

```markdown

## 🎯 Current Focus

- Detection Engineering
- Threat Hunting
- Malware Analysis
- Digital Forensics (DFIR)
- Python Security Automation
```
---

```markdown

# ⭐ Featured Projects

| Project | Focus Area | Repository |
|---------|------------|------------|
| Threat Hunting – Reconnaissance | Splunk Threat Hunting | [View](https://github.com/0x0allenace/Threat-Hunting-Recon) |
| Enterprise DFIR Lab | Incident Response | [View](https://github.com/0x0allenace/ecorp-initial-dfir-lab) |
| Velociraptor Forensic Triage | Endpoint Forensics | [View](https://github.com/0x0allenace/velociraptor-forensic-triage-kape) |
| Suspicious Email Attachment Analysis | Email Security | [View](https://github.com/0x0allenace/suspicious-email-attachment-analysis) |
| Static Malware Analysis | Malware Analysis | [View](https://github.com/0x0allenace/static-malware-analysis-report) |
| Windows Malware Behavioral Analysis | Dynamic Malware Analysis | [View](https://github.com/0x0allenace/windows-malware-behavioral-analysis) |
| Behavioral Anomaly Detection | Machine Learning | [View](https://github.com/0x0allenace/security-anomaly-project) |
| File Signature Detector | Python Security Tool | [View](https://github.com/0x0allenace/file-signature-detector) |

```
---

## 🔗 Connect

- 🔗 [**LinkedIn:**](https://www.linkedin.com/in/allen-ace-soc-analyst/)
- 💻 [**GitHub:**](https://github.com/0x0allenace)

---

## 🛠️ Technical Skills

| Domain | Technologies |
|---------|--------------|
| SIEM | Splunk, Elastic |
| Threat Hunting | SPL, MITRE ATT&CK |
| DFIR | Velociraptor, KAPE, Autopsy, FTK Imager |
| Malware Analysis | PEStudio, Detect It Easy, FLOSS, Procmon, Wireshark |
| Detection Engineering | Sigma, SPL |
| Endpoint Security | Sysmon, Windows Event Logs |
| Programming | Python, PowerShell |
| Networking | Wireshark, TCP/IP |
| Infrastructure | Active Directory, pfSense |

```
---

```markdown

# 🛡️ Security Investigations

```
> Enterprise-style investigations demonstrating real-world incident response, threat hunting, and forensic analysis.

## 🔎 Threat Hunting

> Leveraging SIEM technologies to proactively identify, investigate, and respond to adversary behavior using real-world datasets and the MITRE ATT&CK framework.

## Threat Hunting – Reconnaissance

### Objective

Investigate reconnaissance activity within the BOTS v2 dataset using Splunk.

### Technologies

- Splunk
- Windows Event Logs
- MITRE ATT&CK

### MITRE ATT&CK

| Technique | ID |
|-----------|----|
| Active Scanning | T1595 |
| Gather Victim Network Information | T1590 |


### Key Findings

- Suspicious User-Agent identified
- External IP pivot completed
- IOC extraction performed

### Screenshots


![Threat Hunting Screenshot](images/companycontacts.png)

![Threat Hunting Screenshot](images/contenttype.png)

![Threat Hunting Screenshot](images/recon.png)

🔗 **Repository:** [View Project](https://github.com/0x0allenace/Threat-Hunting-Recon)


### 💡 Lessons Learned

- Improved Splunk investigation methodology.
- Reinforced ATT&CK mapping skills.
- Strengthened IOC correlation workflow.
- Enhanced understanding of enterprise SOC investigations.


## 📌 Enterprise DFIR Lab

### 🎯 Objective

Simulate an enterprise incident response environment using Active Directory, pfSense, Velociraptor, and attacker emulation.

### 🛠️ Technologies

- Velociraptor
- Active Directory
- pfSense
- Windows Event Logs
- KAPE
- Sysmon

### 🎯 MITRE ATT&CK Mapping

| Technique | ID |
|-----------|----|
| Credential Dumping | T1003 |
| Remote Services | T1021 |
| Lateral Tool Transfer | T1570 |


### 🔍 Key Findings

- Conducted enterprise-wide investigation.
- Collected forensic artifacts.
- Contained compromised hosts.
- Documented incident response workflow.

### 📸 Screenshots

![Enterprise Incident Response](images/02_domain_join_Admin.png)
![Enterprise Incident Response](images/Ecorp_firewall_rule.png.jpeg)
![Enterprise Incident Response](images/download-hunt-results.png)

### 🔗 Repository

- [Enterprise DFIR Lab](https://github.com/0x0allenace/ecorp-initial-dfir-lab)
- [Velociraptor KAPE Forensic Triage](https://github.com/0x0allenace/velociraptor-forensic-triage-kape)

### 💡 Lessons Learned

- Improved Velociraptor Artifact collection methodology.
- Reinforced victim isolation methodology.
- Strengthened IOC correlation workflow.
- Enhanced understanding of enterprise SOC investigations.


## 🚧 Coming Soon

- Memory Forensics
- Registry Forensics
- Disk Forensics
- Windows Artifact Analysis
- Timeline Analysis
- KAPE Forensic Triage
- Volatility Memory Analysis



# 🦠 Malware Analysis

> Static and dynamic analysis of Windows malware samples to identify Indicators of Compromise (IOCs), attacker techniques, malicious behaviors, and forensic artifacts using enterprise-style malware analysis methodologies.

---


## 📌 Static Malware Analysis Report

### 🎯 Objective

Perform static analysis on suspicious Windows PE files to identify malicious characteristics, extract Indicators of Compromise (IOCs), and document findings using an enterprise-style malware analysis methodology.

### 🛠️ Technologies

- PEStudio
- Detect It Easy (DIE)
- FLOSS
- Strings
- VirusTotal
- Hash Analysis
- Windows PE Format

### 🎯 MITRE ATT&CK Mapping

| Technique | ID |
|-----------|----|
| Malware | T1587 |
| Masquerading | T1036 |
| Obfuscated Files or Information | T1027 |

### 🔍 Key Findings

- Identified suspicious PE characteristics.
- Extracted file hashes and Indicators of Compromise.
- Reviewed imported Windows API functions.
- Analyzed embedded strings and metadata.
- Documented suspicious behaviors without executing the samples.

### 📸 Screenshots

![Static Malware Analysis](images/capa-capabilities.png)

![Static Malware Analysis](images/pestudio-strings.png)

![Static Malware Analysis](images/floss-decoded.png)

🔗 **Repository:** [Static Malware Analysis Report](https://github.com/0x0allenace/static-malware-analysis-report)

### 💡 Lessons Learned

- Strengthened Windows PE file analysis techniques.
- Improved malware triage methodology using static analysis.
- Reinforced IOC extraction and documentation workflows.
- Enhanced understanding of executable structures and suspicious artifacts.

## 📌 Windows Malware Behavioral Analysis

### 🎯 Objective

Analyze the runtime behavior of a Windows malware sample within a controlled malware analysis laboratory to identify malicious activities, persistence mechanisms, process behavior, network communications, and Indicators of Compromise (IOCs).

---

### 🛠️ Technologies

- REMnux
- FLARE VM
- Procmon
- Process Explorer
- Wireshark
- FakeNet-NG
- Regshot
- Sysmon
- Windows Event Logs

---

```markdown
### 🔄 Analysis Workflow

- Initial malware triage
- Process analysis
- Registry monitoring
- Filesystem monitoring
- Network traffic analysis
- IOC extraction
- MITRE ATT&CK mapping
```

### 🎯 MITRE ATT&CK Mapping

| Technique | ATT&CK ID |
|-----------|-----------|
| User Execution | T1204 |
| Command and Scripting Interpreter | T1059 |
| Process Injection | T1055 |
| Registry Run Keys / Startup Folder | T1547 |
| File and Directory Discovery | T1083 |
| Application Layer Protocol | T1071 |

---

### 🔍 Key Findings

- Executed malware safely inside an isolated analysis environment.

- Observed process creation and parent-child relationships.

- Identified persistence mechanisms and registry modifications.

- Analyzed filesystem activity and dropped artifacts.

- Captured network communications and extracted Indicators of Compromise.

- Documented behavioral findings using an enterprise malware analysis workflow.

---

### 📸 Screenshots

![Process Tree](images/process-tree.png)

![Procmon Activity](images/procmon-events.png)

![Regshot Comparison](images/regshot.png)

![FakeNet-NG Network Traffic](images/network-connections.png)

![Wireshark Capture](images/wireshark-traffic.png)

### 🔗 Repository

[Windows Malware Behavioral Analysis](https://github.com/0x0allenace/windows-malware-behavioral-analysis)

---

### 💡 Lessons Learned

- Strengthened dynamic malware analysis methodology.
- Improved behavioral IOC identification and correlation.
- Reinforced process, registry, and network activity analysis.
- Enhanced understanding of malware execution and persistence techniques.

---


# 📧 Email Security

> Investigation of phishing emails, malicious attachments, and email-based attack vectors.

## 📌 Suspicious Email Attachment Analysis

### 🎯 Objective

Analyze suspicious email attachments within a controlled environment to determine malicious intent and identify Indicators of Compromise.

### 🛠️ Technologies

- VirusTotal
- PE Studio
- File Signature Analysis
- Static Analysis

### 🎯 MITRE ATT&CK Mapping

| Technique | ATT&CK ID |
|-----------|-----------|
| Phishing | T1566 |
| User Execution | T1204 |

### 🔍 Key Findings

- Verified true file type.
- Examined embedded artifacts.
- Assessed malicious behavior.
- Documented findings.

### 📸 Screenshots


![Email Attachment Analysis](images/vt02.jpeg)
![Email Attachment Analysis](images/triagebehavioralactivity.png)
![Email Attachment Analysis](images/virustotal_report.png)


🔗 **Repository:** [View Project](https://github.com/0x0allenace/suspicious-email-attachment-analysis)


### 💡 Lessons Learned

- Strengthened malware triage and static analysis techniques.
- Improved identification and validation of Indicators of Compromise (IOCs).
- Reinforced understanding of phishing attack delivery mechanisms and malicious attachments.
- Enhanced the ability to correlate file artifacts with MITRE ATT&CK techniques during incident investigations.


## 🚧 Coming Soon

- Email Header Analysis
- Email Body Analysis
- Business Email Compromise Investigation
- SPF / DKIM / DMARC Validation
- Email IOC Extraction


```markdown

# ⚙️ Security Engineering

```
> Building practical security tooling, detection content, and analytics that support enterprise security operations.

## 🤖 Security Analytics & Machine Learning

> Applying machine learning techniques to improve behavioral threat detection and anomaly identification in enterprise environments.


## 📌 Behavioral Anomaly Detection

### 🎯 Objective

Develop an unsupervised machine learning pipeline for identifying anomalous behavior within synthetic enterprise security logs.

### 🛠️ Technologies

- Python
- Pandas
- Scikit-learn
- PyTorch
- Jupyter Notebook

### 🤖 Models

- Isolation Forest
- Local Outlier Factor
- One-Class SVM
- Autoencoder

### 🔍 Key Findings

- Generated synthetic enterprise log datasets.
- Engineered behavioral security features.
- Compared multiple anomaly detection algorithms.
- Evaluated model performance using multiple visualizations.

### 📸 Screenshots

![Security Anomaly Detection Screenshot](images/fig1_risk_score_distribution.png)

![Security Anomaly Detection Screenshot](images/fig4_tsne_autoencoder.png)

![Security Anomaly Detection Screenshot](images/fig7_sensitivity_f1.png)

🔗 **Repository:** [View Project](https://github.com/0x0allenace/security-anomaly-project)


### 💡 Lessons Learned

- Improved feature engineering techniques for security event analysis.
- Strengthened understanding of unsupervised machine learning models for anomaly detection.
- Learned to evaluate and compare multiple detection algorithms using performance metrics and visualizations.
- Enhanced the ability to translate behavioral analytics into practical threat detection use cases.

## 🚧 Coming Soon

- User & Entity Behavior Analytics (UEBA)
- Insider Threat Detection
- Time-Series Threat Detection
- Explainable AI for Security
- Graph-Based Threat Analytics


# 🛠️ Security Tool Development

> Lightweight security utilities developed to automate common Blue Team and DFIR workflows.
> These tools demonstrate practical scripting ability applied to real security operations challenges.


## 📌 File Signature Detector

### 🎯 Objective

Develop a Python-based file signature analyzer capable of detecting true file types using magic bytes.

### 🛠️ Technologies

- Python
- Magic Bytes
- Binary Analysis

### ⚙️ Features

- True file type detection
- Malware triage support
- Reverse engineering assistance
- DFIR artifact validation


🔗 **Repository:** [View Project](https://github.com/0x0allenace/file-signature-detector)


### 💡 Lessons Learned

- Improved understanding of file signature (magic byte) analysis for file type validation.
- Reinforced Python programming skills through the development of a practical security utility.
- Strengthened malware triage techniques by identifying files based on their true binary signatures.
- Enhanced appreciation for file validation as a critical step in digital forensics and incident response workflows.

## 🚧 Coming Soon

- IOC Extractor
- IOC Enrichment Tool
- Log Parser
- Hash Analyzer
- Threat Intelligence Aggregator
- Detection Rule Generator


# ⚙️ Detection Engineering *(Planned)*

> Designing and validating production-ready detections mapped to the MITRE ATT&CK® framework.

### 📚 Planned Projects

- Sigma Detection Library
- Splunk Detection Rules (SPL)
- Microsoft Sentinel Detection Rules (KQL)
- Elastic Detection Rules
- YARA Rules
- Detection-as-Code
- ATT&CK Coverage Matrix

---

# 📜 Certifications

Currently pursuing industry-recognized cybersecurity certifications.

### Planned

- CompTIA Security+
- Splunk Core Certified Power User
- Elastic Certified Analyst
- GIAC GCFA (Long-term)

---

# 🌐 Community

> Sharing knowledge through technical writing, walkthroughs, and continuous learning.


# 🗺️ My Cybersecurity Journey

### 2023

- Began professional cybersecurity transition.
- Worked on SOC operations and security monitoring.
- Built foundational SIEM investigation skills.
- Learned Splunk, Windows Event Logs, and detection workflows.

### 2024

- Expanded threat hunting capabilities.
- Investigated security incidents using enterprise-style datasets.
- Developed DFIR workflows.
- Started publishing technical research and walkthroughs.

### 2025

- Advanced threat intelligence and incident investigation skills.
- Built security automation tools using Python.
- Developed enterprise lab environments.

### 2026

- Building a detection engineering portfolio.
- Expanding SIEM detection capabilities.
- Pursuing remote SOC and Threat Hunting opportunities.


# 📝 Technical Articles

## 📝 Featured Articles

- [Locking Down Against Bad USB: Detection and Defense Strategies](https://allenace.medium.com/locking-down-against-bad-usb-detection-and-defense-strategies-daf329415393?sharedUserId=allenace)
- [Wireshark: Getting to Know Wireshark](https://allenace.medium.com/wireshark-getting-to-know-wireshark-f8e19379cc50)
- [Discovering Security Weaknesses: A Practical Guide to Vulnerability Scanning](https://allenace.medium.com/discovering-security-weaknesses-a-practical-guide-to-vulnerability-scanning-30b2785b828f)
- [MemProcFS: The Game Changer in Memory Forensics](https://allenace.medium.com/memprocfs-the-game-changer-in-memory-forensics-463799a87aae)
- [Static Malware Analysis of Suspicious Windows PE Samples: A Blue Team Investigation](https://medium.com/@allenace/static-malware-analysis-of-suspicious-windows-pe-samples-a-blue-team-investigation-6c1e1b178513)
- Detection Engineering *(planned)*
View all articles → [Medium](https://allenace.medium.com/)


# 🎥 Video Walkthroughs

Latest Videos

- [Blue Team Detection Lab](https://www.youtube.com/watch?v=XnsfWq4TmLQ)   
- Mythic C2 Lab *(planned)*
- Threat Hunting *(planned)*
- Active Directory Lab *(planned)*
- Elastic SIEM *(planned)*
- DFIR Walkthrough *(planned)*


## 📊 Portfolio Statistics

| Metric | Value |
|--------|------:|
| Security Investigations | 8+ |
| Threat Hunting Investigations | 2 |
| DFIR Investigations | 2 |
| Malware Analysis Reports | 2 |
| Machine Learning Projects | 1 |
| Security Tools Developed | 1 |
| Technical Articles Published | 70+ |
| Video Walkthroughs | 5 |
| MITRE ATT&CK Techniques Covered | 12+ |
| Languages | Python, PowerShell |

# 📫 Contact

- 🔗 [**LinkedIn:**](https://www.linkedin.com/in/allen-ace-soc-analyst/)
- 📖 [**Medium:**](https://allenace.medium.com)
- 💻 [**GitHub:**](https://github.com/0x0allenace)
- 🎥 [**YouTube:**](https://www.youtube.com/@PurpleOpsLab)
- 🐦 [**X:**](https://x.com/allen_acee)
- 📧 **Email:** ejiakuallen@cyber-wizard.com


## 📈 GitHub Statistics

![GitHub Followers](https://img.shields.io/github/followers/0x0allenace?style=social)
![Visitors](https://komarev.com/ghpvc/?username=0x0allenace&color=blue)
![GitHub Stars](https://img.shields.io/github/stars/0x0allenace/SOC-Analyst-Portfolio?style=social)


<p align="center">

<img height="165" src="https://github-readme-stats.vercel.app/api?username=0x0allenace&show_icons=true&theme=github_dark&hide_border=true"/>

<img height="165" src="https://streak-stats.demolab.com?user=0x0allenace&theme=github-dark&hide_border=true"/>

</p>

<p align="center">

<img height="160" src="https://github-readme-stats.vercel.app/api/top-langs/?username=0x0allenace&layout=compact&theme=github_dark&hide_border=true"/>

</p>

## 🤝 Let's Connect

I'm always interested in discussing:

- Security Operations (SOC)
- Threat Hunting
- Detection Engineering
- Malware Analysis
- Digital Forensics
- Python Security Automation

Feel free to connect with me on LinkedIn or explore my repositories.

## ⭐ Thank You

Thank you for visiting my cybersecurity portfolio.

If you found these investigations useful, feel free to connect with me on LinkedIn, follow my work on Medium, or explore my repositories on GitHub.

I am always open to discussing cybersecurity, threat hunting, DFIR, and remote Security Operations opportunities.
