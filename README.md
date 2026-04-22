# Freshco-Hypermarket-business-analysis
interactive Excel dashboard
- To monitor and evaluate hypermarket delivery performance, customer ordering trends, and overall sales volume.
  
- Developed an interactive Excel dashboard utilizing Pivot Tables and VLOOKUPs to track KPIs and conducted a deep dive into delivery lag times and order-completion rates.
  
- Provided stakeholders with a clear visual representation of operational bottlenecks, enabling data-driven decisions that improved delivery efficiency and customer satisfaction levels.
- The hypermarket was experiencing a "blind spot" in its last-mile delivery: customers were complaining about delays, but management couldn't pinpoint if the issue was in the warehouse (picking), the transit (logistics), or specific peak hours. Additionally, sales reports were static, making it difficult to adjust inventory based on emerging ordering trends.
- I designed a centralized data hub in Microsoft Excel to monitor the end-to-end order lifecycle:
Data Architecture: Unified three disparate datasets—Point-of-Sale (POS) logs, delivery fleet GPS timestamps, and customer feedback—using Power Query and VLOOKUP/INDEX-MATCH.
. KPI Engineering: Developed dynamic calculations for critical retail metrics
. Delivery Lag Time: Calculated the delta between "Order Placed" and "Out for Delivery" to find internal processing delays.
. Order Completion Rate: Tracked the ratio of successful deliveries vs. returns/cancellations.
. Sales Velocity: Measured sales per hour to identify "Golden Hours" for staffing.
. Interactive Dashboarding: Built a visual control center with Slicers and Timelines, allowing managers to drill down into specific delivery zones or product categories

- Targeted Bottleneck Removal: Identified a consistent 45-minute delay in the 5 PM–7 PM window caused by a shortage of evening "pickers," leading to a 15% adjustment in staff shifts.
- Improved Efficiency: Reduced delivery lag times by 12% within the first month by re-optimizing dispatch routes based on zone-specific performance data.
- Sales Growth: Highlighting "Customer Ordering Trends" allowed the marketing team to launch targeted 2-hour "flash sales" during low-traffic periods, increasing overall sales volume by 8%.
