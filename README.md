# Customer-Churn-AI-Analytics
​📊 Customer Feedback & Churn Intelligence Engine
​Business Problem
An online subscription provider was losing customers (churning), but management didn't know whether the driver was pricing, service quality, or customer support.
​Key Results & Business Impact
​Analyzed 7,043 customer records to identify key churn drivers.
​Found an overall churn rate of 26.5%, resulting in $139,000+ in lost monthly revenue.
​Built an automated Python text-classification script that categorized customer complaints into Billing, Technical, or Support categories.
​Tools Used
​Data Cleaning & Analysis: Python (Pandas, NumPy), Google Colab
​AI / Sentiment Analysis: Python (Text Parsing Rules / LLM API)
​Data Visualization: Google Looker Studio
​Key Insights & Recommendations
​Month-to-Month Contracts: Customers on month-to-month plans had a 42% churn rate compared to under 11% for annual plans. Recommendation: Offer a 15% discount incentive to convert month-to-month users to annual plans.
​Fiber Optic Issues: Fiber optic subscribers experienced higher churn due to initial setup confusion. Recommendation: Implement automated onboarding check-in emails during week 1.
# 📊 Customer Feedback & Churn Intelligence Engine

## Business Overview
An online subscription business was experiencing high customer churn, leading to significant monthly revenue loss. Management needed visibility into overall churn rates, revenue impact, and automated categorisation of customer feedback to address root causes.

## Key Results & Business Metrics
* **Total Customers Analyzed:** 1,000 active customer records
* **Overall Churn Rate:** 26.30%
* **Monthly Revenue Lost:** $17,000+ per month
* **AI Sentiment Engine:** Built an automated Python text-classification model that categorized customer feedback into **Billing & Pricing**, **Technical Issues**, and **Customer Support**.

## Tech Stack & Tools
* **Language:** Python (`pandas`, `numpy`)
* **Environment:** Google Colab (Mobile Cloud Execution)
* **AI & Analytics Methods:** Data Wrangling, Descriptive Analytics, Rule-Based Natural Language Processing (NLP)

## Key Business Recommendations
1. **Billing Interventions:** Address the ~35% of customer complaints tied to unexpected price hikes by introducing automated billing alerts prior to contract renewals.
2. **Technical Support Escalation:** Wi-Fi speed and stability issues account for high churn intent; flag recurring drops for prioritized tier-2 tech support.# 🕸️ Automated Web Scraper & Market Intelligence Engine

## Project Overview
Built an automated Python web-scraping and data extraction pipeline using `BeautifulSoup` and `requests`. The engine parses raw HTML from live e-commerce listings, cleans unstructured text into numerical data using regex, and calculates key pricing and inventory analytics.

## Key Scraped Market Metrics
* **Total Products Analyzed:** 20 live product listings
* **Average Market Price:** $38.05
* **Price Range:** $13.99 – $57.25

## Tech Stack
* **Language:** Python (`pandas`, `BeautifulSoup`, `requests`, `re`)
* **Environment:** Google Colab
* **Data Processing:** HTML Parsing, String Cleaning, Regular Expressions (Regex), Descriptive Analytics

## Strategic Business Value
Demonstrates automated market research capability—enabling businesses to track competitor pricing, product availability, and positioning in real time without manual data collection.

# 🤖 Automated AI Workflow & NLP Intent Classifier

## Project Overview
Built an automated natural language processing (NLP) workflow pipeline using Python and Hugging Face Transformers (`facebook/bart-large-mnli`). The pipeline ingests unstructured customer tickets, performs zero-shot classification to categorize intent and urgency, calculates confidence scores, and structures the output for automated downstream routing.

## Key Workflow Results
* **Processing Capabilities:** Zero-shot multi-class intent classification without model retraining
* **Classification Categories:** Urgent Escalation, Billing Inquiry, Technical Issue, General Feedback
* **Accuracy Metrics:** High-confidence routing across sample inbound tickets

## Tech Stack
* **Language:** Python (`pandas`, `transformers`, `torch`)
* **AI Architecture:** Zero-Shot Natural Language Processing (BART Large MNLI Transformer)
* **Environment:** Google Colab

## Strategic Business Value
Reduces manual support triaging time by dynamically categorizing inbound requests in real time, allowing critical technical and billing escalations to reach support teams instantly.# 📊 Relational SQL Database & Customer Lifetime Value (LTV) Analytics Engine

## Project Overview
Engineered a relational SQL database schema in Python (`sqlite3`) to model multi-table customer purchasing behavior. Executed advanced SQL queries utilizing table joins, aggregation functions (`SUM`, `AVG`, `COUNT DISTINCT`), and custom mathematical metrics to extract Customer Lifetime Value (LTV) across distinct customer segments.

## Key Market & Financial Findings
* **Enterprise Segment:** Generated highest total revenue ($6,000.00) with a $3,000.00 LTV across 2 core enterprise accounts.
* **SMB Segment:** Recorded high transaction frequency across 2 clients with an Average Order Value (AOV) of $333.33.
* **Consumer Segment:** Lowest overall retention; identified as prime target for automated re-engagement workflows.

## Tech Stack
* **Language:** SQL (SQLite Dialect), Python (`sqlite3`, `pandas`)
* **Database Concepts:** Relational Schema Design, Foreign Keys, `JOIN` Operations, `GROUP BY` Aggregations, Window Functions
* **Environment:** Google Colab

## Strategic Business Value
Enables executive decision-makers to identify top-tier customer cohorts, optimize acquisition spend, and target high-LTV market segments without relying on manual reporting tools.# 📈 Executive Business Intelligence & Data Visualization Dashboard

## Project Overview
Engineered an automated data visualization engine in Python (`matplotlib`, `seaborn`, `pandas`) to transform multi-divisional financial and sales metrics into an executive-ready dashboard. Generated line charts, comparative bar graphs, correlation heatmaps, and profit contribution breakdowns to enable rapid, data-driven decision-making.

## Key Insights Captured
* **Growth Trajectory:** Technology Sales grew by 116% from Jan ($12K) to Jun ($26K), outperforming Services growth.
* **Profit Margin Correlation:** Strong positive correlation (0.98+) identified between sales volume and divisional profit margin across both lines.
* **Peak Revenue Month:** June delivered the highest overall profit contribution (22.5% of total Q1/Q2 profit).

## Tech Stack
* **Language:** Python (`pandas`, `matplotlib`, `seaborn`)
* **Visualization Tools:** Multi-panel Subplots, Heatmaps, Trend Line Charts, Bar Plots, Pie Charts
* **Environment:** Google Colab

## Business Impact
Eliminates manual reporting overhead by instantly rendering publication-grade visual summaries for executive stakeholders.


