# 🏘️ US-Real-Estate-Market-Analysis
This project explores **profitable real estate investment opportunities in the U.S. housing market** using Zillow's publicly available housing data. **With a $12 million investment budget, our goal is to identify the best U.S. regions for purchasing, upgrading, and renting or selling single-family homes or rental apartments.**

## 📌 Project Overview

This repository highlights my contribution to a collaborative real estate investment analysis project. The objective was to assess the U.S. real estate market using Zillow’s publicly available housing data and provide data-driven recommendations on where and how to invest **$12 million** for optimal returns.

Each team member individually analyzed a specific question related to real estate trends and investment decisions. I focused on:

- **Q2: Are sale prices and inventory listings going up or down in the U.S.?**
- **Q5: What profit can be expected from property sales after paying the mortgage? (Sale ROI)**
- **Q6: What monthly income can be expected from rental properties after expenses? (Rental ROI)**

This repository contains my **code, visualizations, and conclusions** for these questions including other members analysis on thier questions, presented in a Jupyter Notebook format using Python and Zillow datasets.

## 🔍 My Contributions

### 🏠 Q2: Are Sale Prices and Inventory Listings Going Up or Down?

#### 🔎 Key Findings:
- **Median Sale Price** (as of March 2025): $356,140 (+3.23% YoY)
  - Indicates continued demand and moderate appreciation.
- **Inventory Listings**: Up by **+17.69%** from the previous year.
  - Suggests increased supply, possibly due to sellers capitalizing on high prices.
  
#### 📌 Conclusion:
- The U.S. housing market remains **robust** but may be entering a **cooling phase**.
- Investors face a **more competitive but opportunity-rich environment**.
- It’s crucial to monitor local shifts to anticipate price stabilization or surges.

---

### 💰 Q5: Sale-Based ROI After Paying Mortgage

In this section, I developed a financial model to estimate profits from buying, upgrading, and selling properties.

#### 🧮 My Approach:
- Estimated mortgage payments (30-year fixed @ 6.5% interest).
- Modeled appreciation over 5 years.
- Included upgrade costs and selling fees.
- Focused on regions like **Niles, MI** and **Lebanon, PA**.

#### 📌 Conclusion:
- Short-term investments (1–2 years) in select markets can still yield **positive ROI**.
- Must avoid regions with **high property taxes or flat price trends**.
- Regular monitoring of mortgage rates and market shifts is essential.

---

### 📈 Q6: Rental Income ROI After Mortgage & Expenses

I evaluated **net rental returns** after considering mortgage, taxes, and potential vacancy/maintenance costs.

#### 🔍 Key Findings:
- **Top Region**: **Florence, SC** with a rental ROI of **5.54%**.
  - Benefits from low property tax (0.47%) and good rent-to-value ratio.
- **Negative ROI Regions**: Occurred where:
  - Mortgage payments exceeded rent income.
  - High taxes and maintenance costs eroded profits.

#### 📌 Conclusion:
- Investors should prioritize regions with **moderate home prices, low taxes, and sustainable rents**.
- High rental income alone doesn’t guarantee ROI—expenses must be carefully modeled.
- Include **vacancy rates** and **management fees** to reflect true net income.

## 📊 Visualizations
This project includes a mix of **interactive and static charts** that uncover key trends, patterns, and insights across the U.S. housing market using Zillow data.
- **Interactive bar chart** showing ROI % across best-performing states.
- **Sunburst Chart** for Hierarchical breakdown of top 5 states by median sale price and county-wise distribution.
- **Geographical Heatmap** of inventory listings by state (2024–25).
- **Summary Table** - Tabular breakdown of KPIs including ROI, tax rate, rent, and mortgage across selected regions. and many more can see seen inside the notebook.

## 🧑‍🤝‍🧑 Project Collaboration Context

This project was a team effort with the following division of work:

| Team Member        | Contribution                                      |
|--------------------|--------------------------------------------------|
| Member 1           | Q1 – Market Trends & Top-Performing Cities       |
| **Rohith Ambarish**| **Q2 – Price & Inventory Trends**, **Q5–Q6 ROI Models** |
| Member 3           | Q3 – Investment Timing & Location Recommendations |
| Member 4           | Q4 – Days on Market (DOM) Analysis               |
| All Members        | Presented individual models for Q5 & Q6 ROI      |

## 📁 Repository Structure
It contains the datasets used in the 'datasets' folder and the 'jupyter notebook' files.

## 🛠️ Tools Used

- Python (Pandas, NumPy, Matplotlib, Seaborn, Plotly)
- Jupyter Notebooks
- Zillow Housing Data (ZHVI, ZORI, Inventory, Tax Rates)

## 📌 Summary

My analysis shows that:
- The U.S. housing market is growing in both price and listings, but may cool in the short term.
- Strategic sales in smaller markets like **Niles, MI** can deliver meaningful ROI after 1–2 years.
- Rental income is most profitable in markets with **moderate home values and low taxes**, such as **Florence, SC**.

Accurate financial modeling of mortgage, upgrades, and operational costs is **critical** to successful investment.

## 🧪 How to Use
1. Clone the repo.
2. Install required packages (pandas numpy plotly seaborn matplotlib)
3. Launch the Jupyter Notebook
4. Explore the Notebook:
   - All interactive Plotly charts will render inside the notebook.
   - Scroll through markdown + code cells for Data loading, Visualizations, Insights, Conclusion.
  
## 🧠 Key Learnings
- **Analyzed real-world Zillow housing data** to identify market trends and investment opportunities.
- **Learned how to calculate ROI** for both property resale and rental income after expenses.
- **Used interactive Plotly charts to visualize** trends, compare regions, and present insights clearly.
- Identified top-performing markets for profitable investment.
- **Improved skills in Python, data analysis, visualization, and real estate financial modeling.**
- **Gained practical experience applying data science to real estate decision-making.**
   
