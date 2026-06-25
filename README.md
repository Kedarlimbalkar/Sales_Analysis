# 🚚 FedEx Logistics Performance Analysis

[![Python](https://img.shields.io/badge/Python-3776AB?style=flat&logo=python&logoColor=white)](https://python.org)
[![Pandas](https://img.shields.io/badge/Pandas-150458?style=flat&logo=pandas&logoColor=white)](https://pandas.pydata.org)
[![Matplotlib](https://img.shields.io/badge/Matplotlib-11557c?style=flat&logo=python&logoColor=white)](https://matplotlib.org)
[![Seaborn](https://img.shields.io/badge/Seaborn-4C72B0?style=flat&logo=python&logoColor=white)](https://seaborn.pydata.org)
[![NumPy](https://img.shields.io/badge/NumPy-013243?style=flat&logo=numpy&logoColor=white)](https://numpy.org)

## 📌 Problem Statement

FedEx Logistics operates a vast global supply chain where inefficiencies lead to costly delays and reduced customer satisfaction. This project analyzes a comprehensive dataset of **10,324 shipment records across 43 countries** to identify bottlenecks, evaluate cost-effectiveness of shipment methods, and assess delivery timelines — providing a data-driven framework to streamline supply chain operations.

---

## 🔍 Key Findings

- ✈️ **Air shipments dominate** at 59% of all shipments (6,113 records), but come at higher freight costs
- 🌍 Analyzed delivery performance across **43 countries** with significant regional variation in delays
- 💰 Identified cost outliers in freight pricing across different **Vendor INCO Terms**
- 📦 **ARV products** account for 82.8% of all shipments — a critical category for optimization
- ⏰ Delivery delay patterns uncovered across shipment modes (Air vs Truck vs Ocean vs Air Charter)
- 🏭 Manufacturing site locations correlated with average lead times and freight costs

---

## 🛠️ Tech Stack

| Tool | Purpose |
|------|---------|
| Python | Core programming language |
| Pandas | Data manipulation & cleaning |
| NumPy | Numerical operations |
| Matplotlib | Data visualization |
| Seaborn | Statistical plots |
| Jupyter Notebook | Interactive analysis environment |

---

## 🚀 Quick Start

```bash
# Clone the repository
git clone https://github.com/Kedarlimbalkar/FedEx-Logistics-Performance-Analysis
cd FedEx-Logistics-Performance-Analysis

# Install dependencies
pip install -r requirements.txt

# Launch notebook
jupyter notebook notebooks/FedEx_Logistics_Analysis.ipynb
```

---

## 📁 Folder Structure

```
FedEx-Logistics-Performance-Analysis/
├── data/
│   ├── raw/                          # Original SCMS dataset
│   │   └── SCMS_Delivery_History_Dataset.csv
│   └── processed/                    # Cleaned & transformed data
├── notebooks/
│   └── FedEx_Logistics_Analysis.ipynb  # Main analysis notebook
├── src/                              # Helper Python scripts
├── outputs/                          # Charts and result exports
├── requirements.txt
├── .gitignore
├── LICENSE
└── README.md
```

---

## 📊 Analysis Structure (UBM Framework)

### 1. Univariate Analysis
- Distribution of shipment modes
- Product group frequency
- Freight cost distribution
- Weight distribution

### 2. Bivariate Analysis
- Shipment mode vs freight cost
- Country vs average delivery delay
- Product group vs line item value
- Vendor INCO Term vs cost efficiency

### 3. Multivariate Analysis
- Heatmap of delays by country and shipment mode
- Cost per unit across manufacturing sites
- Delivery performance matrix

---

## 📈 Dataset Overview

| Attribute | Value |
|-----------|-------|
| Total Records | 10,324 |
| Total Features | 33 |
| Countries Covered | 43 |
| Shipment Modes | Air, Truck, Air Charter, Ocean |
| Date Range | Multi-year logistics history |

---

## 💡 Business Recommendations

1. **Optimize Air Shipments** — Renegotiate freight contracts for the 59% air shipments to reduce cost
2. **Vendor Performance Monitoring** — Flag vendors with consistent delivery delays using data-driven thresholds
3. **Route Optimization** — Reroute high-delay country shipments to faster modes where cost-effective
4. **ARV Supply Chain Priority** — Dedicated pipeline for ARV products (82.8% of shipments) to reduce bottlenecks

---

## 👤 Author

**Kedar Limbalkar** — ML Engineer & Data Scientist

[![LinkedIn](https://img.shields.io/badge/LinkedIn-Kedar%20Limbalkar-0A66C2?style=flat&logo=linkedin)](https://linkedin.com/in/kedar-limbalkar)
[![Portfolio](https://img.shields.io/badge/Portfolio-kedarlimbalkar.in-blue?style=flat&logo=globe)](https://kedarlimbalkar.in/)
[![GitHub](https://img.shields.io/badge/GitHub-Kedarlimbalkar-181717?style=flat&logo=github)](https://github.com/Kedarlimbalkar)

---

## 📄 License

This project is licensed under the MIT License — see the [LICENSE](LICENSE) file for details.
