# jupyter-notebook---Superstore-Retail-Data-Analysis

A comprehensive data analytics project focused on evaluating business performance, seasonal sales trends, regional profitability, and customer value metrics using Python.

## 📌 Project Overview
This project analyzes retail sales data to uncover key operational insights. It evaluates historical growth, isolates seasonal spikes, highlights underperforming regional markets, and groups customers using Recency, Frequency, and Monetary (RFM) modeling to optimize marketing strategies.

---

## 📊 Key Insights & Visualizations

### 1. Trend & Seasonality Analysis
<img width="1389" height="536" alt="Screenshot 2026-08-20 163417" src="https://github.com/user-attachments/assets/d57aec59-660e-4654-8274-3dbfbd916dea" />

* **Time-Series Growth**: Tracking monthly sales from 2014 to 2018 highlights strong cyclical patterns, with dramatic transaction spikes occurring at the end of each fiscal year.
* **Monthly Aggregation**: Consolidating performance by month shows a massive surge in sales during Q4 (specifically September, November, and December), indicating high holiday-season dependency.

### 2. Regional Performance & Profitability
<img width="737" height="636" alt="Screenshot 2026-08-20 163509" src="https://github.com/user-attachments/assets/fe4f9567-0e23-495e-9377-e88d9ce37f66" />

* **The East Region**: An evaluation of the Eastern market reveals high sales volumes but localized profit leaks.
* **Profit Outliers**: While New York drives the highest sales and profit, states like **Pennsylvania** and **Ohio** generate significant revenue but operate at a net loss.

### 3. Correlation Matrix
<img width="354" height="161" alt="Screenshot 2026-08-20 163528" src="https://github.com/user-attachments/assets/107e92a0-a7af-4474-b5aa-901863f63837" />

* **Sales vs. Profit**: Features a moderate positive correlation (~0.48), showing that expanding volume generally drives profit.
* **Discount Impact**: Shows a negative correlation with profitability (~ -0.22), confirming that aggressive discounting strategies directly harm net margins.

### 4. RFM Customer Segmentation
<img width="391" height="497" alt="Screenshot 2026-08-20 163546" src="https://github.com/user-attachments/assets/13a4ba84-8680-40ec-8468-d3ffb8ed833d" />

* **High-Value Champions**: Identified top tier clients (e.g., `SM-20320`, `TC-20980`) contributing over \$19,000+ in revenue with frequent purchases.
* **Dormant/Low-Value Accounts**: Isolated inactive accounts (e.g., `LD-16855`, `TS-21085`) with negligible monetary contributions and high recency days, marking them for re-engagement or removal.

---

## 🛠️ Tech Stack & Libraries
* **Language**: Python 3.9
* **Environment**: Anaconda / Jupyter Notebook
* **Data Manipulation**: Pandas, NumPy
* **Data Visualization**: Matplotlib, Seaborn

---

## 📂 Project Structure
```text
├── data/
│   └── superstore_dataset.csv     # Raw retail dataset
├── notebooks/
│   └── sales_analysis.ipynb       # Core Jupyter notebook with code & plots
└── README.md                      # Project documentation
```

---

## 🚀 How to Run the Project

### Prerequisites
Ensure you have **Anaconda** installed on your system.

### Step-by-Step Setup

1. **Clone the Repository**
   ```bash
   git clone https://github.com
   cd superstore-data-analysis
   ```

2. **Create and Activate a Virtual Environment**
   ```bash
   conda create --name superstore-env python=3.9
   conda activate superstore-env
   ```

3. **Launch the Notebook**
   ```bash
   jupyter notebook notebooks/sales_analysis.ipynb
   ```

---

## 💡 Strategic Recommendations
* **Optimize Q4 Supply Chain**: Scale up inventory and logistics starting in August to seamlessly handle the massive Q4 demand spike.
* **Reconsider Eastern Discounting**: Audit pricing structures in Pennsylvania and Ohio to find out why high sales are leading to negative profits.
* **Targeted Marketing**: Deploy exclusive loyalty perks to the top RFM tier while testing budget-friendly email win-back campaigns for dormant users.
