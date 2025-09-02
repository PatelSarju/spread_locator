# 📊 Probability Distributions & Transaction Data Analysis

## 🎯 Objective
Apply concepts of **probability distributions** and **spread analysis** on an e-commerce transaction dataset to derive insights into customer purchase behaviors.

## 🛒 Project Scenario
You are a data analyst for an **e-commerce platform** tasked with analyzing **daily transaction amounts** to:  
- 🔍 Check if data follows known distributions  
- 📉 Handle skewed data with transformations  
- 📊 Derive probability-based insights for decision-making  

## 🗂 Dataset Structure
| 🏷 Field Name       | 🧾 Data Type   | 📖 Description                                |
|---------------------|----------------|-----------------------------------------------|
| 🆔 transaction_id   | UUID/String    | Unique identifier for each transaction        |
| 👤 customer_id      | UUID/String    | Unique identifier for each customer           |
| 💰 transaction_amount | Float        | Total transaction amount (₹)                  |
| 📅 transaction_date | Date           | Date of the transaction                       |
| 🔢 transaction_count| Int            | Weekly transactions per customer              |
| 🌍 region           | String         | Customer region (North, South, East, West)    |
| ✅ transaction_status | String       | Success/Fail                                  |

## 📝 Task Checklist
### 📖 Part A – Theoretical Notes
- 📚 Statistical Distributions  
- 📐 Q-Q Plots  
- ⚖️ Discrete vs Continuous Distributions  
- 🎲 Bernoulli, Binomial, Log-Normal, Power Law, Poisson  
- 🔄 Box-Cox Transform  
- 📏 Z-scores, PDF & CDF  

### 💻 Part B – Data Analysis (Python: NumPy, Pandas, SciPy, Statsmodels, Matplotlib, Seaborn)
1. 🎲 Fit data to Bernoulli & Binomial distributions  
2. 🔢 Apply Poisson distribution (transactions/day)  
3. 📉 Model amounts with Log-Normal & Power Law  
4. 📐 Generate & interpret **Q-Q plots**  
5. 🔄 Apply **Box-Cox Transform** for variance stabilization  
6. 📏 Compute **Z-scores** & probability of transactions > ₹5000  
7. 📊 Plot & interpret **PDF** and **CDF**  
8. 🏆 Conclude best-fit distribution & insights  

---
🚀 *This project demonstrates practical application of statistical distribution concepts on real-world e-commerce data.*
