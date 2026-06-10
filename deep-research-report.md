# Project Overview  
This project will analyze the telecom operator’s revenue streams to identify growth levers and revenue leaks. The focus is on using business-oriented analytics (Excel pivot-tables and Power BI dashboards) to uncover how customer behavior, plan mix, and regional factors drive revenue. We aim to deliver insights that inform strategy and improve financial performance.  

# Business Background  
The global telecommunications industry is vast (≈USD 1.53 trillion in 2024) but growth is slowing. Mature markets are saturated and highly competitive. Operators invest heavily in network upgrades (5G, fiber) and face rising costs, yet overall revenue growth is modest (≈3% CAGR projected through 2028). Within this context, our telecom company has a large subscriber base and multiple service plans, but its top-line growth is below expectations.  

Key industry challenges include intense competition (leading to price pressure), high customer churn, and complex cost structures. Many operators find that traditional voice/data services have reached saturation, and new services (IoT, 5G B2B) are not yet driving sufficient revenue. At the same time, internal issues like billing errors and inefficient processes can cause **revenue leakage**. Industry studies estimate telcos can lose up to ~7% of potential revenue through billing or system gaps. To regain growth, operators often focus on customer retention, bundling services, and targeted offers.  

# Problem Statement  
Our client has a broad service offering and many customers, yet revenue growth is disappointing. Management suspects several factors: lower-than-expected ARPU (Average Revenue Per User), high churn, suboptimal plan mix, and potentially unbilled services. In particular, **revenue leakage** – the gap between delivered services and billed revenue – may be eroding income. The task is to analyze customer usage, plan performance, and regional trends to **identify why revenue is lagging** and find opportunities to improve profitability and growth.

# Project Objectives  
- **Assess Revenue Drivers:** Examine how customer segments, subscription plans and region mix contribute to total revenue. Identify which segments or plans drive the most revenue (and which are underperforming).  
- **Detect Revenue Leakage and Churn:** Uncover any patterns where high usage isn’t translating into revenue, and identify customer churn patterns.  
- **Customer Value Analysis:** Calculate customer lifetime value and ARPU for key segments to spotlight high-value customers and growth opportunities.  
- **Plan Portfolio Insights:** Evaluate how different subscription plans (including bundled offers) perform in revenue and customer adoption.  
- **Regional Profitability:** Compare revenue and growth by geographic region to flag underperforming markets.  
- **Actionable Dashboards:** Build Excel and Power BI reports that deliver these insights to decision-makers interactively.  
- **Support Decision-Making:** Provide management with recommendations (e.g. plan adjustments, retention campaigns, targeted offers) backed by data.  

# Business Scope  
The analysis will cover existing internal data on customers, subscriptions, usage, billing, and geography. Specifically, we will analyze: customer profiles (demographics, tenure), service plans and pricing, usage metrics (calls, data, etc.), billing/revenue records, and regional identifiers. The scope includes all major service lines (mobile, fixed broadband, etc.) and customer types (prepaid/postpaid, enterprise/consumer). We will use Microsoft Excel (for data cleaning, pivot tables, ad-hoc analysis) and Power BI (for visualization and dashboards) exclusively.  

Areas **out of scope** include technical network data (beyond customer usage), detailed operational audits, or new data collection. No advanced coding or machine learning will be used; all analysis relies on Excel formulas and Power BI features (per constraints). The scope is strictly business-analytics focused.  

# Stakeholder Analysis  
- **Chief Financial Officer (CFO):** Concerned with revenue growth, cost control, and profitability. Seeks clear metrics (e.g. ARPU, churn, regional revenue) to guide budgeting and investment. This project will arm the CFO with dashboards to monitor revenue performance and identify where to cut costs or boost offers.  
- **Chief Executive/Board:** Focused on strategic growth. Wants to know which markets or segments to prioritize. The outcome (summarized KPIs and trends) will help them set strategy (e.g. pricing, expansion) and report progress to investors.  
- **Marketing & Sales Leaders:** Responsible for customer acquisition and retention. They need to understand which customer segments and plans are most profitable, and where churn is highest. Insights (e.g. “young urban customers on Plan X churn 20% faster”) will guide targeted campaigns and product promotions.  
- **Regional/Business Unit Managers:** Oversee sales in specific regions. They need regional revenue analyses to compare performance. Dashboards will help them allocate resources (e.g. invest more in fast-growing districts) and design local offers.  
- **Customer Service/Retention Team:** Focus on reducing churn. They need to know why customers leave (e.g. network issues, billing confusion) and which at-risk customers are highest value. The analysis will provide data-driven triggers for retention actions.  
- **Finance & BI Analysts:** They will build and maintain reports. Their objective is to deliver accurate, timely dashboards and train users (CFO, marketers) on how to use them. The project gives them a framework (data requirements and KPIs) to develop a BI solution aligned with business needs.  

