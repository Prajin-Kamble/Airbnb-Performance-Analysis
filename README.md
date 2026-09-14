# Airbnb Performance Analysis
## 1. Problem Statement
Airbnb operates as a global online marketplace for short-term accommodation across multiple cities, offering various property types hosted by independent providers. Over time, the platform has experienced rapid growth, regional demand variations, pricing differences, and changes in customer behavior.<br>
However, stakeholders lack a centralized analytical view to understand:<br>
•	Which cities contribute most to business growth?<br>
•	How pricing and property types influence adoption?<br>
•	Customer satisfaction and review behavior.<br>
•	Seasonal demand patterns.<br>
•	Trust and verification levels of hosts.<br>
To address these challenges, this project leverages Power BI-based data analytics to uncover actionable insights from listing, pricing, review, and host data, enabling Airbnb to make data-driven strategic decisions for growth, quality improvement, and customer trust.

## 2. Goal of the Dashboard
The primary goal of this dashboard is to:<br>
• Provide a global overview of Airbnb performance<br>
• Identify high-performing cities and markets<br>
• Analyze pricing strategies and property preferences<br>
• Evaluate customer satisfaction and ratings drivers<br>
• Understand customer behavior through review patterns<br>
• Detect seasonality trends in demand<br>
• Assess host trust and platform safety<br>
• Support business expansion, marketing, and operational decisions<br>

## 3. Key Visuals in Dashboard
The dashboard includes the following key visuals:<br>
• KPI Cards<br>
  - Total Listings<br>
  - Total Cities<br>
  - Total Hosts<br>
  - Property Types<br>
  - Total Reviews<br>
• New Listings Trend (Time Series)<br>
  - Shows lifecycle: Introduction → Growth → Maturity → Decline → Reinvention → COVID impact<br>
• Market Share by City (Bar + Cumulative Line Chart)<br>
  - City-wise contribution to total listings<br>
• Property Type & Pricing (Bar Chart)<br>
  - Price comparison: Hotel vs Airbnb types<br>
• Ratings Heatmap (Matrix Visual)<br>
  - Metrics: Accuracy, Cleanliness, Communication, Location, Value<br>
• Review Frequency Distribution (Histogram + Line)<br>
  - Customer engagement behavior<br>
• Seasonality Analysis (Stacked Area Chart)<br>
  - Monthly review trends by city<br>
• Trust & Verification (Donut Chart)<br>
  - Verified vs Non-verified hosts<br>

## 4. Insights (Based on Client Questions + Dashboard Data)
1. Big Picture / Overview - <br>
- Airbnb operates across 10 cities with 2,79,712 listings and 1,82,024 hosts<br>
- The platform experienced peak growth in 2015, followed by slowdown due to regulations and COVID-19 impact<br>
- Growth lifecycle shows clear phases: rapid growth → maturity → decline → recovery<br>

<b>Insight:</b> Airbnb is a mature platform with external dependency factors (regulations, pandemics)

2. Market Share by City <br>
- Paris, New York, and Sydney contribute nearly 50% of listings and 59% of reviews<br>
- Paris has the highest listings and reviews globally<br>

<b>Insight:</b><br>
- Market is highly concentrated, not evenly distributed<br>
- Few cities dominate supply → risk of over-dependence<br>

3. Property Type & Pricing <br>
- Average prices:<br>
    - Hotel Room: $800<br>
    - Entire Place: $673<br>
    - Shared Room: $580<br>
    - Private Room: $462<br>
- Hotels are significantly more expensive → drives Airbnb adoption<br>

<b>Insight:</b><br>

- Airbnb succeeds due to price advantage over hotels<br>
- “Entire Place” is a strong premium segment<br>

4. Ratings & Customer Satisfaction<br>
- Best-rated cities: Mexico City, Rio de Janeiro<br>
- Worst-rated cities: Hong Kong, Istanbul<br>
- Lowest scoring factors:<br>
    - Cleanliness<br>
    - Value for money<br>

<b>Insight:</b><br>
- High supply ≠ high quality<br>
- Operational quality issues directly impact ratings<br>

5. Review Frequency (Customer Behavior)<br>
- Most users write only 1 review<br>
- 98.8% of users write ≤ 3 reviews<br>

<b>Insight:</b><br>
- Customer engagement is low and skewed<br>
- Reviews are not frequent → limited feedback loop<br>

6. Seasonality Analysis<br>
- Paris & Rome peak: April – August (summer travel)<br>
- New York peaks: Nov – Dec (holiday season)<br>

<b>Insight:</b><br>
- Demand is highly seasonal and location-dependent<br>
- Travel patterns vary by geography<br>

7. Trust & Host Verification<br>
- 66.9% hosts fully verified<br>
- Nearly all hosts provide at least one trust signal<br>

<b>Insight:</b><br>
- Platform maintains strong trust foundation<br>
- Very low anonymous/unverified presence<br>

## 5. Recommendations
1. Business Growth
- Expand in under-penetrated cities (reduce dependency on top 3 cities)
- Invest in emerging markets (Asia, Latin America)

2. Pricing Strategy
- Promote “Entire Place” segment for higher revenue
- Maintain price advantage vs hotels
- Introduce dynamic pricing models for seasonal demand

3. Customer Experience
 - Improve:
    - Cleanliness standards
    - Value for money perception
- Introduce:
    - Host quality training
    - Standardization guidelines

4. Engagement Improvement
 - Encourage more reviews via:
    - Incentives (discounts, coupons)
    - Simplified review process

5. Seasonality Optimization
- Launch seasonal marketing campaigns
- Help hosts with demand forecasting tools

6. Trust & Safety
- Increase host verification to >80%
- Highlight trusted hosts in search ranking
- Strengthen fraud detection

7. Risk Mitigation
- Reduce reliance on top cities
- Prepare contingency strategies for:
    - Regulatory changes
    - Global disruptions (like COVID)

![Snapshot of Power BI dashboard](https://github.com/Prajin-Kamble/Airbnb-Performance-Analysis/blob/main/Screenshot%20of%20the%20dashboard.JPG)
