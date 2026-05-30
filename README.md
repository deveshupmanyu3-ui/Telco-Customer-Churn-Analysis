# 📱 Telco Customer Churn Analysis

## 📋 Business Problem
A telecom company is losing 26.5% of its customers annually.
The goal is to identify which customers are most likely to churn,
understand why they leave, and provide actionable recommendations
to improve customer retention.

---

## 🛠️ Tools Used
- **Python** — Data cleaning, analysis, visualization
- **Pandas** — Data manipulation
- **Matplotlib & Seaborn** — Charts and graphs
- **SQL (SQLite)** — Business queries and insights
- **Power BI** — Interactive dashboard

---

## 📂 Project Structure
```
Telco-Customer-Churn-Analysis/
│
├── Telco_Churn_Analysis.ipynb       # Python analysis notebook
├── Telco_Churn_SQL.ipynb            # SQL queries notebook
├── telco_churn_cleaned.csv          # Cleaned dataset
├── churn.db                         # SQLite database
├── telco_churn_analysis.pbix        # Power BI dashboard
├── churn_dashboard_preview.png      # Dashboard screenshot
├── churn_overview.png               # Churned vs stayed chart
├── churn_by_contract.png            # Churn by contract chart
├── churn_by_internet.png            # Churn by internet chart
├── tenure_distribution.png          # Tenure distribution chart
├── monthly_charges_boxplot.png      # Monthly charges chart
├── correlation_heatmap.png          # Correlation heatmap
└── README.md
```

---

## 🔍 Key Findings

### 1. Overall Churn Rate
- 1,869 out of 7,043 customers churned
- Overall churn rate of 26.5% — 1 in 4 customers leaving

### 2. Contract Type is Biggest Driver
- Month-to-month customers churn at 43%
- Two year contract customers churn at only 3%
- Monthly customers churn 15x more than long term customers

### 3. High Value Customers at Risk
- Churned customers paid $74/month vs $61 for loyal customers
- Business is losing its highest paying customers first
- 1,379 high value customers already lost

### 4. First Year is Critical
- 48% of customers churn within first 12 months
- Loyal customers stay average 38 months vs 18 for churned
- Early intervention is the highest impact retention strategy

### 5. Payment Method Matters
- Electronic check users churn at 45%
- Automatic payment users churn at only 15-16%
- Manual payment = 3x higher churn risk

---

## 💡 Business Recommendations

**Recommendation 1 — Push Annual Contracts**
> Month-to-month customers churn at 43% vs 3% for two year contracts.
> Offering 10-15% discount to switch to annual contracts could
> reduce overall churn by 8-10%.

**Recommendation 2 — Promote Auto Payments**
> Electronic check users churn at 45% vs 15% for auto pay users.
> Offering $5 monthly discount for switching to auto pay could
> reduce churn by 5-7%.

**Recommendation 3 — Fix Fiber Optic Value**
> Fiber optic customers churn at 42% despite paying premium prices.
> Reducing pricing or improving service quality would have
> outsized revenue impact.

**Recommendation 4 — First Year Retention Program**
> 48% of customers churn within first 12 months.
> A structured onboarding program with free upgrade in months 1-3
> could cut first year churn in half.

**Recommendation 5 — Retain High Value Customers**
> Customers paying $60+ monthly churn at 33%.
> Proactive retention calls before month 6 could save
> the business's most valuable customers.

---

## 📊 Dashboard Preview
![Churn Dashboard]



---

## 📈 Dataset
- **Source:** Kaggle — IBM Telco Customer Churn Dataset
- **Records:** 7,043 customers
- **Features:** 21 columns
- **Target:** Churn (Yes/No)

---

## 👤 Author
**Devesh Upmanyu**
- LinkedIn: linkedin.com/in/devesh-upmanyu
- Email: youremail@gmail.com
