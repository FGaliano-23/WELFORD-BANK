# 🏦 WELFORD BANK – End-to-End Data Project 🚀

> ℹ️ **Note:** All data included in this repository are **synthetic** and were generated solely for academic and demonstration purposes. They do **not** represent real customer information.

## 📚 Table of Contents
1. [📖 Overview](#overview)  
2. [🗂️ Project Phases](#project-phases)  
3. [📁 Repository Structure](#repository-structure)  
4. [🎉 Contributors](#contributors)  

---

## 📖 Overview
Welford Bank is an **end-to-end** initiative that spans the entire data-lifecycle for a retail-banking scenario:

- 🛠️ **Design** and construction of a relational database  
- 🧪 **Generation** of realistic synthetic data to populate that database  
- 🤖 **Development** of machine-learning models to tackle key business questions  
- 📊 **Creation** of an interactive dashboard and an executive report for leadership  

The goal is to showcase how multidisciplinary teams—**Data Engineering**, **Data Science**, and **Data/BI Analytics**—collaborate in a cohesive workflow.

---

## 🗂️ Project Phases

| 🚩 Phase | 👥 Owner | 📝 Description |
|---------|---------|---------------|
| 1️⃣ Database design | 🛠️ Data Engineers | • Entity-relationship diagram<br>• SQL script (`SQLiteWelfordBank.sql`) that builds the schema in SQLite |
| 2️⃣ Synthetic data generation | 🛠️ Data Engineers | • Notebooks & scripts that produce `CSV` datasets in Spanish (`_es`) and English (`_en`)<br>• Methodology report (`_DE_Report_DATAGENERATION.pdf`) |
| 3️⃣ Predictive modelling | 🤖 Data Scientists | • Models for:<br>&nbsp;&nbsp;• Fraud detection in transactions<br>&nbsp;&nbsp;• Loan-default risk prediction<br>&nbsp;&nbsp;• Customer segmentation<br>• Each model ships with datasets, a notebook, and `requirements.txt` |
| 4️⃣ BI & Dashboard | 📊 Data Analysts | • Dashboard mock-ups, final views, and an executive report<br>• All assets live in `DataAnalyst/` |

---

## 📁 Repository Structure
```text
WELFORD-BANK/
├── DataEngineer/
│   ├── Database Diagram/
│   │   └── Diagrama-ERWelfordBank.png
│   ├── GenerateData/               # CSV files in Spanish + Tables.ipynb
│   ├── GenerateDataEnglish/        # CSV files in English + Tables.ipynb
│   ├── SQL/
│   │   └── SQLiteWelfordBank.sql
│   └── _DE_Report_DATAGENERATION.pdf
│
├── DataScientist/
│   └── Models/
│       ├── Fraud_Detection_in_Banking_Transactions/
│       │   ├── data/*.csv
│       │   ├── notebook/*.ipynb
│       │   └── requirements.txt
│       ├── Loan default risk prediction/
│       └── Segmentation_of_Banking_Customers/
│
├── DataAnalyst/
│   ├── AnalystFinalReport/
│   ├── Dashboard Mockups/
│   └── Final Dashboard/
│
├── Scientific Approach to Data/    # Cross-cutting documentation
├── Documentation.pdf
└── README.md                       # (this file)
```

## 🎉 Contributors

| 🧩 Role | 🙋‍♀️ Team Members |
|---------|-------------------|
| **Data Engineers** 🛠️ | **Boss:** Daniela<br>**Member:** Wail<br>**Assistants:** Javi, Francisco |
| **Data Scientists** 🤖 | **Boss:** Francisco<br>**Member:** Javi<br>**Assistant:** Wail |
| **Data Analysts / BI** 📊 | **Boss:** Leyre<br>**Member:** Elena<br>**Assistant:** Daniela |