All stakeholders will benefit by receiving clear, actionable reports. For example, leadership dashboards (CFO/CEO) will highlight ARPU, churn, and growth trends. Marketing can use segment-level revenue breakdowns to decide which offerings to promote. Customer service can use churn analytics to prioritize interventions.  

# Industry Research Summary  
**Telecom Industry Overview:** The telecom sector has matured in many markets. Major operators no longer see double-digit growth; instead, industry revenues are growing low-single-digits. This is due to market saturation (most customers already have service), fierce price competition, and only gradual uptake of new services. Operators continue heavy investment in 5G and fiber, but these capex demands put pressure on margins.  

**Revenue Challenges:**  
- *Stagnant Growth:* Analysts project global telecom revenue growth of only ~3% annually (2023–2028). Headwinds include slow economies, regulatory constraints, and uncertainty around monetizing IoT and 5G business services.  
- *High Churn & Price Pressure:* Customers can switch easily (low switching barriers), and if service quality or price is poor they leave. Poor network performance alone causes ~45% of churn, and bad customer service about 39%.  
- *Complex Billing (Revenue Leakage):* The many plans, bundles, and partners make billing complicated. Industry studies find telecoms lose a material share of revenue to billing/system errors (e.g. ~7% of potential revenue). Such leakage directly hurts profit margins.  
- *Cost Inflation:* Energy, labor, and network maintenance costs are rising. Many telcos need to cut operating expenses or prices to stay competitive. 

**Key Business Metrics:** Several metrics are industry-standards for performance.  For revenue analysis the most important are:  **Total Revenue**, **Average Revenue Per User (ARPU)**, **Customer Churn Rate**, **Subscriber Growth**, **EBITDA margin**, etc. ARPU and churn are especially critical. ARPU (total revenue ÷ total subscribers) measures how much each customer generates. Churn rate (percentage of subscribers lost per period) shows retention health.  Other common KPIs include *Subscriber Count*, *Net Additions* (new minus dropped customers), and *Capital Expenditure as % of Sales*. Tracking **Revenue by Segment** (plan type, region, customer class) is also standard in telecom analytics.  

**Best Practices for Revenue Optimization:**  
- **Focus on Customer Retention and Value:** It is well known that retaining existing customers is far cheaper and more profitable than acquiring new ones. Studies show retaining a customer can be 5× cheaper than signing up a new one, and existing customers contribute ~95% of profits. Consequently, many telcos emphasize loyalty programs, service quality improvement, and data-driven retention campaigns.  
- **Service Bundling & Upsell:** Operators drive ARPU by bundling services. For example, converged fixed+mobile plans (FMC/MMC) yield about 25% higher ARPU than standalone offerings. Cross-selling broadband, TV or IoT services to mobile customers (and vice versa) is a proven growth strategy. Industry analyses note that such up-sell and cross-sell greatly improve customer value and stickiness.  
- **Data-Driven Segmentation:** Best-practice telcos use analytics to segment customers by usage, profitability, and churn risk. This allows targeted marketing (e.g. personalized offers to high-ARPU segments) and timely intervention for at-risk customers.  
- **Continuous KPIs Monitoring:** Top operators maintain interactive dashboards tracking core KPIs (ARPU, churn, revenue trends by segment) for timely decision-making. They periodically review and adjust pricing or promotions based on these metrics.  

