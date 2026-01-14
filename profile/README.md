# Hórus - Solar Energy Management Platform

<div align="center">

![Logo](https://raw.githubusercontent.com/Project-Horus-G9/.github/main/Logo.png)

**A Business Intelligence & Monitoring solution designed to optimize solar farm efficiency through real-time data analysis.**

![Status](https://img.shields.io/badge/Status-Completed-success?style=for-the-badge)
![License](https://img.shields.io/badge/License-MIT-blue?style=for-the-badge)

</div>

---

## ☀️ Project Overview

**Hórus** is an enterprise-grade platform developed to assist solar energy companies in managing photovoltaic production.

The system solves the problem of decentralized data by collecting metrics from solar inverters, processing them through a robust **ETL (Extract, Transform, Load)** pipeline, and presenting actionable insights via intelligent dashboards.

Distinctly, Hórus implements a **Hybrid Cloud Architecture**, leveraging the best services from both **AWS** and **Microsoft Azure** to ensure high availability, redundancy, and cost-efficiency.

### 🚀 Key Features

* **☁️ Hybrid Cloud Infrastructure:** Strategic distribution of services between AWS and Azure for resilience.
* **🔄 Custom ETL Pipeline:** Python-based scripts that ingest raw sensor data, clean it, and load it into the analytical database.
* **📈 Real-Time Dashboards:** Visualization of power generation (kWh), equipment status, and efficiency alerts.
* **🤖 Data Simulator:** A custom Python module developed to simulate IoT sensor data for load testing and system validation before physical deployment.

---

## 🛠️ Tech Stack

We utilized a polyglot approach to handle both high-performance backend processing and data manipulation.

### **Backend & Data Engineering**
<div style="display: inline_block"><br>
  <img src="https://img.shields.io/badge/Java-ED8B00?style=for-the-badge&logo=openjdk&logoColor=white" />
  <img src="https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white" />
  <img src="https://img.shields.io/badge/Spring_Boot-6DB33F?style=for-the-badge&logo=spring-boot&logoColor=white" />
</div>

### **Cloud & Database**
<div style="display: inline_block"><br>
  <img src="https://img.shields.io/badge/Amazon_AWS-232F3E?style=for-the-badge&logo=amazon-aws&logoColor=white" />
  <img src="https://img.shields.io/badge/Microsoft_Azure-0089D6?style=for-the-badge&logo=microsoft-azure&logoColor=white" />
  <img src="https://img.shields.io/badge/SQL_Server-CC2927?style=for-the-badge&logo=microsoft-sql-server&logoColor=white" />
  <img src="https://img.shields.io/badge/MySQL-00000F?style=for-the-badge&logo=mysql&logoColor=white" />
</div>

### **Frontend**
<div style="display: inline_block"><br>
  <img src="https://img.shields.io/badge/JavaScript-323330?style=for-the-badge&logo=javascript&logoColor=F7DF1E" />
  <img src="https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white" />
  <img src="https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white" />
</div>

---

## 🏗️ System Architecture

The architecture was designed to simulate a real-world production environment with high data throughput.

1.  **Data Generation:** A **Python Simulator** generates telemetry data (Voltage, Current, Temperature) mimicking solar inverters.
2.  **Ingestion:** Data is sent to the Cloud API.
3.  **Processing (ETL):** Java and Python services process the incoming streams, validating data integrity.
4.  **Storage:**
    * **AWS:** Used for application hosting and object storage.
    * **Azure:** Used for relational database services (SQL Server).
5.  **Visualization:** The web client consumes processed data to render charts and KPIs for the operations team.

---

## 👥 Development Team

| [<img src="https://avatars.githubusercontent.com/VictorRubinec" width="75"><br><sub>@VictorRubinec</sub>](https://github.com/VictorRubinec) | [<img src="https://avatars.githubusercontent.com/Shift39" width="75"><br><sub>@Shift39</sub>](https://github.com/Shift39) | [<img src="https://avatars.githubusercontent.com/gih-sanchez" width="75"><br><sub>@gih-sanchez</sub>](https://github.com/gih-sanchez) |
| :---: | :---: | :---: |
| [<img src="https://avatars.githubusercontent.com/dianaaugusta" width="75"><br><sub>@dianaaugusta</sub>](https://github.com/dianaaugusta) | [<img src="https://avatars.githubusercontent.com/ViHugo03" width="75"><br><sub>@ViHugo03</sub>](https://github.com/ViHugo03) | [<img src="https://avatars.githubusercontent.com/PedroGustavo000" width="75"><br><sub>@PedroGustavo000</sub>](https://github.com/PedroGustavo000) |

---

<div align="center">
  <sub>Project Hórus © 2024</sub>
</div>
