# 📊 Customer Behaviour Analysis – End‑to‑End Project

This project analyses customer behaviour using transactional data. The workflow covers **data cleaning & preparation** (Python), **business queries** (PostgreSQL), and an **interactive dashboard** (Power BI).

## 📁 Project Files

| File | Purpose |
|------|---------|
| `customer_analysis.ipynb` | Jupyter notebook – data loading, cleaning, exploratory analysis, and export of cleaned data |
| `customer_behavior.sql` | PostgreSQL queries – business insights (e.g., customer segmentation, sales trends) |
| `customer_behaviour.pbix` | Power BI report – visualises key metrics, customer segments, and revenue drivers |

## 🔁 End‑to‑End Workflow

1. **Run the Jupyter notebook**  
   – Loads raw data  
   – Cleans and prepares the data  
   – Saves output (e.g., `cleaned_data.csv`)

2. **Import cleaned data into PostgreSQL**  
   – Use the exported CSV to populate a table  
   – Execute `queries.sql` to generate business insights

3. **Open the Power BI dashboard**  
   – Connect to the PostgreSQL database (or use the cleaned CSV)  
   – Explore dashboards like RFM segmentation, revenue trends, and customer profiles

## 🛠️ Tools Used

- **Python** (pandas, numpy, matplotlib/seaborn) – within the Jupyter notebook  
- **PostgreSQL** – for structured querying  
- **Power BI** – for visualisation and reporting

## 🚀 Quick Start

```bash
# Clone the repository
git clone https://github.com/kasmya/Customer-Behaviour-Analysis.git
cd Customer-Behaviour-Analysis

# Install Python dependencies (if any)
pip install pandas numpy matplotlib seaborn

# Run the notebook
jupyter notebook analysis.ipynb

# Then:
# - Import cleaned_data.csv into PostgreSQL
# - Run queries.sql
# - Open dashboard.pbix in Power BI Desktop
