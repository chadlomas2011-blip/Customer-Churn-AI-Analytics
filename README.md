# Applied Data, SQL & AI Portfolio Projects

This repository is a collection of independent learning and portfolio projects. It is **not one single customer-churn study**. Notebooks are grouped by subject to make the work easier to review.

## Project index

| Folder / notebook | Focus | Main tools | Data / scope |
|---|---|---|---|
| [Customer Churn Analysis — Synthetic Demonstration](customer-churn-synthetic-demo.ipynb) | Reproducible data audit, EDA, baseline comparison, logistic regression, and model interpretation | Python, Pandas, NumPy, scikit-learn, Matplotlib | 3,000 generated synthetic records; no real customer data |\n| [SQL Customer LTV Analytics](sql/SQL_Customer_LTV_Analytics.ipynb) | Relational queries, customer segments, revenue, average order value, and illustrative LTV | SQLite, Python, Pandas | Small, hard-coded sample dataset |
| [SQL Dashboard](sql/Colab_SQL_Dashboard.ipynb) | SQL aggregation and a regional revenue chart | SQLite, Matplotlib | Five hard-coded sample sales records |
| [Executive Data Visualization Dashboard](visualization/Executive_Data_Visualization_Dashboard.ipynb) | Sales trends, profit comparisons, correlations, and monthly profit contribution | Pandas, Matplotlib, Seaborn | Six months of hard-coded illustrative figures |
| [Web Scraper Market Intelligence](web-scraping/Web_Scraper_Market_Intelligence.ipynb) | Extract book titles, prices, and availability from a demo catalogue | Requests, BeautifulSoup, Pandas, regex | First page of Books to Scrape demo catalogue |
| [LangGraph Autonomous B2B Lead Pipeline](ai-workflows/LangGraph_Autonomous_B2B_Lead_Pipeline.ipynb) | Five-stage lead workflow prototype with simulated tracking | Python, LangGraph, Pandas, CSV, JSON | Sample records and simulated outputs |
| [Construction Industry Lead Loss & Latency Analysis](construction-analytics/Construction_Industry_Lead_Loss_&_Latency_Analysis.ipynb) | Construction-related lead loss and response-latency analysis exercise | See notebook | Inspect notebook for dataset, method, and supported findings |

## Notebooks pending review

- [AI Automated Workflow Pipeline](AI_Automated_Workflow_Pipeline.ipynb) — experimental notebook; inspect code and outputs before relying on claims.
- [Untitled2](Untitled2.ipynb) — filename and purpose need clarification before it can be presented as a featured project.

## Important notes on interpretation

- Several notebooks use **small, hard-coded or illustrative datasets**. Their outputs demonstrate analytical methods; they are not evidence of actual client, employer, or market performance.
- The SQL LTV notebook creates its customer and order tables in memory from sample records. Its dollar amounts are illustrative, not real business revenue.
- The dashboard notebook defines its six-month sales and profit figures directly in code. Its growth and correlation outputs should be understood as demonstrations using illustrative data.
- The web-scraping notebook targets the public Books to Scrape demonstration website and processes the first page of listings. Its output shows 20 products, an average listed price of $38.05, and a range of $13.99–$57.25; these are sample-site observations, not broad market research.
- The lead pipeline is a prototype using sample records and simulated workflow outputs. It does not establish real lead conversions or a production deployment.
- The new customer-churn notebook is explicitly a **synthetic demonstration**, not a real-world churn study. Its generated labels are based on assumptions defined in code. It does not support claims about actual customer churn rates, revenue loss, or business performance. A real-world case study still requires a documented public or authorized dataset.

## Skills demonstrated

Python fundamentals, data wrangling, SQL queries and joins, aggregation, exploratory analysis, data visualization, scikit-learn classification pipelines, model evaluation, web scraping, workflow design, and communicating limitations of synthetic and sample data.

## Running the notebooks

Open a notebook in GitHub or Google Colab. Review the first code and data cells before running. The web scraper requires internet access and retrieves data from the demonstration site at runtime.

## About

Created by Chad Lomas as independent learning and portfolio work. These projects were not paid client engagements.

See [PORTFOLIO_OVERVIEW.md](PORTFOLIO_OVERVIEW.md) for a short overview.
