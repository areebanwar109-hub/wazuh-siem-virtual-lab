# 🛡️ Wazuh SIEM Virtual Lab & Threat Detection

## 📌 Project Overview

This project demonstrates the deployment of an end-to-end cybersecurity virtual lab using VMware Workstation Pro, Kali Linux, and Wazuh SIEM.

The lab was designed to simulate a SOC-style monitoring environment, covering endpoint monitoring, log collection, threat detection, custom rule engineering, alert analysis, and Role-Based Access Control.


## 🏗️ Lab Architecture

Kali Linux (Endpoint)
        │
        │ Wazuh Agent & Log Collection
        ▼
Wazuh Manager
        │
        ├── Event Analysis
        ├── Decoders
        └── Detection Rules
        │
        ▼
Wazuh Indexer
        │
        ▼
Wazuh Dashboard
        │
        ▼
SOC Analyst


## 🛠️ Technologies Used

- VMware Workstation Pro
- Kali Linux
- Wazuh SIEM
- Nmap
- Wireshark
- Burp Suite
- MITRE ATT&CK Framework


## 🔐 Key Features

- Virtual lab and NAT network configuration
- Wazuh SIEM deployment
- Wazuh Manager, Indexer, and Dashboard verification
- Wazuh agent installation and registration
- Endpoint monitoring and log collection
- Security event generation and alert analysis
- File Integrity Monitoring (FIM)
- Network reconnaissance testing
- Custom log source configuration
- Custom XML decoder development
- Custom detection rule engineering
- MITRE ATT&CK mapping
- Rule validation using wazuh-logtest
- Centralized security dashboards
- Role-Based Access Control (RBAC)
- Principle of Least Privilege


## 🚨 Detection Workflow

Logs → Decoders → Detection Rules → Alerts → Dashboard Analysis


## 🎯 MITRE ATT&CK Mapping

**Technique:** T1110 - Brute Force

Custom detection logic was developed to identify failed login activity and generate security alerts mapped to the MITRE ATT&CK framework.


## 📊 Key Learning Outcomes

This project provided hands-on experience with:

- SIEM deployment and operations
- SOC monitoring workflows
- Endpoint telemetry collection
- Log analysis
- File Integrity Monitoring
- Detection engineering
- MITRE ATT&CK mapping
- Alert investigation
- Role-Based Access Control


## 📄 Project Report

The complete technical report for this project is available in this repository.


## 👩‍💻 Author

**Areeba Anwar**  
Cyber Security Student | Aspiring SOC Analyst
