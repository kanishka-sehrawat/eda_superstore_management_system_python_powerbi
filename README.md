# eda_superstore_management_system_python_powerbi

## SuperStore Management System Analysis
_Analysing store efficiency and profitability to support strategic purchasing and inventory decisions using Python and Power BI._

---

## Table of Contents
- <a href="#overview">Overview</a>
- <a href="#business-problems">Business Problem</a>
- <a href="#dataset">Dataset<a/>
- <a href="#tools--technologies">Tools & Technologies </a>
- <a href="#project-structure">Project Structure</a>
- <a href="#data-cleaning-preparation">Data Cleaning & Preparation</a>
- <a href="#exploratory-data-analysis-eda">Exploratory Data Analysis</a>
- <a href="#research-questions-key-findings">Reasearch Question & Key findings</a>
- <a href="#dashboard">Dashboard</a>
- <a href="#how-to-run-this-project">How to run this project<a/>
- <a href="#final-recommendations">Final Recommandation</a>
- <a href="#author--contact">Author & Contact</a>

---
<h2><a class="anchor" id="overview"></a>Overview</h2>

This project presents an end-to-end analysis of a Superstore Management System using a self-generated dataset. Python was used for data creation, exploratory analysis, and hypothesis testing, while Power BI was used to develop interactive dashboards. The analysis provides actionable insights into sales performance, customer purchasing behavior, pricing strategies, and inventory optimization.

<h2><a class="anchor" id="business-problem"></a>Business Problem</h2>

This project analyzes a Superstore Management System using a self-created dataset to address key challenges in retail sales and inventory management. 

- It identifies underperforming products and categories, evaluates regional and payment-based contributions to revenue and profit, and examines purchasing efficiency.

- The analysis also highlights inventory turnover inefficiencies and applies statistical methods to validate performance differences, enabling data-driven optimization of pricing, sales, and inventory strategies.

<h2><a class="anchor" id="dataset"></a>Dataset</h2>
- A self-generated Excel dataset (.xls) stored in the /data/ folder

- Data was cleaned, transformed, and used to create a summary table for analysis

<h2><a class="anchor" id="tools-technologies"></a>Tools & Technologies</h2>
- Python(Pandas,Numpy,Matplotlib,Seaborn)

- Power BI(Interactive Visualisation)

---
</h2><a class="anchor" id="project-structure"></a>Project Structure</h2>
```
superstore-analysis/
│
├── README.md

├── requirements.txt

│
├── data/
│   └── superstore_data.xls

│
├── notebooks/
│   └── analysis.ipynb

│
├── dashboard/
│   └── superstore_dashboard.pbix

│
└── images/
    └── dashboard_preview.png
```

<h2><a class="anchor" id="data_cleaning-preparation"></a>Data Cleaning & Preparation</h2>
-The dataset was synthetically generated, ensuring controlled data quality with no missing values.

-Standardized data types and addressed outliers to enhance data integrity

-Developed aggregated summary tables across categories, regions, and payment methods to support dashboard insights


<h2><a class="anchor" id="exploratory-data-analysis"></a>Exploratory Data Analysis(EDA)</h2>
The exploratory data analysis (EDA) phase was conducted to understand the structure, patterns, and key relationships within the Superstore dataset. Since the dataset was self-generated, this step also ensured data consistency and realism.

**Data Understanding:**
Examined dataset structure, data types, and key variables such as sales, profit, region, category, and payment method.

**Data Cleaning:**
Checked for missing values, duplicates, and inconsistencies. Ensured correct data types and handled any anomalies.

**Univariate Analysis:**
Analyzed individual features like sales, profit, and order counts to understand their distribution and identify outliers.
**Bivariate & Multivariate Analysis:**

Explored relationships between variables such as:
-Sales vs Profit

-Category vs Profitability

-Region vs Order Volume

-Payment Method vs Transactions

**Key Trends Identified:**

-Certain regions contributed significantly higher sales

-Specific payment methods dominated transaction volume

-Some product categories showed lower profitability despite high sales

**Outlier Detection:**

-Identified extreme values in sales and profit that could impact analysis.

-Feature Insights for Dashboard:

Insights from EDA were used to design Power BI visuals such as KPI cards, regional performance charts, and payment method analysis.

<h2><a class="anchor" id="dashboard"></a>Dashboard</h2>
- Dynamic filtering by region, category, and payment method

- KPI cards highlighting total sales, profit, and top-performing payment method

- Visual analysis of sales and profit across regions and product categories

- Identification of high-performing and underperforming segments

- Insights into purchasing patterns and payment preferences

![Superstore Management Dashboard](

---

###  How to Run This Project

#### 1. Clone the repository

```bash
git clone https://github.com/kanishka-sehrawat/superstore-analysis.git
cd superstore-analysis
```

#### 2. Install required Python libraries

```bash
pip install -r requirements.txt
```

#### 3. Run the analysis

* Open the notebooks in the `notebooks/` folder using Jupyter Notebook or VS Code
* Run all cells to reproduce the analysis and insights

#### 4. View the dashboard

* Open the `.pbix` file from the `dashboard/` folder in Power BI Desktop
* Use filters and visuals to explore insights

---
<h2><a class="anchor" id="final-recommendations"</a>Final Recommendations</h2>
- Focus on promoting high-performing products and regions to maximize revenue
- Re-evaluate pricing or strategy for underperforming products
- Leverage high-usage payment methods to improve customer experience
- Use data-driven insights to guide purchasing and sales decisions

**Kanishka**
Data Analyst











