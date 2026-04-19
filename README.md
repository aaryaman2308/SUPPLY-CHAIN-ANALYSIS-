#🔗 End-to-End Supply Chain Analysis Using Python
### Data Analyst Portfolio Project 2026

![Python](https://img.shields.io/badge/Python-3.9+-blue?logo=python)
![Pandas](https://img.shields.io/badge/Pandas-Data%20Analysis-green)
![Scikit-Learn](https://img.shields.io/badge/Scikit--Learn-ML-orange)
![Status](https://img.shields.io/badge/Status-Complete-brightgreen)

---

## 📌 Project Overview

This end-to-end supply chain analysis project demonstrates how a Data Analyst solves **real business problems** using Python. The project covers the full analytics lifecycle — from raw data to machine learning — and produces actionable business recommendations.

> Inspired by the YouTube tutorial: **"End-to-End Supply Chain Analysis Project Using Python | Data Analyst Portfolio Project 2026"** by [Tech Classes](https://www.youtube.com/@TechClasses)

---

## 🏢 Business Context

A consumer goods company operating across **Healthcare, Beauty, Skincare, Haircare, and Cosmetics** categories wants to:

- Identify revenue-generating products and underperforming suppliers
- Detect delivery bottlenecks and root causes of defects
- Predict high-risk products using Machine Learning
- Make data-driven decisions to reduce costs and improve efficiency

---

## 📂 Project Structure

```
supply-chain-analysis/
│
├── 📓 Supply_Chain_Analysis.ipynb   ← Main Jupyter Notebook (full analysis)
├── 🐍 Supply_Chain_Analysis.py      ← Python script version
├── 📊 supply_chain_data.csv         ← Dataset (1000 rows × 27 features)
│
├── outputs/
│   ├── 01_revenue_profit.png        ← Revenue & Profit Distribution
│   ├── 02_sales_defects.png         ← Sales Volume & Defect Rates
│   ├── 03_research_questions.png    ← Research Question Visuals
│   ├── 04_bottlenecks.png           ← Bottleneck Detection
│   ├── 05_root_cause.png            ← Root Cause Analysis
│   ├── 06_time_series.png           ← Monthly Trend Analysis
│   └── 07_ml_results.png            ← ML Model Results
│
├── requirements.txt
└── README.md
```

---

## 🔬 Analysis Sections

| # | Section | Key Techniques |
|---|---------|---------------|
| 1 | Business Problem Understanding | Domain knowledge, KPI definition |
| 2 | Data Loading & First Look | `pd.read_csv()`, `.info()`, `.describe()` |
| 3 | Exploratory Data Analysis | Bar plots, histograms, correlation |
| 4 | Data Cleaning & Feature Engineering | Date parsing, derived metrics, flags |
| 5 | Research Questions | Pivot tables, groupby aggregations |
| 6 | Bottleneck Detection | Fulfillment time analysis, scatter plots |
| 7 | Root Cause Analysis | Defect breakdown, revenue loss estimation |
| 8 | Time Series Analysis | Monthly trends for revenue, orders, defects |
| 9 | Machine Learning | Random Forest, Gradient Boosting, Logistic Regression |
| 10 | Business Insights | Data-driven recommendations table |

---

## 📊 Dataset Features

| Feature | Description |
|---------|-------------|
| Product type | Category (Healthcare, Beauty, etc.) |
| SKU | Stock Keeping Unit ID |
| Supplier name | Supplier A–E |
| Location | City in India |
| Lead time | Expected delivery days |
| Defect rates | Proportion of defective units |
| Inspection results | Pass / Fail |
| Revenue generated | Total revenue per order |
| Transportation costs | Shipping cost |
| Stock levels | Current inventory |
| ... | 27 features total |

---

## 🤖 Machine Learning

**Task:** Binary classification — predict whether a product/order is **High Risk** (defective or fails inspection)

**Models trained:**
- ✅ Random Forest Classifier
- ✅ Gradient Boosting Classifier
- ✅ Logistic Regression (with StandardScaler)

**Evaluation:** Classification Report · Confusion Matrix · ROC-AUC Curve

**Top Predictors:** Defect rates · Revenue generated · Lead time · Manufacturing costs

---

## 💡 Key Business Insights

| Area | Finding | Recommendation |
|------|---------|---------------|
| 📦 Revenue | **Beauty** is the top revenue category | Scale inventory & marketing for Beauty SKUs |
| 🏭 Quality | **Supplier E** has the highest defect rate | Conduct quality audit; enforce SLA penalties |
| 🚚 Logistics | **Road** is the most cost-effective mode | Use Road/Rail for non-urgent bulk orders |
| ⚠️ Risk | 628/1000 products flagged as high-risk | Add pre-shipment QC checkpoints |
| 💸 Loss | ~₹3.85L estimated loss from defects | Invest in defect-reduction programs |
| 📈 ML | Random Forest for risk prediction | Deploy model to flag risky orders pre-dispatch |

---

## 🚀 How to Run

### Option 1: Jupyter Notebook (Recommended)
```bash
# 1. Clone the repo
git clone https://github.com/YOUR_USERNAME/supply-chain-analysis.git
cd supply-chain-analysis

# 2. Install dependencies
pip install -r requirements.txt

# 3. Launch Jupyter
jupyter notebook Supply_Chain_Analysis.ipynb
```

### Option 2: Python Script
```bash
python Supply_Chain_Analysis.py
```

---

## 🛠️ Tech Stack

| Tool | Purpose |
|------|---------|
| **Python 3.9+** | Core programming language |
| **Pandas** | Data manipulation & cleaning |
| **NumPy** | Numerical operations |
| **Matplotlib** | Data visualisation |
| **Seaborn** | Statistical plots |
| **Scikit-Learn** | Machine learning models |
| **Jupyter Notebook** | Interactive analysis |

---

## 📈 Sample Visualisations

> All charts are saved in the `/outputs/` folder after running the notebook.

- Revenue by Product Type (bar chart)
- Defect Rate by Supplier (box plot)
- Bottleneck Detection (scatter plot)
- Monthly Trends (multi-panel time series)
- ROC Curves for all ML models

---

## 👤 Author

**AARYAMAN2308**  
Data Analyst | Python | SQL | Power BI  
🔗 [LinkedIn](https://www.linkedin.com/in/aaryaman-sharma-33b946381/) · 💻 [GitHub](https://github.com/aaryaman2308)

---

## 📄 License

This project is open source under the [MIT License](LICENSE).

---

*⭐ If you found this helpful, please star this repo!*
