**Smart Buy Retail Company — Project Background**

**Overview**:

Smart Buy Retail Company, established in 2022, is a national retail enterprise headquartered in Nigeria, operating across five major states: Lagos, Port Harcourt, Kano, Abuja, and Ibadan. The company offers a diverse product portfolio spanning Beauty, Fashion, Groceries, Home & Living, and Electronics, served through both online and in-store channels.

**Problem Statement**

Despite generating significant volumes of operational and transactional data across its sales, marketing, discounting, and loyalty functions, Smart Buy had largely left this data underutilised. Without a structured analytical framework, the business lacked the visibility needed to make confident, data-driven commercial decisions from optimising regional strategies to evaluating the true return on marketing investment.

**Project Objective**

This project delivers a thorough analysis and synthesis of Smart Buy's internal data to surface critical, actionable insights that directly support the company's commercial growth. By transforming raw data into clear narratives and evidence-backed recommendations, this project equips Smart Buy's leadership with the intelligence needed to compete more effectively across all markets and channels.

**Key Areas of Analysis**
1. **Monthly Trend Analysis**: Evaluation of sales patterns over time, with a regional lens, focusing on three core performance indicators: Revenue, Order Volume, and Profit Margin  to identify seasonality, growth trajectories, and periods of underperformance.
2. **Product-Level Performance**: An Analysis of Smart Buy's various product lines, understanding their impact on sales and returns
3. **Regional Comparison**: A comparative evaluation of sales performance, order volumes, and Marketing Return on Investment (ROI) across all five operational states, identifying regional strengths, gaps, and opportunities for targeted resource allocation.
4. **Loyalty Program Effectiveness**: An assessment of the loyalty program and its measurable impact on customer retention rates and sales performance.
5. **Discount Category Analysis**: An investigation into which discount bands and promotional categories generate the most profit

**Data Structure & Initial Checks**

Smart Buy's Database is shown below, connecting six tables: transaction, product, channel, customer type, region and date, with 6000 orders 

