# 🏦 Banking & Transaction Analytics

A hands-on exploratory data analysis (EDA) of retail banking transaction patterns, customer account velocity, and branch-level throughput using Python and Pandas.

---

## 📌 Project Overview
In modern retail banking and fintech, understanding transactional flow and account behaviors is essential for risk management, liquidity planning, and customer retention. 

This project explores a multi-table relational dataset combining customer demographics, account records, transactional logs, and branch metadata. The analysis focuses on understanding daily cash flow dynamics, identifying account activity patterns, and evaluating branch transaction loads.

*(Note: While the core dataset includes loan tables, this initial phase focuses exclusively on transaction, customer, account, and branch mechanics.)*

---

## 🛠️ Tech Stack & Tools
* **Language:** Python 3.x
* **Data Processing & Cleaning:** Pandas, NumPy
* **Data Visualization:** Matplotlib, Seaborn
* **Environment:** Google Colab

---

## 📊 Key Findings & Insights

* **Transaction Velocity & Peak Windows:** Transaction volumes show distinct clustering around specific days of the week and hours of the day, reflecting core retail spending habits and high-throughput liquidity windows.
* **Account Activity Segregation:** Joining customer accounts with transaction logs revealed a clear divide between highly active core accounts driving regular deposit/withdrawal velocity and a cluster of dormant or low-activity accounts.
* **Branch-Level Load Imbalance:** Transactional volume across physical branches is heavily skewed—a small subset of key regional branches processes a disproportionately large share of total daily transactions, signaling potential operational bottlenecks.

---

## 💡 Strategic Recommendations

1. **Targeted Account Re-Engagement:** Deploy automated, data-driven notifications and tailored incentives to re-engage accounts exhibiting prolonged inactivity, reducing churn risk and reactivating dormant balances.
2. **Branch Resource Optimization:** Reallocate customer support staff and technical infrastructure toward top-volume branch hubs to shorten wait times and eliminate transaction delays during peak windows.
3. **Liquidity & Cash Management:** Utilize daily transaction demand curves to optimize ATM replenishment schedules and branch cash reserve limits, ensuring cash flow matches real-world customer usage patterns.

---

## 📁 Repository Structure

```text
banking-portfolio-analysis/
│
├── notebooks/
│   └── Transaction_Risk_Analytics.ipynb   # Main Python analysis notebook
├── images/
│   └── Fintech Project ERD 2026-10-04.jpeg  # ERD For Raw Relational Schema
└── README.md                                # Project documentation
