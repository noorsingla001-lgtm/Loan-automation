# Loan Automation Project 🚀

An automated Loan Automation workflow built with **n8n**. This project handles the entire lifecycle of loan processing—from initial intake and eligibility check to comprehensive risk assessment, final approvals, and instant notifications.

---

## 📋 Table of Contents
* [Features](#-features)
* [Workflow Architecture](#-workflow-architecture)
* [Screenshots & Dashboards](#-screenshots--dashboards)
* [Getting Started](#-getting-started)
* [Technologies Used](#-technologies-used)

---

## ✨ Features
* **Automated Data Intake:** Seamlessly syncs data with data sources like Google Sheets.
* **Risk Assessment Engine:** Categories applications automatically into Low, Medium, or High risk.
* **Real-time Alerts:** Trigger-based instant alerts for immediate team action on high-risk profiles.
* **End-to-End Processing:** Complete workflow automation minimizing manual intervention.

---

## 📐 Workflow Architecture
The backend logic is entirely designed using the n8n visual automation platform, connecting triggers, conditional logic nodes, and messaging protocols natively.

---

## 📸 Screenshots & Dashboards

Here is a visual breakdown of the automation workflow and system components:

### 1. Main n8n Workflow
This is the core automation pipeline mapping the step-by-step logic of the loan processing system.
![n8n Project Workflow](./n8n%20project.png)

### 2. Google Sheet Data Pipeline
The central tracking layer where user submissions are captured and modified dynamically.
![Google Sheet Tracking](./Google%20Sheet.png)

### 3. Risk Assessment Alerts
The system automatically generates specific status flags based on the computed applicant risk level:

| Risk Category | Alert Preview |
| :--- | :--- |
| **Low Risk** | ![Low Risk](./Low%20Risk.jpeg) |
| **Medium Risk** | ![Medium Risk Alert](./Medium%20Risk%20Alert.jpeg) |
| **High Risk** | ![High Risk Alert](./High%20Risk%20Alert.jpeg) |

---

## 🚀 Getting Started

### Prerequisites
* An active [n8n](https://n8n.io/) instance (Cloud or self-hosted).
* A Google Cloud Console account with Google Sheets API enabled.

### Installation & Setup
1. **Clone the repository:**
```bash
   git clone [https://github.com/noorsingla001-lgtm/Loan-automation.git](https://github.com/noorsingla001-lgtm/Loan-automation.git)