# Key Business Questions  
To guide the analysis, we will answer detailed business questions such as:  
- **Customer Segments:** Which customer segments (by age, tenure, usage profile, or other demographics) generate the highest revenue and ARPU? Which segments are growing or shrinking? (High-level analyses often begin with ARPU and subscriber segmentation.)  
- **Plan/Service Contribution:** Which subscription plans or bundles contribute most to total revenue? Which plans have the largest customer bases (adoption rate)? Are some plans underperforming in revenue per subscriber?  
- **Regional Performance:** How does revenue vary by geographic region or market? Which regions are underperforming relative to their customer count, and why? (E.g. is a region’s low revenue due to low ARPU or high churn?)  
- **Usage vs. Revenue:** Are there customers who consume a lot of service (calls/data) but pay little (e.g. on low-tier plans)? Do some plans have a mismatch between usage and price?  
- **Churn & Retention:** What is the churn rate overall and by segment/plan/region? Which factors (plan type, customer age, tenure) are associated with higher churn? Which customer groups are at risk of leaving, and what revenue might be at stake?  
- **Cross-sell/Upsell Potential:** Which customers currently buy a single service (e.g. only mobile) who might be candidates for an additional service (broadband/TV)? What is the potential ARPU uplift from cross-selling? (Leveraging the fact that existing customers spend 4× more than new ones.)  
- **Plan Adoption:** Which new or promotional plans have the highest take-up? Are there pricing or feature gaps (e.g. high usage customers have no suitable plan)?  

These questions will be explored using pivot tables and BI filters to drill down on segment-level revenue and trends. Together they aim to pinpoint where to focus marketing and product strategies.

# Data Requirements  
To answer these questions, we need:  
- **Customer Data:** Unique customer identifiers, demographics (age, segment, tenure), and contact info if available.  
- **Subscription/Plan Data:** Records of each customer’s subscribed plan(s) over time (plan type, bundle components, effective dates). This includes any add-on services (e.g. extra data packs).  
- **Usage Data:** Aggregated usage metrics per customer (e.g. monthly minutes, data volumes, SMS count). This enables ARPU analysis.  
- **Billing & Revenue Data:** Transaction-level or summary data showing charges and payments. Specifically, monthly billed revenue per customer (or account) and the breakdown by service (voice, data, equipment, etc.).  
- **Churn/Retention Data:** Flags or dates for customer cancellations or discontinuations, and reasons if logged.  
- **Regional/Geographical Data:** Each customer’s location or region (e.g. state/district). Region codes to map revenue to geography.  
- **Plan Metadata:** Details of each plan (price points, included usage, service tiers). This is needed to analyze plan performance.  
- **Timeframe:** Historical data (e.g. last 12–24 months) to assess trends and seasonality.  

All data sources must be exportable to Excel or connected to Power BI. In scope are internal data systems (CRM, billing, usage logs). No external data is assumed (market data or competitive pricing) unless readily available, so the analysis focuses on internal drivers.

# KPI Framework  
We will track a set of key performance indicators that encapsulate telecom revenue performance:  

- **Total Revenue (Period):** Sum of all billed revenue over a period (monthly/quarterly). This is the baseline financial KPI.  
- **Average Revenue Per User (ARPU):** Defined as *Total Revenue ÷ Average Subscriber Count*. ARPU is a core industry metric for assessing per-customer profitability. (Higher ARPU indicates more revenue per subscriber, often through premium plans or bundles.)  
- **Revenue by Region:** Total revenue broken down by geographic region or market, enabling identification of high- and low-performing areas.  
- **Revenue by Plan/Bucket:** Total revenue attributable to each subscription plan or bundle. This shows which offerings are most lucrative.  
- **Customer Retention Rate:** Percentage of customers retained (not churned) over a period, i.e. 100% – *Churn Rate*. A higher retention rate means lower customer turnover.  
- **Customer Churn Rate:** Percentage of customers who cancel service in a period. (For example, if 20 out of 200 customers left in a month, churn = 10%.) Lower churn is better; high churn forces the company to replace customers constantly.  
- **Revenue Growth Rate:** Period-over-period growth in total revenue (e.g. YOY or QoQ). Tracks whether revenue is actually improving.  
- **Customer Lifetime Value (CLV):** An estimate of average revenue a customer will generate over their entire relationship (from sign-up until churn), usually calculated as ARPU × expected tenure. CLV helps prioritize high-value segments.  
- **Plan Adoption Rate:** Share of total customers subscribed to each plan (or bundle). It can also be defined as the percentage of new customers choosing a given plan. This indicates popularity and market fit of each offering.  

Each KPI will be computed in Excel (using formulas and pivots) and displayed in Power BI dashboards. For example, ARPU and churn (critically noted by analysts) will appear as trend lines. Revenue by region and plan will be visualized in charts. CLV and adoption rates will be derived from the base data. These metrics collectively provide a multidimensional view of revenue health.

