# Applied Data, SQL & AI Portfolio Projects

This repository is a collection of independent learning and portfolio projects. It is **not one single customer-churn study**. The notebooks cover SQL analysis, data visualization, web scraping, NLP/workflow experiments, and a B2B lead-pipeline prototype.

I am building on formal training in the Google Data Analytics Professional Certificate and Applied Python for Data Science and AI.

## Project index

| Notebook | Focus | Main tools | Data / scope |
|---|---|---|---|
| [SQL Customer LTV Analytics](SQL_Customer_LTV_Analytics.ipynb) | Relational queries, customer segments, revenue, average order value, and illustrative LTV | SQLite, Python, Pandas | Small, hard-coded sample dataset |
| [SQL Dashboard](Colab_SQL_Dashboard.ipynb) | SQL aggregation and a regional revenue chart | SQLite, Matplotlib | Five hard-coded sample sales records |
| [Executive Data Visualization Dashboard](Executive_Data_Visualization_Dashboard.ipynb) | Sales trends, profit comparisons, correlations, and monthly profit contribution | Pandas, Matplotlib, Seaborn | Six months of hard-coded illustrative figures |
| [Web Scraper Market Intelligence](Web_Scraper_Market_Intelligence.ipynb) | Extract book titles, prices, and availability from a demo catalogue; summarize and export results | Requests, BeautifulSoup, Pandas, regex | First page of Books to Scrape demo catalogue |
| [AI Automated Workflow Pipeline](AI_Automated_Workflow_Pipeline.ipynb) | AI-assisted workflow / text-processing experiment | Python; inspect notebook for full dependencies | Experimental notebook; review code and outputs before relying on claims |
| [LangGraph Autonomous B2B Lead Pipeline](LangGraph_Autonomous_B2B_Lead_Pipeline.ipynb) | Five-stage lead workflow prototype: discovery, enrichment, qualification, outreach drafting, and simulated tracking | Python, LangGraph, Pandas, CSV, JSON | Sample records and simulated outputs |
| [Construction Industry Lead Loss & Latency Analysis](Construction_Industry_Lead_Loss_%26_Latency_Analysis.ipynb) | Construction-related lead loss and response-latency analysis exercise | See notebook | Inspect notebook for dataset, method, and supported findings |

## Important notes on interpretation

- Several notebooks use **small, hard-coded or illustrative datasets**. Their outputs demonstrate analytical methods; they are not evidence of actual client, employer, or market performance.
- The SQL LTV notebook creates its customer and order tables in memory from sample records. Its dollar amounts are illustrative, not real business revenue.
- The dashboard notebook defines its six-month sales and profit figures directly in code. Its growth and correlation outputs should be understood as demonstrations using illustrative data.
- The web-scraping notebook targets the public Books to Scrape demonstration website and processes the first page of listings. The recorded sample output shows 20 products, an average listed price of $38.05, and a range of $13.99–$57.25; these are sample-site observations, not broad market research.
- The lead pipeline is a prototype using sample records and simulated workflow outputs. It does not establish real lead conversions or a production deployment.
- This repository does **not currently provide a verified customer-churn dataset/notebook supporting the previously stated churn rates or revenue-loss estimates**. Those figures have therefore been removed rather than repeated without evidence.

## Skills demonstrated

Python fundamentals, data wrangling, SQL queries and joins, aggregation, exploratory analysis, data visualization, web scraping, text processing, workflow design, and communicating limitations of sample data.

## Running the notebooks

Open a notebook in GitHub or Google Colab. Review the first code and data cells before running. The web scraper requires internet access and retrieves data from the demonstration site at runtime.

## About

Created by Chad Lomas as independent learning and portfolio work. These projects were not paid client engagements.
