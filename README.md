# 🛡️ Task 3: Basic Vulnerability Scan with Nessus Essentials

## 📌 Objective
Perform a basic vulnerability scan on a personal machine using a free vulnerability scanner to identify common security risks.

---

## 🔧 Tools Used
- **Nessus Essentials** (Tenable)
- Platform: Kali Linux 2025.2

---

## 🖥️ Scan Target
- **Target**: `127.0.0.1` (localhost)
- **Scan Type**: Basic Network Scan
- **Scan Engine**: Nessus Plugin Set (latest at time of scan)

---

## ✅ Scan Summary
- **Total Vulnerabilities Detected**: _e.g., 27_
- **Risk Breakdown**:
  - 🔴 Critical: _e.g., 2_
  - 🟠 High: _e.g., 5_
  - 🟡 Medium: _e.g., 10_
  - 🟢 Low: _e.g., 10_

---

## 🔍 Sample Critical Vulnerabilities

### CVE-2023-XXXXX
- **Severity**: Critical
- **Description**: Outdated OpenSSL version vulnerable to remote code execution
- **Remediation**: Update OpenSSL to version 1.1.1u or later

### CVE-2022-XXXXX
- **Severity**: High
- **Description**: Apache exposed with weak default configuration
- **Remediation**: Harden Apache settings and disable directory listing

---

## 📤 Deliverables
- [x] 🧾 Vulnerability scan report (`Nessus_Report.pdf`)
- [x] 📸 Screenshots of scan results


## 👨‍💻 Author
**Name**: Shlok Jadhav
**Course/Module**: Cybersecurity Lab  
**Date**: June 2025
