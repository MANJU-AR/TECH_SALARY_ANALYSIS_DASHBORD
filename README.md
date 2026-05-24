# 📊 Tech Salary Analytics Platform

A complete end-to-end data science pipeline that analyzes compensation trends across 4,500+ tech professionals. The project generates a suite of interactive, browser-based HTML dashboards from a CSV dataset, covering everything from exploratory data analysis to machine learning model training and executive-level reporting.

---

## 🚀 Features

- **30+ Real Visualizations** — Histograms, box plots, violin plots, heatmaps, scatter plots, KDE curves, and more, all embedded as base64 PNGs in self-contained HTML files
- **9 Interactive Dashboards** — Each focused on a specific analytical layer
- **ML Model Development** — Model training, hyperparameter tuning, and prediction generation
- **Deep Insight Mining** — Statistical evidence for salary drivers including location, skills, certifications, and experience
- **Executive Reporting** — KPI summaries and strategic recommendations in a BI-style layout
- **Gender Pay Gap Analysis** — Controlled analysis of compensation equity
- **Financial Profiling** — Savings, expenses, tax rates, and cost-of-living adjustments

---

## 📁 Project Structure

```
.
├── tech_sal.py                  # Main pipeline script
├── tech_salary_dataset.csv      # Input dataset (4,500+ records, 60+ features)
└── output/
    ├── index.html               # Main landing page
    ├── visualizations.html      # 30+ charts dashboard
    ├── eda_dashboard.html       # Exploratory Data Analysis
    ├── feature_analysis.html    # Feature importance & correlation
    ├── statistical_analysis.html# Descriptive & inferential statistics
    ├── model_training.html      # ML model development
    ├── insights.html            # Deep insight mining
    ├── business_insights.html   # Business interpretation layer
    └── executive_dashboard.html # Executive KPI dashboard
```

---

## 🛠️ Tech Stack

| Category | Libraries |
|---|---|
| Data Manipulation | `pandas`, `numpy` |
| Visualization | `matplotlib`, `seaborn` |
| Output Format | HTML (base64-embedded charts) |
| Language | Python 3.x |

---

## ⚙️ Setup & Usage

**1. Clone the repository**
```bash
git clone https://github.com/your-username/tech-salary-analytics.git
cd tech-salary-analytics
```

**2. Install dependencies**
```bash
pip install pandas numpy matplotlib seaborn
```

**3. Add your dataset**

Place `tech_salary_dataset.csv` in the project root. The dataset should include columns such as:
- `annual_salary_usd`, `experience_years_total`, `primary_tech_field`
- `location`, `education_level`, `work_arrangement`, `employment_type`
- `num_skills`, `certifications`, `job_satisfaction_score`
- `monthly_housing_usd`, `monthly_food_usd`, `annual_savings_usd`, etc.

**4. Run the pipeline**
```bash
python tech_sal.py
```

**5. Open the dashboard**

Open `index.html` in your browser to explore all dashboards.

---

## 📊 Dashboards Overview

### 📈 Advanced Visualizations
30+ charts covering salary distributions, tech field comparisons, experience curves, correlation heatmaps, and financial breakdowns.

### 🔍 EDA Dashboard
Univariate, bivariate, and multivariate analysis of all major dataset features.

### 🎯 Feature Intelligence
Feature importance rankings, correlation analysis, and multicollinearity checks.

### 📐 Statistical Intelligence
Descriptive statistics, hypothesis testing, and inferential analysis.

### 🤖 ML Model Development
Model training pipeline with hyperparameter tuning and salary prediction generation.

### 💡 Insight Mining
Key data-driven findings including:
- Location premium (SF/NYC earn 35–45% above average)
- Experience returns (8–12% annual growth for first 8 years)
- Skill multiplier (~$8,500 per additional skill)
- Certification ROI (22% salary premium)
- Gender pay gap (7% after controlling for variables)

### 🏢 Business Interpretation
Non-technical summaries of opportunities, risks, and strategic recommendations.

### 👔 Executive Dashboard
BI-style KPI cards and trend highlights including:
- Average salary: **$165,200** (↑ 5.2% YoY)
- Top 10% salary: **$475K**
- Gender pay gap: **7.2%**
- Remote work adjustment: **-12%**

---

## 📌 Key Insights

- **Top-paying roles**: ML Engineer ($285K), Data Architect ($268K), Cloud Architect ($255K)
- **Top locations**: San Francisco ($245K), New York ($238K), London ($198K)
- **AI/ML roles** are growing 35% YoY and face critical talent shortages
- **Remote-first hiring** can reduce compensation costs by 15–20%
- Professionals at **5–8 years experience** represent the highest flight risk

---

## 🤝 Contributing

Pull requests are welcome. For major changes, please open an issue first to discuss what you'd like to change.

---

## 📄 License

[MIT](LICENSE)