# Proposed Analysis Areas  
To address the objectives and questions above, we propose analyzing the following areas:

- **Customer Value Segmentation:** Segment customers by demographic or behavior (e.g. usage tier, age group, tenure) and calculate revenue metrics for each. Compare ARPU, total spend, and retention for each segment. Identify the highest-value cohorts (e.g. long-tenure high-usage customers) versus riskier cohorts (e.g. young customers with low ARPU). Such analysis will reveal which segments generate the lion’s share of revenue.  

- **Subscription Plan Performance:** Evaluate each subscription plan/bundle for profitability and popularity. For each plan: compute total revenue, ARPU (revenue per subscriber on that plan), churn rate, and number of subscribers. Identify top-performing plans (high revenue/ARPU) and underperformers (low ARPU or high churn). For example, compare bundled plans against standalone ones; industry research suggests bundled plans boost ARPU (≈25% higher). This will guide whether to promote, adjust, or discontinue specific plans.  

- **Regional Revenue Analysis:** Compare revenue and growth by region. Use maps or charts to highlight regions with low revenue relative to subscriber counts. Drill into factors: is a region’s poor performance due to lower ARPU (e.g. many low-tier customers) or higher churn? Geographic analysis may uncover local issues (poor coverage, misaligned pricing) to address.  

- **Usage vs Revenue Mismatch:** Identify customers whose usage patterns do not align with their billing. For example, find high-data users on low-priced plans (potential upsell candidates) or customers whose usage exceeds plan allowances (could indicate billing gaps). This helps detect revenue leakage: when customers use services but are not billed appropriately. Ensuring usage → billing alignment is key, as even small leaks hurt profitability.  

- **Churn and Retention Analysis:** Analyze churn drivers. Use cohort and trend analysis to see when and why customers leave. For instance, calculate churn rate by plan, region, and customer age group. Identify common traits of churners (e.g. mostly on basic plans, new customers who never bundled). Since nearly half of churn is driven by quality issues, cross-reference churn spikes with network quality reports or customer complaints. Pinpointing causes enables targeted retention campaigns (e.g. loyalty offers for at-risk users).  

- **Cross-Sell and Upsell Opportunities:** Examine customers of single services for cross-sell potential. For each customer segment, calculate attachment rates (e.g. percent of mobile customers also using broadband). Identify segments with low cross-sell penetration but high value (e.g. high-ARPU mobile-only customers who could adopt home internet). Use spend patterns to flag who might upgrade to bigger bundles. As Simon-Kucher notes, leveraging existing subscribers with cross-sell can significantly grow revenue.  

- **Plan Adoption and Competitiveness:** Look at adoption rate of newly introduced plans or promotions. Analyze take-up of entry-level vs premium plans. If a plan has low adoption, consider market repositioning. Also, compare the company’s ARPU and churn to industry benchmarks (investor reports) to gauge competitiveness.  

Each area will be explored with Excel pivot tables (for quick slicing) and with Power BI visuals (for interactive dashboards). The goal is to turn data into specific insights (e.g. “Plan A underperforms with 30% higher churn than average”) that directly inform business tactics.

# Dashboard Strategy  
We will design a multi-page Power BI dashboard to present the findings and KPIs. Key pages and their contents include:  

- **Executive Summary Dashboard:** High-level snapshot for leadership. Shows total revenue and growth rate, overall ARPU, total subscribers, average churn rate, and customer lifetime value. KPIs will be presented as big number tiles and trend charts. Includes summary maps or bar charts of revenue by top regions and by plan category. This page provides a “bird’s-eye view” of business performance.  

- **Customer Revenue Dashboard:** Focused on customer segments. Interactive visuals will allow filtering by demographic attributes (age, segment, tenure) or by usage categories. Graphs will display revenue by segment, segment ARPU, and segment churn/retention rates. This helps identify which customer groups (e.g. prepaid vs postpaid, urban vs rural) drive profit.  

- **Plan Performance Dashboard:** Details on each subscription plan’s performance. Contains charts for revenue contribution per plan, plan adoption rates (customers per plan), and plan-specific ARPU and churn. For example, a bar chart could rank plans by revenue, with color-coding for average churn. This will highlight high-revenue plans (candidate heroes) and low-performing ones.  

