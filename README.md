# 📊 AI Financial Market Analysis

Exploratory Data Analysis of AI Revenue, R&D Spending, and Stock Market Impact for **OpenAI, Google, and Meta** (2015–2024), built in Python.

📄 [Read the full project report (PDF)](report/AI_Financial_Market_Analysis_Report.pdf)

---

## 🧩 What Problem Did I Solve?

AI companies have poured hundreds of billions of dollars into R&D over the last decade, and investors constantly try to judge whether that spending is paying off — and whether big product launches (ChatGPT, GPT-4, Gemini, LLaMA) actually move the stock market. I used 10 years of daily financial data for OpenAI, Google, and Meta to answer three questions:

- Which company invests the most in AI R&D, and is it converting into revenue?
- Is there a measurable relationship between R&D spending and AI revenue?
- Do major product launches cause noticeable short-term stock swings?

## 🗂️ Dataset Used

| | |
|---|---|
| **File** | `data/ai_financial_market_daily_realistic_synthetic.csv` |
| **Rows** | 10,959 daily records |
| **Period** | Jan 2015 – Dec 2024 |
| **Companies** | OpenAI, Google, Meta |
| **Columns** | `Date`, `Company`, `R&D_Spending_USD_Mn`, `AI_Revenue_USD_Mn`, `AI_Revenue_Growth_%`, `Event`, `Stock_Impact_%` |

This is a realistic synthetic dataset (no missing values), built to simulate daily AI-industry financials and tag real-world product-launch events (e.g. GPT-4 release, Gemini AI release) alongside their stock impact.

## 🛠️ Tools & Libraries

- **Python 3**
- **Pandas** — data cleaning, datetime conversion, groupby aggregations, filtering
- **Matplotlib** — bar charts and time-series line charts
- **Seaborn** — scatter plots, correlation heatmap, pairplot
- **Jupyter / Google Colab** — development environment

## 🔑 Key Findings

📈 Major AI product launches were associated with noticeable stock market reactions, highlighting the impact of innovation on investor sentiment.

📊 Revenue growth accelerated significantly after 2019, reflecting increased adoption and commercialization of AI technologies.

💰 AI revenue growth eventually outpaced R&D spending, suggesting that long-term AI investments can generate substantial returns over time.

## 📈 Charts & Visualizations

**Company-wise R&D Spending vs. AI Revenue ($Bn)**
![R&D vs Revenue by company](charts/01_rd_vs_revenue_by_company.png)

**Stock Impact Over Time (All Companies)**
![Stock impact over time](charts/02_stock_impact_over_time.png)

**Combined R&D Spending and AI Revenue, Year by Year**
![R&D vs revenue trend](charts/05_rd_vs_revenue_trend.png)

**Correlation Between Financial Metrics**
![Correlation heatmap](charts/04_correlation_heatmap.png)

**AI Revenue Growth (%) Over Time by Company**
![Revenue growth scatter](charts/03_revenue_growth_scatter.png)

## 👩‍💻 Author

**Sneha Mandlik**
Fresher Data Analyst | Python | SQL | Power BI | Mumbai

[LinkedIn](https://www.linkedin.com/in/sneha-mandlik-29431b24a/) · [GitHub](https://github.com/SnehaMandlik)

