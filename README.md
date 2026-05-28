 Retail-Sales-Analysis-and-Hypothesis-Testing-
An end-to-end Business Intelligence (BI) and Data Analytics project on Kaggle Retail Sales dataset, featuring a dynamic Executive Dashboard and Statistical Analysis (t-Test & amp; ANOVA) built completely in Excel.
 Project Architecture
The project is structurally divided into three interconnected layers:
1. **ENTRY (The Gateway): Features a comprehensive project overview and an structured data dictionary for technical transparency.
2. DASHBOARD (The BI Layer): A dynamic, "Premium Dark Mode" interactive dashboard tracking core KPIs (Revenue, Transactions, AOV) synced with demographic slicers.
3. STATISTICAL TEST (The Lab): Advanced inferential statistics driven by hypothesis testing to mathematically model customer behaviors.

📐 Inferential Statistics & Hypothesis Testing
Rather than relying purely on visual trends, I implemented rigorous statistical testing using Excel's Analysis ToolPak at a 95% confidence level (\alpha = 0.05):
Independent Two-Sample t-Test:** Evaluated whether average spending differs significantly by **Gender**. 
  * Result:* $P-value = 0.9747$. Since $p > 0.05$, the null hypothesis cannot be rejected. Cinsiyet harcama miktarı üzerinde belirleyici bir faktör değildir.
* **One-Way ANOVA:** Analyzed variance across different **Product Categories** (Beauty, Clothing, Electronics).
  * *Result:* P-value = 0.8526. Since $p > 0.05$, there is no statistically significant difference in customer spending patterns across various product segments.

 Tech Stack & Tools Used
* **Data Analytics / BI:** Microsoft Excel (Advanced Pivot Tables, Interactive Slicers, Dynamic Charting)
* **Statistical Modeling:** Excel Analysis ToolPak (t-Test: Two-Sample Assuming Equal Variances, Anova: Single Factor)
* **Methodology:** Exploratory Data Analysis (EDA), Hypothesis Testing, Data Visualization
