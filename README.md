# Financial-Statement-Analysis
### Project Overview
This project creates a financial intelligence framework designed to identify **Capital Stagnation** and **Liquidity Risk** across 4,668 companies. It moves beyond basic accounting profits to uncover the hidden operational and structural risks that threaten a company's actual cash availability.

### **The Real-World Problem**

Many businesses look successful on paper because their sales are high, but they are actually "cash-poor". This happens when money is trapped in unpaid customer invoices or slow-moving inventory. If a company cannot turn its sales into liquid cash quickly enough to pay its own debts, it faces a high risk of technical insolvency.

### **Core Objectives**

The analysis focuses on solving four primary business challenges:

* **Working Capital Bottlenecks:** It identifies companies where cash is trapped by flagging extreme delays in customer payments—sometimes stretching beyond 600 days—and comparing these to industry averages.


* **Hidden Insolvency Risks:** It isolates businesses that rely too heavily on borrowed money (debt-to-equity ratios above 2.0), making them vulnerable if the market dips.


* **Profit Erosion:** It uncovers "fake growth" by identifying firms where rising internal costs are eating away at actual profits, even when total sales numbers look good.


* **Market Value Traps:** It protects investors from hyped-up, overpriced stocks by cross-referencing market prices against proven financial health scores like the Piotroski and Altman Z-Score.



### **The Technical Solution**

To make this data actionable, the project uses a professional data engineering workflow:
1.
1. **SQL Integration**: Cleans and blends raw data into a master reporting view named `vw_Fact_LiquidityRiskAnalysis`.


2. **Power BI Dashboarding**: Connects this data to a visual ecosystem featuring automated risk alerts, sector benchmarking, and correlation charts.


3. **Proactive Oversight**: Transitions the management approach from reading old annual reports to using a real-time roadmap for protecting the portfolio and allocating capital wisely.

### Data Source
The dataset used in this project was sourced from Kaggle, a widely recognized platform for data science and analytics. The dataset used in this project is a comprehensive corporate intelligence repository covering a cross-industry universe of 4,668 companies. It is structured across ten distinct Excel workbooks, including Annual_P_L_1_final.xlsx, Balance_Sheet_final.xlsx, cash_flow_statments_final.xlsx, and ratios_1_final.xlsx, providing a multi-dimensional view of financial health.

Unlike standard datasets that focus solely on top-line revenue, this source provides a granular look at the friction points between operations and liquidity. It includes:


***Operational Cycle Metrics:*** Data on debtor collection timelines and cash conversion cycles to identify where capital is trapped.

***Structural Leverage Data:*** Detailed balance sheet figures used to calculate debt-to-equity ratios and evaluate insolvency risks.

***Profitability and Margin Trends:*** Comparative annual and quarterly profit and loss statements that reveal net profit contractions despite sales stability. 

***Fundamental Health Scores:*** Market-leading indicators, such as the Altman Z-Score and Piotroski G-Factor, paired with real-time price-to-earning (PE) multiples from price_final.xlsx.  


Before analysis, the data was reviewed and prepared to ensure consistency and accuracy. This included handling missing values, validating data types, and structuring the dataset for efficient querying in SQL and visualization in Power BI.

Overall, the dataset offers a solid foundation for deriving actionable insights and supports the project’s objective of delivering data-driven recommendations for improved decision-making.

### Tools
- Excel ( for data Cleaning) [Download Here](https://microsoft.com)
- SQL ( for Data Analysis)
- Power BI (Creating Reports)

### Data Cleaning/Preparation
Before conducting the analysis, the dataset was carefully cleaned and prepared to ensure accuracy, consistency, and reliability of the results. The data, sourced from Kaggle, was initially reviewed to understand its structure, data types, and any potential quality issues.

To transform the raw financial records of 4,668 companies into a reliable, automated analytics pipeline, the data underwent a structured cleaning and preparation process. This stage focused on fixing data inconsistencies, handling missing files, and structuring the dataset for seamless integration between SQL and Power BI.

The dataset such as; **Annual_P_L_1_final.xlsx**, **Annual_P_L_2_final.xlsx**, **Balance_Sheet_final.xlsx**, **cash_flow_statments_final.xls**, **ratios_1_final.xlsx**, **ratios_2_final.xlsx**, **Quarter_P_L_1_final.xlsx**,**Quarter_P_L_2_final.xlsx**,**other_metrics_final.xlsx**,**price_final.xlsx** was being cleaned using excel in order to remove the inconsistencies in the dataset such as line-break, spacing between text, improper text formating 

The dataset was then structured into a clean and analysis-ready format, enabling efficient querying in SQL and seamless integration into Power BI for visualization. This preparation step ensured that all subsequent insights and conclusions were based on high-quality, reliable data.
### Exploratory Data Analysis
Before Carrying out this analysis the following business questions where being asked for better performanance and decision-making
1.  How do high-risk cases, compliance violations, and fraud detection trends vary across firms and over time?
2.  Which risk factors have the greatest impact on total revenue, and what are the main drivers of financial loss?
3.  Does higher audit effectiveness lead to reduced compliance violations and improved fraud detection?
4.  How does the use of AI in auditing compare to non-AI audits in terms of effectiveness, detection rates, and client satisfaction?
5.  How does employee workload affect audit performance and overall client outcomes?
6.  What factors most strongly influence client satisfaction across the dataset?
### Data Analysis.