- **Regional Revenue Dashboard:** Geographic analysis view. Includes a map or region-level bar chart showing revenue, ARPU, and churn by region. Users can drill down into regions or states to see city-level performance if data allows. Filters for time period and segment enable time-trends by region. This reveals regions that need sales attention or infrastructure investment.  

- **Revenue Trend Dashboard:** Time-series view of revenue and related KPIs. Displays monthly (or quarterly) trends for total revenue, ARPU, new subscribers (net additions), and churn over time. Line charts highlight patterns and seasonality (e.g. any drop in certain months). Trend insights help in forecasting and in measuring impact of past initiatives.  

- **Business Recommendations Dashboard:** Summarizes key findings and suggested actions. It can combine relevant charts (e.g. top 5 segments vs bottom 5 segments by ARPU, or churn drivers) alongside bullet-point insights. This page is for decision-makers to quickly see “Now What?”, linking data to strategy.  

All dashboards will allow slicing and dicing (e.g. filtering by time, segment, region). Excel workbooks will also be prepared (pivot tables and charts) for ad-hoc analysis by analysts. The dashboards’ purpose is to turn the above analysis into interactive reports that drive discussion at management meetings.  

# Expected Benefits  
From this analysis, the company can expect:  

- **Identified Revenue Growth Opportunities:** By highlighting high-value segments and upsell potentials, the company can target efforts to increase ARPU. For example, cross-selling broadband to top mobile users can raise blended ARPU (bundled plans have ~25% higher ARPU).  
- **Plugged Revenue Leaks:** Detecting mismatches between usage and billing can recover otherwise lost revenue. Even a few percent of leakage can swing profits significantly. The analysis will pinpoint where billing processes or system issues may be causing under-billing.  
- **Improved Customer Profitability:** Segmentation will reveal which customers are most and least profitable. Management can then personalize offers (e.g. premium bundles for high-value customers) and prune unprofitable pricing. Knowing that existing customers contribute ~95% of profits, the company can focus on maximizing value from its base.  
- **Reduced Churn, Higher Retention:** Understanding churn drivers (e.g. plan type, quality issues) allows targeted retention programs. For instance, if network quality is found to cause churn in a region (as 45% of churn is tied to this factor), then investing in infrastructure or compensating affected customers can pay off.  
- **Optimized Plan Portfolio:** The insights will reveal which plans to promote, adjust, or retire. Underperforming plans (high churn, low revenue) can be redesigned or phased out, simplifying offerings. Conversely, plans that show strong adoption and revenue can be used in marketing.  
- **Enhanced Decision-Making:** Executives and managers will have a consistent KPI dashboard to monitor. This shared “single source of truth” enables faster, data-driven decisions (instead of relying on ad-hoc reports). For example, real-time visibility into regional sales performance will let regional managers react quickly if a market starts lagging.  

Overall, the analysis is expected to yield actionable intelligence that drives revenue growth, cost optimization, and better strategic alignment. (Industry experience shows that telcos which focus on data-driven customer management and plan optimization often see double-digit improvements in ARPU and 3–6% reductions in churn.)

# Risks and Assumptions  
- **Data Quality/Reliability:** We assume customer, billing and usage data are reasonably complete and accurate. *Risk:* Incomplete or inconsistent data (e.g. missing usage logs) could skew results. Proper data validation is needed.  
- **Tool Limitations:** Using Excel and Power BI means very large datasets (millions of records) could be slow to process. We assume data volumes are manageable (e.g. by summarizing data in BI-friendly tables). *Risk:* If data is too granular, performance issues may require further aggregation.  
- **Stakeholder Engagement:** It is assumed that stakeholders (especially in IT/finance) will provide required data and context. *Risk:* Delays in data access or conflicting definitions between departments (e.g. differing definitions of “active subscriber”) could impede progress.  
- **Execution:** The analysis assumes that recommended actions are implementable. *Risk:* Even with insights, if organizational barriers prevent acting on them (e.g. reluctance to change plans or invest in retention), benefits may not materialize.  
- **Market Factors:** External events (economic downturn, competitor moves) are outside scope. We assume that the primary revenue challenges are internal or controllable. *Risk:* Unforeseen external shocks could override insights.  
- **Tooling Constraints:** We assume Excel and Power BI can handle the analytic needs without resorting to advanced analytics (per project constraint). If, for example, predictive modeling were required, it’s out of scope.  

