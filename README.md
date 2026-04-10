# Session 10: Operation Sandbox - Malware Analysis Environment

## Project Overview
This project focuses on the secure configuration of a Linux-based sandbox environment intended for malware analysis. The goal was to establish a "Clean" Ubuntu environment, verify system integrity, and implement network isolation protocols to prevent lateral movement or data exfiltration during analysis.

## Technical Tasks Completed
* **Virtualization**: Configured an Ubuntu 22.04 VM using Oracle VirtualBox.
* **Network Security**: Managed transitions between **NAT** (for updates/Git pushes) and **Host-only Adapter** (for air-gapped isolation).
* **System Auditing**: Performed a full system audit and staged results for session verification.
* **Version Control**: Initialized a Git repository and successfully linked it to a remote GitHub origin.

## Repository Contents
* `sandbox_report.txt`: Detailed forensic report and environment verification answers.
* `README.md`: Project documentation and environment overview.

## Security Disclaimer
This environment is designed for educational malware analysis. Always ensure the virtual network adapter is set to **Host-only** before executing any untrusted binaries to maintain a strict air-gap.
