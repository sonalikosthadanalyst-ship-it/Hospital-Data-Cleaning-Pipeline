# Automated Hospital Data Cleaning & Parsing Engine (2026 Q2)

## 🏥 Project Overview
An automated data-engineering script developed in Python to ingest, clean, and transform messy, unstructured raw hospital operational records. This pipeline programmatically resolves deep data inconsistency issues, prepares clean analytical tables, and ensures formal relational structural constraints.

## 🛠️ Automated Processing Logic
* **Library Integration:** Leverages core data science packages including **Pandas** for structural transformation and **NumPy** for complex logic handling.
* **Duplication Management:** Automatically identifies, audits, and drops complex repeated entries based on primary identifier arrays like `Admission_ID`.
* **Anomalous Values Handling:** Scans datasets to detect missing patient metrics (e.g., blank `Patient_Name`) and handles structural null values seamlessly.
* **Data Standardisation:** Re-architects inconsistent time strings into clean, structured ISO datetime objects for downstream databases.

## 🧰 Tech Stack Used
* **Programming Core:** Python 3.x
* **Data Management Frameworks:** Pandas, NumPy
* **Execution Infrastructure:** Google Colab Environment (.ipynb Jupyter Layout)

## 📂 Repository Contents
* `Hospital_Data_Pipeline.ipynb` - The primary production-grade Python notebook containing automated pipeline engine blocks.