# Success Criteria  
Success will be measured by both deliverables and business impact:  
- **Deliverables:** Completion of a comprehensive PID and analysis report, along with finalized Excel data models and Power BI dashboards. These deliverables must meet user acceptance (stakeholders review and approve).  
- **User Adoption:** Key stakeholders (CFO, marketing leads, regional managers) actively use the dashboards for decision-making. Engagement metrics (e.g. regular dashboard views) will indicate adoption.  
- **Insight Clarity:** Stakeholders agree that the analysis answered the key questions. For example, identification of the top 3 revenue segments and underperforming plans will be acknowledged.  
- **Actionable Recommendations:** Management endorses at least some of the proposed recommendations (e.g. launching a targeted upsell campaign or restructuring plans).  
- **KPI Improvement (post-project):** Although longer-term, a targeted goal (e.g. reduce churn by X%, increase ARPU by Y%) could be set as a result of implementing the recommendations. Achieving movement toward those targets would signify success.  

In summary, the project is successful if it delivers clear insights and practical dashboards that directly inform strategic actions (even if implemented outcomes are measured later).

# Business Recommendations  
Based on the anticipated insights, we expect to recommend the following strategic actions:  
- **Revise Plan Portfolio:** Discontinue or reprice underperforming plans. For example, if analysis shows a basic plan has very low ARPU and high churn, consider merging it with a more profitable plan or changing its features. Emphasize and market bundled plans (FMC/MMC) since they boost ARPU by ~25%. Introduce incentives (discounts or added features) to encourage customers to move to higher-tier bundles.  
- **Enhance Customer Retention Programs:** Use the segmentation findings to run targeted loyalty campaigns. For high-value segments at risk of churn (e.g. long-tenure premium users), offer personalized retention offers (added benefits, loyalty points). Strengthen customer service in key areas: for instance, if network quality issues are causing churn (≈45% of churn), invest in network upgrades or provide service credits to affected customers. Track satisfaction (NPS) closely, as telecoms typically have low NPS and improving it is correlated with retention.  
- **Plug Revenue Leakage:** Based on any identified gaps between usage and billing, tighten processes. This could involve auditing billing system configurations, improving data integration between network and billing, and closing loops on promotions and discounts so that all services are billed correctly. Netsuite research notes that even small billing fixes can yield large profit gains. For example, ensure roaming and partner contracts are accurately implemented to avoid unbilled roaming revenue.  
- **Cross-Sell and Upsell to Existing Customers:** Focus marketing on customers with high usage but on basic plans – offer them upgrades. Since existing customers account for ~95% of profits, growing revenue from within is critical. Introduce bundled offers (e.g. mobile + broadband discounts) and feature add-ons (e.g. premium content, IoT devices) for current subscribers. Use the BI dashboards to identify exactly which customers to target (e.g. “postpaid smartphone users with high data usage only on a voice plan”).  
- **Geographic Strategy:** Reallocate sales and marketing resources to regions with untapped potential. For regions with high churn or low uptake, consider localized campaigns (improve coverage, regional promotions). Conversely, invest in expansion or upsell in regions with strong ARPU growth. Provide regional managers with incentive tied to these insights.  
- **Ongoing Monitoring:** Establish regular (e.g. monthly) review of the created dashboards in management meetings. This ensures insights lead to action. Recommend that KPIs such as ARPU, churn, and revenue by plan become part of routine executive reporting. This way, strategic decisions (pricing changes, network investments) can be dynamically adjusted as new data comes in.  

These recommendations are aligned with industry best practices: focusing on customer retention and value, optimizing pricing, and using data to steer strategy. Implementation should be done in collaboration with marketing, finance, and operations to ensure that analytics insights translate into measurable business improvements.

# Project Conclusion  
This Project Initiation Document lays the foundation for a comprehensive Telecom Revenue Analysis. By combining industry insights with the company’s data, we will deliver a clear picture of why revenue is underperforming and where the greatest opportunities lie. The project will produce actionable intelligence – through defined KPIs and interactive dashboards – that empowers decision-makers to take targeted actions. Ultimately, by understanding customer behavior, plan profitability, and regional performance in depth, the company can unlock revenue growth, improve customer profitability, and make more informed strategic choices. This PID, focused on business outcomes and leveraging familiar tools (Excel and Power BI), ensures the project stays aligned with stakeholder needs and drives real impact.  

**Sources:** Authoritative industry reports and studies were used to inform this document, including latest telecom market outlooks and telecom analytics best practices.