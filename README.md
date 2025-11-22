# 📊 AdvisorInsight: Financial Advisor Dashboard
**Team:** Group 007 | **Status:** Release v1.0

![Build Status](https://img.shields.io/badge/build-passing-brightgreen)
![Version](https://img.shields.io/badge/version-1.0.0-blue)
![Security](https://img.shields.io/badge/security-AES--256-red)

<br />
<div align="center">
  <img src="./assets/Gemini_Generated_Image_tptpjutptpjutptp.png" alt="AdvisorInsight Dashboard Preview" width="100%">
  <p><em>Figure 1: AdvisorInsight Dashboard View</em></p>
</div>
<br />

## 📖 Project Overview
**AdvisorInsight** is a secure, web-based dashboard designed to modernize the workflow of financial advisors. By aggregating client portfolio data, providing real-time risk analysis, and automating reporting, this solution aims to reduce administrative overhead by **40%** and improve client retention.

### 🌟 Key Features (Scope)
* **🔐 Role-Based Access:** Secure login via Auth0 protocols (Admin vs. Advisor).
* **📈 Risk Heatmaps:** Visual representation of portfolio volatility using Chart.js.
* **📄 Automated Reporting:** One-click generation of PDF/Excel reports for client meetings.
* **👥 Client Management:** Searchable database of client assets and performance history.

---

## 🛠️ Technical Architecture
* **Frontend:** React.js (Dashboard Interface)
* **Backend:** Node.js (API Handling)
* **Database:** MongoDB (Client Records)
* **Security:** AES-256 Encryption (Data at Rest) & TLS 1.3 (Data in Transit)

---

## 🚀 Setup Instructions
To run this project locally for development or testing purposes, follow these steps:

### Prerequisites
* Node.js (v14.0 or higher)
* npm (v6.0 or higher)

### Installation Steps
1.  **Clone the repository:**
    ```bash
    git clone [https://github.com/your-username/group-007_advisor-insight.git](https://github.com/your-username/group-007_advisor-insight.git)
    ```
2.  **Navigate to the project directory:**
    ```bash
    cd group-007_advisor-insight
    ```
3.  **Install dependencies:**
    ```bash
    npm install
    ```
4.  **Start the development server:**
    ```bash
    npm start
    ```
5.  **Access the Dashboard:**
    Open your browser and navigate to `http://localhost:3000`.

---

## 📂 Repository Structure
```text
/group-007_advisor-insight
├── /assets            # Project screenshots & static images
├── /config            # Auth0 and Security configurations
├── /src               # Source code for React components
├── /docs              # User Manuals & Wiki
└── README.md          # Project Documentation
