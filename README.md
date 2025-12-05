# Financial Complaints Power BI Dashboard

## Project Overview

This project contains an interactive Power BI dashboard built using a financial complaints dataset. The dashboard provides insights into total complaints, dispute behavior, timely responses, issue categories, product-level breakdowns, and geographic distribution across the United States. Users can explore trends using filters such as date received and media submission channel.

## Dataset

The dataset includes anonymized consumer financial complaints collected through various submission channels.

### Key Fields

- Company: Financial institution or service provider receiving the complaint.  
- Company Response to Consumer: Final action or message provided to the consumer.  
- Complaint ID: Unique identifier for each complaint record.  
- Consumer Consent Provided?: Indicates whether the consumer consented to publish their complaint narrative.  
- Consumer Disputed?: Shows if the consumer disputed the company’s response.  
- Date Received: Date on which the complaint was originally received.  
- Date Submitted: Date the complaint was forwarded to the company (if available).  
- Issue: High-level category describing the type of complaint (e.g., billing disputes, identity theft).  
- Sub-Issue: Additional detail or subtype of the main issue.  
- Product: Financial product involved (credit card, bank account, mortgage, etc.).  
- Sub-Product: Additional product-level classification (e.g., debit card, checking account).  
- State: U.S. state where the consumer resides.  
- ZIP Code: ZIP code of the consumer (5-digit).  
- Submitted via: Channel through which the complaint was submitted (web, phone, referral, etc.).  
- Timely Response?: Indicates whether the company provided a timely response.  
- Bottom of Gauge / Top of Gauge: Calculated fields used for KPI or gauge visual thresholds.  
- Complaints: Numeric field used for aggregation and charting.  

## Dashboards

### Financial Complaints Overview Dashboard

- Displays total complaints, timely response percentage, dispute rate, and percentage resolved at no cost.  
- Visualizes top issues such as deposits/withdrawals, billing disputes, identity theft, underwriting, etc.  
- Provides a U.S. map view with complaint counts by state.  
- Includes a monthly trend view to show seasonality and complaint spikes.  
- Offers a tree-map of complaints by product type.  
- Shows consumer dispute distribution (Yes, No, N/A).  
- Allows filtering by date range and media/submission channel.  

## Dashboard Screenshot

![Financial Complaints Dashboard]!(Screenshot/Screenshot%20(143).png)

## Insights

Key insights illustrated in the dashboard include:

- 7,293 total complaints in the selected period.  
- 98.60% timely response rate, indicating strong responsiveness.  
- 100% dispute rate for selected filters or sample view.  
- 91.29% complaints resolved at no cost to consumers.  
- Deposits and withdrawals represent the highest issue category (1,213 complaints).  
- Credit card complaints are the most common product category (~4K).  
- Complaint volume varies significantly across states, with populous states showing higher counts.  
- Monthly trends indicate peaks during March (708) and other seasonal fluctuations.  
- Consumer dispute status shows Yes: ~9.7%, No: ~41%, N/A: ~49%.  

## How to Use

1. Download the `.pbix` file from this repository.  
2. Open it in Power BI Desktop.  
3. Use the date and submitted via filters to refine the view.  
4. Hover over visuals to reveal tooltip-level detail.  
5. Explore issue types, dispute outcomes, and product-level breakdowns for deeper insights.  

## Future Enhancements

- Add drill-down pages for company-specific complaint analytics.  
- Integrate sentiment scoring using consumer complaint narratives.  
- Add model-based forecasting for monthly complaint volumes.  
- Expand geospatial analysis to ZIP or county-level mapping.  
- Include additional KPIs such as refund amounts or resolution times (if data available).  
