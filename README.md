# NovaShyld Task 2 – Vulnerability Assessment using OpenVAS

## Candidate Details

- Name: Hariprasath
- Internship: Ethical Hacking & Penetration Testing Internship
- Organization: NovaShyld Technologies
- GitHub Repository: https://github.com/hp-wave-cloud/NovaShyld-Task_2
- GitHub Pages: https://hp-wave-cloud.github.io/NovaShyld_Task_2/
---

# Task Objective

The objective of this task was to understand the vulnerability assessment process by installing and configuring Greenbone OpenVAS, scanning an authorized target machine, analyzing the discovered vulnerabilities based on severity, and documenting the findings according to industry-standard practices.
---

## Step 1: OpenVAS Installation & Configuration

### Activities Performed
- Installed Greenbone Vulnerability Manager (OpenVAS)
- Configured PostgreSQL database
- Initialized vulnerability feeds
- Configured GVM services:
  * gvmd
  * ospd-openvas
  * gsad
- Verified installation using:
  * gvm-check-setup

## Learning Outcomes
- Understanding Greenbone Vulnerability Manager architecture
- Managing vulnerability feeds
- Configuring scanning services
- Troubleshooting installation issues
---

## Step 2: Vulnerability Scanner Setup

### Activities Performed
- Accessed Greenbone Security Assistant (GSA)
- Logged into the web interface
- Configured the default scanner
- Verified scanner availability
- Created a scanning target

### Learning Outcomes
- Scanner management
- Target configuration
- Understanding scan configurations
---

### Step 3: Target Configuration
- Target Environment
- Target Machine
- Metasploitable2 (Authorized Lab)
- Scanner: OpenVAS Community Edition
- Scan Type: Full and Fast Scan
- Network: VIsolated Virtual Lab

### Activities Performed
- Identified target IP address
- Added the target inside OpenVAS
- Created a scan task
- Configured scan profile
- Started the vulnerability assessment

### Learning Outcomes
- Safe target management
- Scan policy selection
- Practical vulnerability assessment workflow
---

## Step 4: Vulnerability Scan Execution

### Activities Performed
- Executed a complete vulnerability scan against the authorized target.
- OpenVAS identified multiple services including:
  FTP
  SSH
  HTTP
  SMB
  MySQL
  Telnet

The scanner analyzed exposed services for known vulnerabilities using the latest Greenbone Community Feed.

### Learning Outcomes
- Scan execution
- Scan monitoring
- Understanding vulnerability detection methods
---

## Step 5: Vulnerability Analysis
- Severity Classification
- The identified vulnerabilities were categorized according to CVSS severity:
  Critical
  High
  Medium
  Low
  Log

### Activities Performed
- Reviewed:
  CVSS Scores
  CVE IDs
  Affected Services
  Vulnerability Descriptions
  Recommended Fixes

### Learning Outcomes
- Reading vulnerability reports
- Understanding CVSS scoring
- Risk prioritization
- Security remediation planning
---

## Ethical Consideration

All vulnerability assessments were performed exclusively within an authorized personal laboratory environment.

No unauthorized systems, public infrastructure, or third-party assets were scanned.
---

## Repository Structure

NovaShyld_Task_2

├── Screenshots/

│   ├── 01_OpenVAS_Login.png

│   ├── 02_Dashboard.png

│   ├── 03_Target_Creation.png

│   ├── 04_Task_Creation.png

│   ├── 05_Scan_Running.png

│   ├── 06_Scan_Completed.png

│   ├── 07_Vulnerability_Summary.png

│   ├── 08_Critical_Findings.png

│   └── 09_Report_Export.png
│

├── Reports/

│   ├── Vulnerability_Report.pdf

│   └── Scan_Summary.md
│
├── Task2_Step1_OpenVAS_Setup.md

├── Task2_Step2_Scanner_Configuration.md

├── Task2_Step3_Target_Setup.md

├── Task2_Step4_Scan_Execution.md

├── Task2_Step5_Vulnerability_Analysis.md

├── Task2_Step6_Report_Documentation.md

│
└── README.md
---

## Skills Acquired
- Vulnerability Assessment
- Greenbone OpenVAS Administration
- Vulnerability Management
- CVSS Risk Analysis
- CVE Identification
- Security Reporting
- Scan Configuration
- Target Management
- Cybersecurity Documentation
- Linux Administration
---

## Tools Used
- Kali Linux 2026.1 ARM64
- Greenbone OpenVAS (GVM)
- Greenbone Security Assistant (GSA)
- PostgreSQL
- Metasploitable2
- Linux Terminal
---

## Conclusion
Task 2 provided practical experience in deploying and operating an enterprise-grade vulnerability assessment platform. Through hands-on installation, scanner configuration, vulnerability analysis, and report generation, I gained valuable experience in identifying security weaknesses, interpreting risk levels, and documenting findings following cybersecurity best practices.
---

Prepared by: Hariprasath Ravichandran
---

NovaShyld Technologies – Ethical Hacking & Penetration Testing Internship
