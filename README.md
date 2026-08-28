# data_science_dashboard

# Data Science Dashboard

A complete end‑to‑end data pipeline and analytics dashboard built with Python, Pandas, SQLite, and Streamlit.

This project demonstrates:
- Data ingestion (CSV → Pandas)
- Data validation and cleaning
- Warehouse modeling (DIM + FACT tables)
- SQLite storage
- JSON export
- Streamlit dashboard visualization
- CLI + Jupyter Notebook compatibility

---

## 📁 Project Structure
data_science_dashboard/
│ dashboard.py
│ pipeline.py
│ requirements.txt
│ data.csv
│ transactions.csv
│ database.db
│ output.json
│ merged_output.json


---

## 🚀 Features

### ✔ ETL Pipeline (`pipeline.py`)
- Loads raw CSV data  
- Validates required fields  
- Cleans missing values  
- Saves cleaned data to:
  - JSON  
  - SQLite (`database.db`)  

### ✔ Data Warehouse
Creates:
- `dim_customer`
- `fact_transactions`
- `customers`
- `customer_transactions`

### ✔ Streamlit Dashboard (`dashboard.py`)
Visualizes:
- Customer spend amounts  
- Cleaned warehouse data  
- Interactive charts  

---


### ✔ ETL Pipeline (`pipeline.py`)
- Loads raw CSV data  
- Validates required fields  
- Cleans missing values  
- Saves cleaned data to:
  - JSON  
  - SQLite (`database.db`)  

### ✔ Data Warehouse
Creates:
- `dim_customer`
- `fact_transactions`
- `customers`
- `customer_transactions`

### ✔ Streamlit Dashboard (`dashboard.py`)
Visualizes:
- Customer spend amounts  
- Cleaned warehouse data  
- Interactive charts  

---

## ▶️ Running the Pipeline## 
Or inside Jupyter Notebook (auto‑configured).
python pipeline.py --input data.csv --output output.json
---

## ▶️ Running the Dashboard
streamlit run dashboard.py
http://localhost:8501

## 📦 Requirements

Install dependencies:
pip install -r requirements.txt

## 🌐 Deploying to Streamlit Cloud

1. Push this repo to GitHub  
2. Go to https://share.streamlit.io  
3. Select:
   - Repo: `data_science_dashboard`
   - Branch: `main`
   - File: `dashboard.py`
4. Deploy

---

## 📜 License

MIT License
