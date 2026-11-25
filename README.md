# SOC Threat Detection & Monitoring with Wazuh

## Project Overview

This project demonstrates the deployment and configuration of the Wazuh SIEM platform for endpoint monitoring, security event analysis, and File Integrity Monitoring (FIM).

The lab simulates core Security Operations Center (SOC) activities by monitoring a Windows endpoint, collecting security events, performing file change detection, and investigating alerts through the Wazuh dashboard.

Through this project, I gained hands-on experience with SIEM technologies, endpoint security monitoring, and threat detection workflows commonly used by cybersecurity analysts.

---

## Skills Demonstrated

- Security Information and Event Management (SIEM)
- Wazuh Administration
- Endpoint Monitoring
- Security Event Analysis
- File Integrity Monitoring (FIM)
- Ubuntu Server Administration
- Windows Endpoint Management
- Threat Detection
- Security Operations Center (SOC) Fundamentals
- Log Analysis
- Incident Investigation
- Cybersecurity Documentation

---

## Technologies Used

| Technology | Purpose |
|------------|----------|
| Wazuh | Open-source SIEM Platform |
| Ubuntu Server | Wazuh Manager Hosting |
| Windows Endpoint | Monitored Device |
| File Integrity Monitoring (FIM) | File Change Detection |
| Security Event Monitoring | Threat Detection |
| GitHub | Documentation & Portfolio |

---

# Lab Architecture

## Wazuh Architecture

![Wazuh Architecture](Screenshots/Wazuh%20Architecture.jpg)

### Overview

The Wazuh architecture consists of:

- Wazuh Manager
- Wazuh Dashboard
- Monitored Endpoint
- Security Event Collection
- Threat Detection and Alerting

The Wazuh Manager collects and processes events from monitored systems before presenting them through the Wazuh Dashboard.

---

# Task 1: Wazuh Manager Installation

## Objective

Deploy a Wazuh Manager on Ubuntu Server.

## Activities Performed

- Prepared Ubuntu environment
- Executed installation commands
- Verified Wazuh Manager deployment
- Confirmed service functionality

### Ubuntu Wazuh Manager Installation

![Ubuntu Wazuh Manager Installation](Screenshots/Ubuntu%20Wazuh%20Manager%20Installation.jpg)

### Wazuh Manager Running

![Wazuh Manager Running](Screenshots/Wazuh%20Manager%20Running.jpg)

### Key Learning

I learned how SIEM platforms are deployed and managed within an enterprise environment.

---

# Task 2: Wazuh Dashboard Access

## Objective

Access and review the Wazuh Dashboard.

### Wazuh Login and Dashboard

![Wazuh Login and Dashboard](Screenshots/Wazuh%20Login%20and%20Dashboard.jpg)

### Dashboard Overview

![Wazuh Dashboard Overview](Screenshots/Wazuh%20Dashboard%20Overview.jpg)

### Key Learning

The dashboard provides visibility into:

- Endpoint activity
- Security events
- Vulnerability information
- Threat detection alerts
- Compliance-related monitoring

---

# Task 3: Agent Registration

## Objective

Deploy and register an endpoint agent with the Wazuh Manager.

### Agent Registration

![Agent Registration](Screenshots/Agent%20Registration.jpg)

### Agent Restart and Verification

![Agent Restart and Verification](Screenshots/Agent%20Restart%20and%20Verification.jpg)

### Results

The endpoint successfully registered with the Wazuh Manager and began forwarding security data for monitoring and analysis.

---

# Task 4: File Integrity Monitoring (FIM)

## Objective

Configure and test File Integrity Monitoring.

### File Integrity Monitoring Configuration

![File Integrity Monitoring](Screenshots/File%20Integrity%20Monitoring%20Configuration.jpg)

### Key Learning

File Integrity Monitoring helps identify:

- Unauthorized file modification
- File creation
- File deletion
- Potential malicious activity

This capability is commonly used for security monitoring and compliance requirements.

---

# Task 5: Testing File Activity

## Objective

Generate monitored file activity and observe detection by Wazuh.

### Test File Activity

![Test File Activity](Screenshots/Test%20File%20Activity.jpg)

### Results

After creating and modifying files on the monitored endpoint, Wazuh successfully generated events showing the changes detected by the File Integrity Monitoring module.

### Security Relevance

FIM can help detect:

- Malware behavior
- Unauthorized system changes
- Insider threats
- Suspicious user activity

---

# Task 6: Security Alert Analysis

## Objective

Review security alerts generated within the Wazuh platform.

### Security Alerts Dashboard

![Security Alerts Dashboard](Screenshots/Security%20Alerts%20Dashboard.jpg)

### Activities Performed

- Reviewed security alerts
- Investigated detected events
- Explored alert severity levels
- Examined event details

### Key Learning

SIEM tools provide cybersecurity teams with centralized visibility into security events across an organization.

---

# Security Benefits of Wazuh

Wazuh helps organizations by providing:

- Centralized log management
- Endpoint monitoring
- Threat detection
- Security event analysis
- File integrity monitoring
- Compliance monitoring
- Alert generation
- Incident investigation support

---

# Lessons Learned

Through this project I learned:

- How SIEM platforms collect and process events.
- The importance of endpoint monitoring.
- How security analysts investigate alerts.
- How File Integrity Monitoring works.
- How agents communicate with SIEM platforms.
- How centralized visibility improves security operations.
- The role of SIEM solutions within a Security Operations Center (SOC).

---

# Project Outcomes

✅ Successfully deployed Wazuh

✅ Registered and monitored an endpoint

✅ Configured File Integrity Monitoring

✅ Generated file activity events

✅ Investigated security alerts

✅ Performed basic threat monitoring

✅ Developed practical SOC analyst skills

---

# Conclusion

This project provided hands-on experience with Wazuh SIEM and endpoint monitoring technologies.

During the lab, I deployed a Wazuh Manager, connected an endpoint agent, configured File Integrity Monitoring, generated security events, and analyzed alerts through the dashboard.

The experience reinforced the importance of continuous monitoring, endpoint visibility, and centralized security event management in modern cybersecurity operations.

---

# Repository Structure

```text
wazuh-siem-endpoint-monitoring-lab/

├── README.md

└── Screenshots/
    ├── Wazuh Architecture.jpg
    ├── Ubuntu Wazuh Manager Installation.jpg
    ├── Wazuh Manager Running.jpg
    ├── Wazuh Login and Dashboard.jpg
    ├── Wazuh Dashboard Overview.jpg
    ├── Agent Registration.jpg
    ├── Agent Restart and Verification.jpg
    ├── File Integrity Monitoring Configuration.jpg
    ├── Test File Activity.jpg
    └── Security Alerts Dashboard.jpg
```

---

## Author

**Toheeb Olabamiji**

Aspiring Cloud Engineer & Cybersecurity Professional

### Connect With Me

- GitHub: https://github.com/Beehot07
- LinkedIn: https://www.linkedin.com/in/toheeb-olabamiji-b92337265
