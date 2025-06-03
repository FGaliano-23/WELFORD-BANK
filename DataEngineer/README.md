# 🗄️ DataEngineer - Welford Bank

This module is part of the **Welford Bank** project and contains all the work carried out by the **Data Engineering team**.  
Its main goal is to **provide high-quality synthetic data**, well-structured and ready to be used by analysis and data science teams.

---

## 📂 Repository Structure

DataEngineer/
├── Database Diagram/
│ └── Diagrama-ERWelfordBank.png
├── GenerateData/ # Dataset en español (_es)
│ ├── Tables.ipynb # Notebook generador
│ └── *.csv
├── GenerateDataEnglish/ # Dataset en inglés (_en)
│ ├── Tables.ipynb
│ └── *.csv
├── SQL/
│ └── SQLiteWelfordBank.sql 
└── _DE_Report_DATAGENERATION.pdf


### Why two data folders?

* **`GenerateData`**: Spanish version, used for local testing.  
* **`GenerateDataEnglish`**: English version (suffix `_en`), used by DS/ML teams.  
Both are generated with the **same seed (`SEED = 15`)** to ensure reproducibility.

---

## 🗄️ Database Schema

<img src="Database Diagram/Diagrama-ERWelfordBank.png" width="500"/>

* 20 tables; the **`clients`** table is the core of the schema.  
* Color-coded by business domain (Clients, Loans, Fraud, Metrics, etc.).

---

## ⚙️ Data Generation

| Metric | Value |
|--------|-------|
| Client records | **25,001** |
| Transaction records | **1,048,576** |
| Loan payment records | **1,048,576** |
| Execution time | **≈ 2 min 37 s** on laptop i7/16 GB RAM |

The `Tables.ipynb` notebook follows this structure:

1. **Parameters and reference lists**  
2. **Helper functions**  
3. **Generation loop**  
4. **DataFrame → CSV** (`<table>_welfordbank_<lang>.csv`)

Main libraries: **pandas, numpy, faker, random, datetime**

---

## 🛠️ SQL Scripts

* **`SQLiteWelfordBank.sql`**  
  * Creates the full schema with all tables.<br>
  * Used to load CSVs into the SQL-generated structure.

---

## 📄 Detailed Report

For more in-depth information, please refer to the **_DE_Report_DATAGENERATION.pdf**, which includes technical documentation, decisions, and limitations of this work.

---

## ▶️ Getting Started

```bash
# 1. Run all notebook cells
# 2. Synthetic data will be generated
``` 
## 👥 DATA ENGINEERING TEAM MEMBERS
- Javier Osuna
- Wail Achalhi
- Francisco Galiano
- Daniela Correa

## 👥 WELFORD BANK TEAM MEMBERS
- Javier Osuna
- Wail Achalhi
- Francisco Galiano
- Daniela Correa
- Elena Sanjuan
- Leyre Verdú