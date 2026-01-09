# Nook_Book_Pt3 simulated incidents and data integrity analysis

## Overview
Nook_Book is a controlled web application developed to study system behavior, data integrity, and forensic investigation techniques. While the application presents as a simple social media–style profile, its underlying purpose is to function as a **test environment for observing and analyzing system anomalies**.

Version 3 introduces **intentional incidents and data integrity violations** into the previously logged system established in Version 2.

---

## Version 3 Purpose
The goals of Version 3 are to:

- Simulate realistic system incidents
- Introduce data and log inconsistencies
- Observe how anomalies manifest in stored records
- Analyze the trustworthiness of system logs
- Prepare data for forensic investigation

This version transitions the project from *observation* to *analysis*.

---

## Simulated Incidents

Version 3 includes **intentional system disruptions**, such as:

- Missing or deleted log entries
- Altered interaction records
- Interactions without corresponding logs
- Logs without matching interaction data
- Timestamp inconsistencies
- Duplicate or malformed entries

All incidents are **artificially introduced** and documented for educational analysis.

---

## System Scope

### Included
- Existing interaction and logging mechanisms
- Manual or scripted data manipulation
- Incident documentation
- Database-level changes

### Excluded (Intentional)
- Incident prevention mechanisms
- Intrusion detection
- Log integrity protection
- Automatic alerting
- Data recovery tools

The system remains intentionally vulnerable to support forensic analysis.

---

## Data Handling

### Interaction Data
- Some records may be altered or removed
- Data integrity is intentionally compromised
- No automatic detection mechanisms exist

### Logging Data
- Logs may be incomplete, modified, or inconsistent
- Logs remain unprotected
- Log reliability is intentionally degraded

These conditions simulate real-world investigative challenges.

---

## Environment & Tools
- Visual Studio Code
- XAMPP
- phpMyAdmin
- SQL command-line or phpMyAdmin query tools

---

## Forensic Focus
Version 3 enables analysis such as:

- Detecting discrepancies between datasets
- Identifying missing or altered records
- Establishing timelines from incomplete data
- Assessing log reliability
- Recognizing indicators of tampering

---

## Planned Transition to Version 4
The datasets produced in Version 3 serve as the evidence base for Version 4, where formal forensic investigation and reporting are performed.

---

## Disclaimer
All incidents in this version are **simulated** and performed in a controlled environment for educational purposes.

