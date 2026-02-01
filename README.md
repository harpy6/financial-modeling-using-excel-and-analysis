# 📈 Tata Steel Ltd – Financial Forecasting Model

## 📌 Project Overview

This project presents a **financial forecasting model for Tata Steel Ltd**, focusing on key performance indicators such as **Sales, EBITDA, and Earnings Per Share (EPS)**. The model analyzes historical financial data and projects future performance using trend-based forecasting techniques.

The objective is to understand **business cycles, growth trends, and profitability outlook** of Tata Steel over a long-term horizon, making it useful for **students, finance learners, analysts, and academic evaluations**.

---

## 🎯 Objectives

* Analyze historical financial performance of Tata Steel Ltd
* Forecast future **Sales, EBITDA, and EPS**
* Study growth trends, volatility, and recovery patterns
* Understand the impact of economic cycles on steel industry performance
* Build a structured forecasting case study for academic use

---

## 🛠️ Tools & Technologies

* **Microsoft Excel / Spreadsheet Model** (source data)
* **Statistical Trend Analysis**
* **Financial Forecasting Techniques**
* **Charts & Visualizations**
* *(Optional Extension)* Python / NumPy / Pandas

---

## 📊 Data Description

The dataset includes **15 years of financial data**, divided into:

* **Actual Data (A)**: 2016–2025
* **Estimated Data (E)**: 2026–2030

### Key Variables

* **Sales (₹ Crores)**
* **EBITDA (₹ Crores)**
* **Earnings Per Share – EPS (₹)**
* **Year-on-Year Growth (%)**

---

## 📈 Sales Forecasting Analysis

* Sales show **strong growth phases (2019, 2022)** and **decline phases (2020, 2024–25)**
* Significant post-pandemic recovery observed in 2022
* Forecast assumes **stable long-term growth of ~5–6% annually**

**Projected Sales (₹ Cr):**

* 2026E: ~264,071
* 2030E: ~330,572

---

## 📉 EBITDA Forecasting Analysis

* EBITDA reflects **high volatility**, indicating sensitivity to raw material prices and demand cycles
* Peak profitability observed in 2022
* Sharp correction in 2023–24 due to cost pressures
* Forecast indicates **gradual margin normalization**

**Projected EBITDA (₹ Cr):**

* 2026E: ~41,022
* 2030E: ~52,341

---

## 💰 EPS Forecasting Analysis

* EPS shows **extreme fluctuation**, including negative values in early years
* Strong earnings spike in 2022
* Post-2023 moderation reflects cyclical correction
* Forecast assumes **stable earnings recovery** with declining growth rate over time

**Projected EPS (₹):**

* 2026E: ~11.77
* 2030E: ~16.38

---

## 📊 Visualizations Included

* Sales Forecast Trend Chart
* EBITDA Forecast Trend Chart
* EPS Forecast Trend Chart
* Linear trend equations for EPS projection

These charts help visualize **long-term growth direction and volatility patterns**.

---

## ⚠️ Assumptions & Limitations

* Forecasts are based on **historical trends only**
* No macroeconomic, geopolitical, or commodity price shocks considered
* Model does not include balance sheet or cash flow projections
* Results should not be treated as investment advice

---

## 🔮 Future Scope

* Integration with **Python-based time series models (ARIMA, Regression)**
* Scenario analysis (Bull / Base / Bear cases)
* Margin forecasting and cost structure modeling
* Linking financial forecasts with stock valuation models

---

## 👨‍💻 Author

**Prashant Thakur**
Finance & Data Analytics Enthusiast

---

## 📚 Disclaimer

This project is created **strictly for academic and educational purposes**. Forecasts are indicative and should not be used for real-world investment decisions.

---

⭐ *If you found this project useful, consider starring the repository!*



# 📊 DCF & WACC Valuation Model (India Focus)

> **A practical corporate finance project that estimates firm value using Discounted Cash Flow (DCF) and Weighted Average Cost of Capital (WACC), built with real Indian market data.**

---

## 🚀 Project Overview

This project demonstrates a **bottom-up valuation approach** by calculating WACC using peer company analysis and applying it to DCF valuation. It is designed to mirror **real-world equity research and investment banking practices**.

The model uses Indian retail & fashion sector peers to derive beta, capital structure, and cost of capital assumptions.

---

## 🎯 Objectives

* Estimate **Weighted Average Cost of Capital (WACC)** using market-based inputs
* Apply **DCF methodology** to determine intrinsic firm value
* Perform **peer comparison & beta adjustments** (levered and unlevered)
* Understand the impact of **capital structure, tax, and risk premium** on valuation

---

## 🧮 Key Concepts Covered

* Discounted Cash Flow (DCF)
* Weighted Average Cost of Capital (WACC)
* Cost of Equity (CAPM)
* Cost of Debt (After-Tax)
* Levered & Unlevered Beta
* Peer Comparable Analysis
* Capital Structure Optimization

---

## 🏢 Peer Companies Used

* Avenue Supermarts (DMart)
* Trent Ltd
* Vedant Fashions
* Aditya Birla Fashion & Retail
* Metro Brands

> All figures are in **INR**, unless stated otherwise.

---

## 📐 Methodology

### 1️⃣ Cost of Equity (CAPM)

```text
Cost of Equity = Risk-Free Rate + Beta × Equity Risk Premium
```

* Risk-Free Rate: **6.70%**
* Equity Risk Premium: **8.45%**
* Levered Beta (derived): **0.98**
* **Cost of Equity: 14.96%**

---

### 2️⃣ Cost of Debt

* Pre-Tax Cost of Debt: **7.46%**
* Tax Rate: **30%**
* After-Tax Cost of Debt: **5.22%**

---

### 3️⃣ Beta Adjustments

```text
Unlevered Beta = Levered Beta / (1 + (1 − Tax Rate) × Debt/Equity)
Levered Beta   = Unlevered Beta × (1 + (1 − Tax Rate) × Debt/Equity)
```

* Median Unlevered Beta (Peers): **0.95**

---

### 4️⃣ Capital Structure

| Component             | Value       |
| --------------------- | ----------- |
| Total Debt            | ₹1,609 Cr   |
| Market Capitalization | ₹235,270 Cr |
| Debt Weight           | 3.84%       |
| Equity Weight         | 99.32%      |

---

### 5️⃣ WACC Calculation

```text
WACC = (E/V × Cost of Equity) + (D/V × Cost of Debt)
```

✅ **Final WACC: 15.05%**

---

## 📈 Output & Insights

* Shows how **low leverage + high equity weight** increases WACC sensitivity to beta
* Demonstrates the importance of **peer-based beta normalization**
* Suitable for **valuation interviews, finance internships, and equity research roles**

---

## 🛠 Tools & Skills Used

* Corporate Finance & Valuation
* Financial Modeling (DCF & WACC)
* Excel-based Analysis
* Equity Research Techniques
* Ratio & Risk Analysis

---

## 📂 Repository Structure

```text
├── DCF_WACC_Model.xlsx
├── DCF_WACC.pdf
├── Assumptions.md
└── README.md
```

---

## 📌 Assumptions & Notes

* Tax rate considered is the **marginal corporate tax rate**
* Beta calculated using **5-year monthly data**
* Market values used instead of book values

---

## 👤 Author

**Prashant Thakur**
Finance | Valuation | Equity Research

📫 *Feel free to connect for feedback or collaboration.*

---

⭐ If you found this project useful, consider starring the repository!
