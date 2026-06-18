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

1. **Google leads at scale.** Google accumulated ~$423Bn in AI R&D spend and ~$284Bn in AI revenue over the decade — more than 4x OpenAI's totals — while Meta sits in between (~$265Bn spent / ~$190Bn earned).
2. **R&D spend and AI revenue are strongly correlated (r ≈ 0.94).** Year-over-year totals rose almost in lockstep industry-wide, from ~$49Bn spent / ~$19Bn earned in 2015 to ~$99Bn spent / ~$96Bn earned in 2024.
3. **Product launches move the stock far more than steady growth does.** The five biggest single-day stock impacts in the dataset were all OpenAI launch events — the predicted GPT-5 release (+18.5%), GPT-4 (+15.2%), and the ChatGPT/GPT-3.5 launch (+12.0%) among them — showing announcement-driven volatility dominates short-term price moves.

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

## 📁 Project Structure

```
ai-financial-market-analysis/
├── README.md
├── requirements.txt
├── AI_Financial_Market_Analysis.ipynb
├── data/
│   └── ai_financial_market_daily_realistic_synthetic.csv
├── charts/
│   └── (chart images used in this README)
└── report/
    └── AI_Financial_Market_Analysis_Report.pdf
```

## 👩‍💻 Author

**Sneha Mandlik**
Fresher Data Analyst | Python | SQL | Power BI | Mumbai

[LinkedIn](www.linkedin.com/in/sneha-mandlik-29431b24a) · [GitHub](https://github.com/SnehaMandlik)

## 📄 License

This project is licensed under the [MIT License](LICENSE).