![image alt](https://raw.githubusercontent.com/MelodyNwaonusuru/Retail_Project/main/Screenshot%202026-05-03%20182527.png)

Download the Power BI report file to explore the interactive dashboard:

[⬇️ Download Retail_dataset.pbix](https://github.com/MelodyNwaonusuru/Retail_Project/raw/main/Retail_dataset.pbix)> ⚠️ Requires [Power BI Desktop](https://powerbi.microsoft.com/desktop/) to open.


**Executive Summary — Business Performance Overview**

**Smart Buy Retail Company**

1. Smart Buy generated #935.44M in total revenue, #183.03M in gross profit, and a 19.57% gross profit margin across 6,000 orders and 24,093 units sold.
2. Online outperformed Store in gross profit (#101.48M vs #81.55M), while Lagos led regional revenue at #197.53M, with all five regions performing within a relatively narrow range. 
3. Returning customers: dominated revenue contribution at 576.43M vs 359.01M from new customers, underlining the strength of Smart Buy's existing customer base.
4. Revenue peaked in January and November, with dips in February and December suggesting seasonal patterns worth monitoring. 
5. Notably, the 0% discount band generated the highest gross profit, with profitability falling as discount depth increased  making discount discipline a key margin lever for the business.

Below is the overview page from the Power BI dashboard, and more examples are included throughout the report.

![image alt](https://github.com/MelodyNwaonusuru/Retail_Project/blob/main/Screenshot%202026-05-07%20171357.png?raw=true)

**Insight Deep Dive — Product Performance**

**Key Findings**

1. Beauty leads across all commercial metrics, recording the highest revenue and gross profit among all five product categories, with performance trending consistently upward. This makes Beauty Smart Buy's most valuable and reliable product line.
2. Electronics and Groceries present a profitability paradox — despite generating some of the highest revenue figures, both categories return disproportionately low gross profit, signalling significant margin pressure that requires urgent attention.
3. Home & Living and Electronics carry the heaviest discount burden, receiving the highest discount allocations across the portfolio. This is directly counterproductive, as deeper discounting is eroding the very profit these categories could otherwise generate.
4. Beauty and Fashion operate on the lowest marketing spend, yet both categories deliver strong commercial returns, revealing a striking inverse relationship where higher marketing expenditure does not translate into higher revenue, and may in fact be inefficiently allocated across the remaining categories.
5. Electronics and Groceries dominate in units sold, recording the highest quantities across the product portfolio. Fashion and Beauty, by contrast, move the fewest units yet generate superior profit, underscoring that volume alone is not a reliable indicator of commercial value.

![image alt](https://github.com/MelodyNwaonusuru/Retail_Project/blob/main/Screenshot%202026-05-07%20171218.png?raw=true)


**Insight Deep Dive — Regional Performance**

**Key Findings**

1. Lagos and Kano lead the business commercially, consistently generating the highest revenue and gross profit across all five regions establishing themselves as Smart Buy's two most critical and productive markets.
2. Lagos and Kano also carry the highest discount allocations across all regions, raising an important question about whether the volume and revenue they generate is being achieved at the unnecessary cost of margin, and whether these results could be sustained with tighter discount discipline.
3. Lagos and Kano deliver the strongest Marketing ROI, confirming that marketing investments in these two regions are converting efficiently into commercial returns making them the most responsive markets to promotional activity.
4. Ibadan presents a compelling anomaly despite recording the lowest Marketing ROI, it still delivers high revenue and strong gross profit. This suggests Ibadan's performance is being driven by organic demand rather than marketing efficiency, and that there may be significant untapped upside if its marketing strategy is reviewed and optimised.
5. Lagos and Kano dominate in quantity sold, recording the highest unit volumes across all regions further reinforcing their position as Smart Buy's highest-throughput and most commercially active markets.
6. Lagos and Kano are Smart Buy's commercial engines, but their dependence on heavy discounting warrants scrutiny.
7. Ibadan's ability to generate strong returns with poor marketing ROI signals a market that is underserved by its current strategy and potentially one of the most rewarding opportunities for targeted investment across the entire regional portfolio.

![image alt](https://github.com/MelodyNwaonusuru/Retail_Project/blob/main/Screenshot%202026-05-07%20203443.png?raw=true)


**Insight Deep Dive — Monthly Performance and Seasonality**


**Key Findings**

1. Revenue is quite volatile month-to-month — there are frequent swings (both positive and negative), especially in 2025, where growth jumps as high as ~28% and drops below -15%. This suggests inconsistent demand or external factors affecting sales.
2. Q3 tends to perform stronger overall — months like July–September (especially 2025) show solid revenue and growth spikes, indicating some seasonality or a peak buying period.
3. Gross profit margin is stable but not improving — it mostly sits around 18%–20%, which is good for consistency, but there’s no clear upward trend despite revenue fluctuations.
4. Discounts fluctuate without clear impact on growth — higher discounts (₦11k–₦13k range) don’t always correspond to higher growth, which may mean discounts aren’t being used efficiently.

![image alt](https://github.com/MelodyNwaonusuru/Retail_Project/blob/main/Screenshot%202026-05-07%20171110.png?raw=true)


**Recommendations**

**Strategic Priorities**

1. Prioritise customer retention above new acquisition — returning customers generate #217M more in revenue than new customers; investing in structured loyalty programmes, personalised offers, post-purchase re-engagement, and exclusive returning-customer incentives will protect and compound this commercial advantage
2. Enforce discipline around the 0% discount band — the data is unambiguous: full-price transactions are the most profitable; the business should resist the impulse to apply blanket promotional discounts and instead focus on value-driven marketing, product storytelling, and experience improvements that justify full-price purchasing
3. Fundamentally reassess marketing spend allocation — the current evidence shows a weak or inverse relationship between marketing spend and revenue performance at the category level; a channel-by-channel audit should be conducted, with budget cut from low-conversion activity and reallocated toward demonstrably high-return channels and formats
4. Investigate and act on the Ibadan anomaly — Ibadan is generating strong revenue and profit with poor marketing efficiency, which almost certainly means organic demand is doing the heavy lifting; a structured experiment to reduce paid marketing spend in Ibadan while monitoring volume impact would either unlock budget savings or reveal a ceiling that smarter targeting could push through
5. Lead all commercial planning with Beauty and Fashion — these two categories should anchor promotional calendars, seasonal campaign briefs, inventory planning, and visual merchandising decisions; the data does not support continuing to over-invest in Electronics and Groceries from a marketing standpoint without first resolving the profitability gap
6. Protect and grow Lagos and Kano as priority markets — while their high discount allocations deserve scrutiny, their commercial throughput makes them the backbone of the business; they should receive priority treatment in stock depth, delivery speed, customer experience quality, and localised campaign relevance
7. Accelerate the online channel — a #20M gross profit gap over Store is not a marginal difference; the business should treat Online growth as a strategic priority, investing in checkout optimisation, delivery proposition improvement, digital acquisition, and UX enhancements that convert browsing into purchasing at a higher rate
8. Address the Electronics and Groceries margin problem directly — both categories are moving high volumes with low profit return; options to explore include pricing architecture reviews, category bundle strategies, cost renegotiations with suppliers, and a deliberate reduction in discount depth to test whether demand is genuinely price-elastic or whether margin can be recovered without significant volume loss.

These recommendations are drawn directly from the data and are designed to be actionable within a short execution window. The 90-day focus is on quick wins that protect margin, improve channel efficiency, and double down on what the data has already confirmed is working.


Tools Used
Tool	Purpose
1. Power BI Desktop —	Data modelling, DAX measure development, dashboard design and layout
2. Power Query (M) — Data transformation, column structuring, data type enforcement
3. DAX	KPI measures — Gross Profit Margin, Marketing ROI, MoM Revenue Growth %, Average Discount, Total Revenue Per Product, conditional formatting logic
4. Star Schema Modelling — Structured the data model with one fact table and five dimension tables for clean cross-filtering
5. Custom Date Table —	Built manually in Power Query to enable accurate time intelligence and correct Month Name ordering.
