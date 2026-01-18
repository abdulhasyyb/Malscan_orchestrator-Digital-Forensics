# MalScan Orchestrator
## Digital Forensics & Malware Analysis Automation (n8n)

---

## Overview
**MalScan Orchestrator** is a **digital forensics automation workflow** built using **n8n** to orchestrate malware analysis, enrichment, and reporting in a controlled and repeatable manner.

The project automates the end-to-end process of **malware sample submission**, **sandbox analysis**, **threat intelligence enrichment**, and **AI-assisted reporting**, reducing manual effort while maintaining forensic accuracy.

This project was developed as part of an **academic Digital Forensics course**.

You can view project demonstration at:
https://www.linkedin.com/posts/abdul-haseeb-09886b287_cybersecurity-malwareanalysis-threatintelligence-activity-7401738853734068227--zKC?utm_source=share&utm_medium=member_desktop&rcm=ACoAAEW3gLQBj3NU-P3mb3Ss_R5lwz21wIGj_0U

---

## Problem Statement
Manual malware analysis is time-consuming and error-prone, especially when correlating data from multiple sources such as sandboxes and threat intelligence platforms.  
This project demonstrates how **workflow automation** can streamline forensic triage while preserving analyst oversight.

---

## Key Features
- **Automated malware sample submission** via web form  
- **Sandbox-based dynamic analysis orchestration**  
- **Threat intelligence enrichment** using external reputation sources  
- **Triage score extraction and prioritization**  
- **AI-assisted forensic report generation**  
- **Automated alerting for high-risk samples**  
- **Modular and extensible workflow design**

---

## Workflow Architecture
1. Analyst uploads a suspicious file via a form trigger  
2. File is submitted to a sandbox environment for analysis  
3. System waits for sandbox execution to complete  
4. Static and dynamic analysis reports are retrieved  
5. Hash-based enrichment is performed using threat intelligence sources  
6. Reports are merged and pre-processed  
7. AI agent generates a structured malware analysis summary  
8. Alerts and reports are produced for analyst review  

---

## Technologies Used
- **n8n** (Workflow Automation)
- **Sandbox Analysis APIs** (e.g., Triage)
- **Threat Intelligence APIs** (e.g., VirusTotal)
- **JavaScript** (n8n Code Nodes)
- **LLM Integration** (AI-assisted reporting)
- **Webhook & HTTP-based integrations**

---

## Digital Forensics Concepts Applied
- **Malware triage and prioritization**
- **Dynamic behavior analysis**
- **Indicator of Compromise (IOC) extraction**
- **Threat intelligence correlation**
- **Evidence preservation through structured reporting**
- **Automation in forensic workflows**

---

## Project Structure
```text
MalScan-Orchestrator
│
├── workflow/
│   └── malscan-orchestrator.json   # Sanitized n8n workflow
│
├── docs/
│   └── architecture.png            # Workflow diagram (optional)
│
└── README.md
