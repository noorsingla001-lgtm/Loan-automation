# Loan Automation System 🏦🤖

An automated Loan Automation workflow built with **n8n**. This project streamlines the entire loan lifecycle, including intake, eligibility checks, risk assessment, approval processing, and automated notifications.

---

## 📋 Table of Contents
- [Features](#-features)
- [Project Structure](#-project-structure)
- [Tech Stack](#-tech-stack)
- [Getting Started](#-getting-started)
- [Workflow Previews](#-workflow-previews)
- [License](#-license)

---

## ✨ Features

*   **Automated Intake:** Seamlessly captures loan application data.
*   **Dynamic Risk Assessment:** Categorizes applicants into Low, Medium, and High-risk brackets.
*   **Data Management:** Automatically updates and tracks applicant information via Google Sheets.
*   **Instant Notifications:** Sends automated alerts and updates based on the application's risk evaluation and approval status.

---

## 📁 Project Structure

Based on the repository files, the project includes the following assets:
*   `loan automation` - The core n8n workflow file/configuration.
*   `n8n project.png` - Visual overview of the completed n8n workflow graph.
*   `Google Sheet.png` - Preview of the database/spreadsheet used for tracking applications.
*   `Low Risk.jpeg` / `Medium Risk Alert.jpeg` / `High Risk Alert.jpeg` - Screenshots demonstrating the automated alerting mechanism for different risk tiers.

---

## 🛠️ Tech Stack

*   **Automation Engine:** [n8n.io](https://n8n.io/)
*   **Database/Storage:** Google Sheets
*   **Communication:** Email / Webhooks / Notification Service (as configured in your n8n workflow)

---

## 🚀 Getting Started

### Prerequisites
1. An active instance of **n8n** (Self-hosted or n8n Cloud).
2. A Google account with access to Google Sheets.

### Installation & Setup
1. **Clone the repository:**
```bash
   git clone [https://github.com/noorsingla001-lgtm/Loan-automation.git](https://github.com/noorsingla001-lgtm/Loan-automation.git)
