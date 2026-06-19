# CyberShield ASM Dashboard

## Overview

CyberShield ASM Dashboard is a web-based Attack Surface Management (ASM) platform designed to help security teams identify, monitor, prioritize, and manage vulnerabilities across organizational assets.

The dashboard provides real-time visibility into assets, vulnerabilities, attack paths, risk scores, monitoring events, and security alerts through an interactive and user-friendly interface.

---

## Features

### Asset Inventory Management

* Discover and track organizational assets
* View asset details including IP address, service, and risk score
* Search and filter assets by severity and status

### Vulnerability Management

* CVE tracking and monitoring
* CVSS score visualization
* Severity classification:

  * Critical
  * High
  * Medium
  * Low

### Risk Analysis

* Risk Score Distribution Chart
* Severity Breakdown Dashboard
* CVSS Trend Analysis
* Common Exposed Ports Analysis

### Attack Path Visualization

* Visual representation of attack paths
* Asset-to-asset attack flow mapping
* Risk prioritization based on attack exposure

### Security Monitoring

* Real-time monitoring events
* Configuration change detection
* Unauthorized access detection
* Security event tracking

### Alert Management

* Critical vulnerability alerts
* Highest-risk vulnerability popup
* Alert filtering by severity
* Detailed vulnerability information

### Email Notification System

* Send vulnerability details through email
* Multiple vulnerability selection
* Alert sharing functionality
* EmailJS integration support

### Vulnerability Lifecycle Management

* Open
* Investigating
* Pending Patch
* Resolved

### Log Management

* Track cleared vulnerabilities
* Retrieve vulnerabilities back to dashboard
* Historical vulnerability records

---

## Dashboard Components

### Executive Summary

* Total Assets
* Critical Vulnerabilities
* High Severity Vulnerabilities
* Open Tickets

### Security Analytics

* Risk Score Distribution
* Severity Breakdown
* CVSS Score Trend
* Common Exposed Ports

### Asset Inventory Table

* Asset Name
* IP Address
* Service
* Severity
* Ticket Status
* Assignee
* Risk Score

### Monitoring Panel

* Security Events
* Asset Changes
* Threat Indicators
* Activity Tracking

---

## Technologies Used

### Frontend

* HTML5
* CSS3
* JavaScript (ES6)

### Libraries

* Tailwind CSS
* Chart.js
* Font Awesome
* EmailJS

### Visualization

* Interactive Charts
* Risk Analytics
* Attack Path Visualization

---

## Project Structure

```text
CyberShield/
│
├── CyberShield Dashboard.html
├── README.md
├── assets/
│   ├── screenshots/
│   └── icons/
│
├── docs/
│   ├── architecture.png
│   ├── use-case-diagram.png
│   └── test-cases.pdf
│
└── LICENSE
```

---

## Installation

1. Clone the repository

```bash
git clone https://github.com/your-username/CyberShield-ASM-Dashboard.git
```

2. Open the project folder

```bash
cd CyberShield-ASM-Dashboard
```

3. Launch the dashboard

```bash
Open CyberShield Dashboard.html in any modern web browser
```

---

## Future Enhancements

* Threat Intelligence Integration
* MITRE ATT&CK Mapping
* PDF Report Generation
* Risk Heat Maps
* SIEM Integration
* Compliance Dashboard
* AI Security Assistant
* Role-Based Access Control (RBAC)
* Real-Time Vulnerability Scanning
* Database Integration

---

## Sample Use Cases

### Security Operations Center (SOC)

Monitor critical vulnerabilities and prioritize remediation activities.

### Vulnerability Management Team

Track CVEs, assess risk levels, and manage patching workflows.

### Security Analysts

Investigate alerts and visualize attack paths.

### Network Administrators

Monitor exposed services and configuration changes.

---

## Project Objectives

* Improve visibility of organizational attack surfaces.
* Identify and prioritize critical vulnerabilities.
* Reduce security risks through proactive monitoring.
* Support incident response and remediation workflows.
* Provide actionable security insights through visualization.

---

## Team

**CyberShield ASM Dashboard - Team 5**

Developed as a cybersecurity project focusing on Attack Surface Management, Vulnerability Assessment, and Risk Monitoring.

---

## License

This project is intended for educational and research purposes.

---

## Author

Vijayashree B

Cybersecurity Enthusiast | Network Security | Vulnerability Management | Attack Surface Monitoring
