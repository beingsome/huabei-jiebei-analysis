Project: Credit Product Risk Diagnostic & Strategy Analysis
1. Project Overview
Project Type: Independent Risk Diagnostic Analysis

Data Source: Real transaction data from two consumer credit products (Huabei & Jiebei)

Time Period: April 2020 – July 2020 (4 months)

Tech Stack: Power BI (DAX, Power Query, Drill-through), Excel (Power Query, Pivot Tables), Python (Pandas)

2. Business Problem
The core business questions driving this analysis were:

Risk Identification: What are the hidden risk structures within our product portfolio, and how do they differ between the two credit products?

Growth Drivers: Is business growth healthy, and what is the fundamental driver of performance differences across teams—market conditions or team capabilities?

3. Key Findings
3.1 Differentiated Risk Profiles
Jiebei (Cash Loan): This product accounts for 99.9% of total transaction volume. Its credit risk is highly concentrated in long-term products (12-month and 18-month), creating a large exposure to macroeconomic fluctuations and single-point defaults.

Huabei (Consumer Credit): Despite a small transaction volume, a significant cash-out risk signal was identified. Its 6-month product contributed 46.3% of total volume with only 9.3% of users, a severe "inverted pyramid" structure that strongly suggests cash-out or misuse activity.

3.2 Market as the Primary Performance Driver
Geographic Disparity: Performance shows a clear "coastal > inland" hierarchy. Hefei was a notable exception, ranking among the top-performing cities despite being inland.

Limited Evidence of "Star Teams": Team performance rankings were almost entirely dependent on their city's market size. Product structures across different teams within the same city were highly homogenous, with no evidence of teams possessing unique capabilities to select high-value customers or penetrate new markets.

3.3 Staffing Ratio Not a Core Issue
A dedicated scatter plot analysis found no significant correlation between a team's manager-to-staff ratio and its per-capita transaction efficiency. Market size far outweighed management structure as a performance driver.

4. Business Recommendations
Based on this diagnosis, I proposed three concrete strategic actions:

Implement Differentiated Risk Control: Apply strict credit review and single-exposure limits for Jiebei's long-term products (12-month, 18-month), while closely monitoring Huabei's 6-month and 12-month products for abnormal large transactions to prevent cash-out risk.

Reallocate Market Resources: Shift expansion resources towards high-potential, under-penetrated inland cities like Chongqing, Xi'an, Chengdu, and Wuhan.

Optimize Performance Metrics: Move from evaluating teams on absolute revenue to metrics like "market share growth" to better align incentives with market development.

5. Technical Implementation
Data Modeling & Automation: Cleaned and integrated multi-source data using Power Query, and built a suite of DAX measures for core metrics (average transaction value, per-capita efficiency, manager-to-staff ratio).

Interactive Dashboard: Developed a multi-page Power BI report with an overview dashboard and drill-through pages for province-level analysis, enabling real-time, self-service diagnostics.

Diagnostic Analysis: Employed cross-comparison of amount-to-user ratios, multi-dimensional drilling (by region, team, and product), and scatter plot visualization to validate hypotheses and uncover hidden patterns.
