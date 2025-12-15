# 🛍️ Customer Shopping Behavior Analysis – Retail Analytics

_Analyzing customer purchase behavior to identify buying patterns, customer segments, and revenue drivers using PostgreSQL, Python, and Power BI._

---

## 📌 Table of Contents
- <a href="#overview">Overview</a>
- <a href="#business-problem">Business Problem</a>
- <a href="#dataset">Dataset</a>
- <a href="#tools--technologies">Tools & Technologies</a>
- <a href="#project-structure">Project Structure</a>
- <a href="#data-cleaning--preparation">Data Cleaning & Preparation</a>
- <a href="#exploratory-data-analysis-eda">Exploratory Data Analysis (EDA)</a>
- <a href="#research-questions--key-findings">Research Questions & Key Findings</a>
- <a href="#dashboard">Dashboard</a>
- <a href="#how-to-run-this-project">How to Run This Project</a>
- <a href="#final-recommendations">Final Recommendations</a>
- <a href="#author--contact">Author & Contact</a>

---
<h2><a class="anchor" id="overview"></a>Overview</h2>

This project analyzes retail customer shopping behavior using transactional data to understand purchasing patterns, discount usage, customer segmentation, and subscription impact. An end-to-end analytics workflow was implemented using PostgreSQL for querying, Python for analysis, and Power BI for visualization.

---
<h2><a class="anchor" id="business-problem"></a>Business Problem</h2>

Retail businesses need deeper visibility into customer behavior to improve sales and retention. This project aims to:
- Identify high-value customer segments
- Understand discount-driven purchasing behavior
- Compare subscriber vs non-subscriber spending
- Analyze revenue contribution across age groups and product categories

---
<h2><a class="anchor" id="dataset"></a>Dataset</h2>

- Retail customer transaction dataset
- **3,900 purchase records** across multiple product categories
- Key fields include:
  - Customer demographics (Age, Gender, Location, Subscription Status)
  - Purchase details (Item, Category, Purchase Amount, Season)
  - Behavioral data (Discount Applied, Review Rating, Shipping Type)

---
<h2><a class="anchor" id="tools--technologies"></a>Tools & Technologies</h2>

- PostgreSQL (CTEs, Joins, Aggregations)
- Python (Pandas)
- Power BI (Interactive Dashboards)
- GitHub

---
<h2><a class="anchor" id="project-structure"></a>Project Structure</h2>

```
customer-shopping-behavior-analysis/
│
├── README.md
├── data/
│   ├── raw/
│   └── processed/
├── sql/
│   └── customer_analysis_queries.sql
├── notebooks/
│   ├── data_cleaning.ipynb
│   └── exploratory_data_analysis.ipynb
├── dashboard/
│   └── customer_shopping_dashboard.pbix
├── reports/
│   └── Customer_Shopping_Behavior_Analysis_Report.pdf
└── docs/
    ├── problem_statement.pdf
    └── presentation.pptx
```

---
<h2><a class="anchor" id="data-cleaning--preparation"></a>Data Cleaning & Preparation</h2>

- Handled missing review ratings using median imputation by category
- Standardized column names for consistency
- Created derived features such as age groups and purchase frequency
- Removed redundant promotional columns
- Loaded cleaned data into PostgreSQL for analysis

---
<h2><a class="anchor" id="exploratory-data-analysis-eda"></a>Exploratory Data Analysis (EDA)</h2>

- Identified spending patterns across demographics
- Analyzed discount usage by product category
- Compared subscriber vs non-subscriber behavior
- Evaluated repeat purchase trends

---
<h2><a class="anchor" id="research-questions--key-findings"></a>Research Questions & Key Findings</h2>

1. **Customer Segmentation**: Majority customers classified as non-subscribers
2. **Subscription Impact**: Subscribers show higher average purchase value
3. **Discount Dependency**: Identified products with high discount reliance
4. **Revenue Contribution**: Revenue concentrated among specific age groups
5. **Shipping Behavior**: Express shipping users spend more on average

---
<h2><a class="anchor" id="dashboard"></a>Dashboard</h2>

- Power BI Dashboard shows:
  - Revenue by category and age group
  - Subscription vs non-subscription split
  - Customer segments and purchase trends
  - Discount-driven product performance

![Customer Shopping Dashboard](images/dashboard.png)

---
<h2><a class="anchor" id="how-to-run-this-project"></a>How to Run This Project</h2>

1. Clone the repository:
```bash
git clone https://github.com/guptaakshay252/Customer-Shopping-Behavior-Analysis-Retail-Analytics-PostgreSQL-Python-Power-BI
```

2. Load data into PostgreSQL:
```bash
python scripts/load_data_postgres.py
```

3. Run analysis notebooks:
- `notebooks/data_cleaning.ipynb`
- `notebooks/exploratory_data_analysis.ipynb`

4. Open Power BI dashboard:
- `dashboard/customer_shopping_dashboard.pbix`

---
<h2><a class="anchor" id="final-recommendations"></a>Final Recommendations</h2>

- Promote subscriptions to increase repeat purchases
- Optimize discount strategy to reduce dependency
- Focus marketing on high-revenue age groups
- Use segmentation for personalized campaigns

---
<h2><a class="anchor" id="author--contact"></a>Author & Contact</h2>

**Akshay Gupta**  
Data Analyst  
📧 Email: guptaakshay0020@gmail.com  
🔗 LinkedIn: https://www.linkedin.com/in/akshay-gupta-185569335/
