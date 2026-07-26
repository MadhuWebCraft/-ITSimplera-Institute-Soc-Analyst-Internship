# Week 4 – Advanced Malware Analysis and Incident Response

## 📌 Objective

The objective of this task was to perform Advanced Malware Analysis and Incident Response within a controlled virtual environment. The project involved analyzing a malware sample using both static and dynamic analysis techniques, monitoring its behavior through forensic tools, identifying Indicators of Compromise (IOCs), comparing findings with public malware intelligence, and preparing an Incident Response Plan.

---

## 🛠️ Environment

- VMware Workstation
- Windows 10 Virtual Machine
- Kali Linux Virtual Machine
- Process Explorer
- Process Monitor (Procmon)
- Event Viewer
- PEStudio / Static Analysis Tools
- Hash Calculation Tools
- VirusTotal / MalwareBazaar (Public Threat Intelligence)

---

## 📋 Tasks Performed

### 1. Malware Sample Preparation
- Downloaded a previously reported malware sample from a trusted malware repository.
- Stored the sample inside a password-protected ZIP archive.
- Prepared an isolated malware analysis environment.

### 2. Static Analysis
- Examined file metadata.
- Calculated file hashes.
- Reviewed executable information.
- Performed string analysis.
- Identified basic Indicators of Compromise (IOCs).

### 3. Dynamic Analysis
- Executed the malware inside an isolated Windows virtual machine.
- Monitored:
  - Running processes
  - Registry activity
  - File system behavior
  - System events
- Documented observed malware behavior.

### 4. IOC Collection
Collected and documented Indicators of Compromise including:
- File name
- File hashes
- Process information
- Registry activity
- File locations
- Observed malware behavior

### 5. Hybrid Analysis
- Correlated findings from both static and dynamic analysis.
- Compared observations with publicly available malware intelligence reports.

### 6. Incident Response Plan
Prepared an Incident Response Plan covering:
- Detection
- Identification
- Containment
- Eradication
- Recovery
- Lessons Learned

---

## 📷 Documentation

The repository contains detailed documentation including:
- Step-by-step implementation
- Malware analysis screenshots
- Static analysis observations
- Dynamic analysis observations
- IOC documentation
- Incident Response Workflow

---

## 🎯 Learning Outcomes

Through this task, I gained practical experience in:

- Malware Analysis Methodology
- Static Analysis
- Dynamic Analysis
- Process Monitoring
- Registry Monitoring
- IOC Identification
- Digital Forensics
- Threat Detection
- Incident Response
- SOC Operations

---

## ⚠️ Disclaimer

The malware sample was analyzed strictly within an isolated virtual environment for educational purposes as part of the ITSimplera Solutions SOC Internship Program.

The sample was never executed on the host operating system.

---

## 👩‍💻 Author

**Challa Madhumitha**

SOC Internship – ITSimplera Solutions
