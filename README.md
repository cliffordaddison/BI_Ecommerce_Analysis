# Project Overview

Avada launched as an e-commerce business in 2018, specializing in consumer electronics and accessories with global reach. The company has accumulated more than 100,000 data records covering sales performance, product catalog, marketing initiatives, and operational metrics. I conducted a comprehensive analysis of this dataset to identify opportunities for improving Avada's business performance.

My analysis focuses on delivering actionable insights across these key areas:

1. **Sales Performance**: Monthly and yearly growth patterns, average order values, and order volumes
2. **Product Analysis**: Revenue impact of different product categories and identification of top and bottom performers
3. **Operations Review**: Assessment of shipping and delivery performance across products and regions
4. **Marketing Assessment**: Evaluation of the loyalty program's impact on sales and its growth potential
5. **Returns Analysis**: Investigation of return patterns, frequently returned products, and regional variations

# Data Processing Approach
- Source dataset in Excel format available [here](https://github.com/cliffordaddison/BI_Ecommerce_Analysis/blob/main/E-list_Data.xlsx)
- Data cleaning methodology and issue resolution documented [here](https://github.com/cliffordaddison/BI_Ecommerce_Analysis/blob/main/Issue_Log.xlsx)
- SQL analysis queries available [here](https://github.com/cliffordaddison/BI_Ecommerce_Analysis/blob/main/sql_code.sql)
- Excel-based data analysis workbook found [here](https://github.com/cliffordaddison/BI_Ecommerce_Analysis/blob/main/Ecommerce_Analysis.xlsx)
- Database structure diagram located [here](https://github.com/cliffordaddison/BI_Ecommerce_Analysis/blob/main/ERD.png)

# Key Findings Summary
![image](https://github.com/user-attachments/assets/f0948444-957b-470c-b515-a8daacd20907)

1. **COVID-19 Market Surge (2020-2021):** Electronics sales, especially **27-inch 4K gaming monitors, MacBook Air laptops, Apple AirPods, and iPhones**, experienced dramatic growth during the pandemic. This surge corresponds with the shift to remote work, online learning, and home-based entertainment.
2. **Seasonal Revenue Peaks:** Sales consistently spiked during **January, September, and December**, indicating strong seasonal patterns tied to New Year purchases, back-to-school shopping, and holiday sales.
3. **Post-Pandemic Normalization:** Sales momentum declined throughout 2022, returning to pre-pandemic levels by Q4 2022, suggesting market normalization and potential demand saturation.
4. **Steady Performers:** Products like **Samsung Charging Cable Packs and Webcams** maintained consistent sales volumes without significant fluctuations, representing stable but niche market segments.

*NOTE: Interactive filters are available in the Excel version for detailed exploration.

# Detailed Analysis
## Sales Performance
<p align="center">
  <img src="https://github.com/user-attachments/assets/4eafd840-efad-401b-9253-d78b4d6219b7">
</p>

- Avada processed 108,000+ orders between 2019-2022, achieving $28M in total revenue with an average order value of $260.
- 2020 delivered peak revenue performance at $10M with a $300 AOV, while 2021 generated $9M revenue with a $255 AOV but higher order volume (35K vs 33K orders).
- The strongest year-over-year growth occurred in 2020, with order volume increasing 101% and revenue jumping 163%.
- March through December 2020 showed exceptional sales performance, directly correlating with pandemic-driven consumer behavior.
- Revenue was lowest in 2019 ($3.8M) and 2022 ($4.9M), bookending the pandemic boom period.

### Seasonal Patterns
![Screenshot 2025-02-19 163236](https://github.com/user-attachments/assets/3c044eb2-aa3f-4bb6-952e-81f48b8be917)

- September and December consistently showed the strongest sales performance annually, aligning with back-to-school and holiday purchasing cycles.
- Sales typically declined from February through June and in October, following post-holiday and post-back-to-school periods.
- 2022 broke this pattern with overall declining sales, ending the year below 2019 performance levels.

### Product Performance
<p align="center">
  <img src="https://github.com/user-attachments/assets/62fbfe72-38dc-4bd0-8787-e371fd0caea3">
</p>

- Four products dominate revenue generation: 27-inch 4K gaming monitors, Apple AirPods, MacBook Air laptops, and ThinkPad laptops, collectively accounting for $27M (96% of total sales).
- The top two performers—27-inch 4K gaming monitors and MacBook Air laptops—contribute $17.5M (63% of total revenue).
- Lower-performing products include Bose SoundSport headphones, Apple iPhone, Samsung charging cable packs, and Samsung webcams, generating just $1M (4% of total sales).
- Laptop products command the highest average order values: MacBook Air at $1,500 and ThinkPad at $1,100, while Samsung charging cable packs have the lowest AOV at $20.
- Apple AirPods lead in order frequency with 48K units sold (45% of all orders), followed by 27-inch 4K gaming monitors with 23K units (22% of orders).
- Bose SoundSport headphones had the lowest sales volume at 27 units (0.02% of orders), followed by Apple iPhone at 288 units (0.3% of orders).

## Shipping and Delivery
- Average shipping time across all regions and product lines is 2 days, with total delivery time averaging 8 days.
- Two notable exceptions significantly exceed these averages: Samsung Charging Cable in EMEA (9-day shipping) and Apple AirPods in North America (6-day shipping).
- These delays extend average delivery times to 15 days in EMEA and 11 days in North America for affected products.
- Bose SoundSport Headphones show faster shipping in APAC and LATAM regions, averaging 1 day.
- Accounting for these outliers, overall shipping times increase to 3 days in EMEA and 4 days in North America, with average delivery extending to 9 days.

## Loyalty Program Impact
<p align="center">
  <img src="https://github.com/user-attachments/assets/dfa66220-545f-470f-bf2c-3a45b3d33ed9">
</p>

- Non-loyalty customers generated $17M in revenue (61% higher than the $11M from loyalty members).
- The loyalty program showed increasing effectiveness over time: loyalty members contributed 11% of revenue in 2019 and 29% in 2020, then grew to 53% in 2021 and 55% in 2022.
- Average order value for loyalty members increased consistently, reaching $245 in 2022 compared to $214 for non-loyalty customers.

## Returns Analysis
<p align="center">
  <img src="https://github.com/user-attachments/assets/b86984ff-caea-4acd-94cf-9543a721af20">
</p>

- Total returns since 2019: 5,379 products, representing a 5% overall return rate.
- ThinkPad Laptop (12%) and MacBook Air Laptop (11%) show the highest return rates, while Apple AirPods (2,636 returns) and 27-inch 4K Gaming Monitor (1,444 returns) have the highest absolute return volumes.
- North America leads in returns with 2,998 items (56%), followed by EMEA with 1,462 returns (27%).
- Returns peaked in 2020 and early 2021, coinciding with the sales surge period.
- No returns recorded after July 2021, which requires investigation to determine the cause.

# Strategic Recommendations
## Sales Strategy
**Capitalize on Pandemic Insights**: The 101% YOY growth in 2020 demonstrates how external factors can drive electronics demand. Develop contingency marketing strategies for similar future events while preparing for demand normalization.

**Optimize High-Performance Products**: Focus marketing and inventory resources on the four products generating 96% of revenue. Implement targeted promotions during peak seasons (September-December) and create loyalty incentives for these high-value items.

**Enhance Premium Product Positioning**: With laptops averaging $1,300 AOV, emphasize their premium value proposition. Consider introducing financing options to make these higher-priced items more accessible to broader customer segments.

**Address Underperforming Segments**: The bottom four products contributing only 4% of sales need strategic attention. Analyze root causes for poor performance and implement targeted improvements during off-peak months (February-June, October) through pricing adjustments, promotional campaigns, or product line optimization.

## Operations Enhancement
**Standardize Shipping Performance**: Implement processes to achieve consistent 1-2 day shipping across all regions and product lines.

**Resolve Delivery Anomalies**: Investigate and address the specific causes of extended shipping times for Samsung Charging Cables in EMEA and Apple AirPods in North America to bring performance in line with company standards.

## Loyalty Program Development
**Expand Program Investment**: With loyalty members now contributing 55% of revenue (2022), increase program investment through enhanced benefits, personalized incentives, and improved customer engagement strategies.

**Leverage Growing AOV**: Loyalty member AOV increased from $207 (2019) to $245 (2022), indicating higher spending propensity. Develop tiered rewards systems that encourage larger purchases and cross-selling opportunities.

**Convert Non-Loyalty Customers**: Despite lower individual AOV ($214), non-loyalty customers represent significant revenue potential ($17M total). Implement targeted conversion strategies including attractive signup bonuses, benefit highlighting, and personalized promotions.

## Returns Management

**Investigate High-Return Products**: Address the root causes of high return rates for ThinkPad Laptops (12%) and MacBook Air Laptops (11%), and high return volumes for Apple AirPods (2,636) and 27-inch 4K Gaming Monitors (1,444). Examine potential quality issues, compatibility problems, or expectation misalignment.

**Focus on North American Operations**: With North America accounting for 56% of all returns, conduct regional analysis to identify specific distribution, customer service, or product usage factors contributing to this concentration.

**Investigate Return Data Gap**: The absence of returns after July 2021 requires immediate investigation to determine if this reflects improved operations, data collection issues, or reporting anomalies.

## Database Structure
The following diagram illustrates the current database architecture supporting this analysis.
<p align="center">
  <img src="https://github.com/user-attachments/assets/eb9bdbdc-5ea5-451a-8a98-cbcb33d1ef6c">
</p>
