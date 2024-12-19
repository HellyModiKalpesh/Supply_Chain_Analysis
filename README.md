# Supply Chain Analysis

## Live Dashboard
[View the Live Dashboard Here](https://app.powerbi.com/view?r=eyJrIjoiMWZhNTg2ZjQtMzhkOS00OTVmLWJjZDMtYTIxM2NiZmZmNjVlIiwidCI6ImZlMzQ2NjBjLWI3MjgtNDI0NC05MDRhLTUwNDg4MTNjZjIzMCJ9&pageName=5d5e5d762697add52859)

## Project Overview
AtliQ Mart, a fast-growing FMCG manufacturer headquartered in Gujarat, India, operates in Surat, Ahmedabad, and Vadodara, with plans to expand to other metro and Tier 1 cities in the next two years. However, service issues have led to the non-renewal of contracts by some key customers, largely due to challenges in timely and complete order deliveries. This project aims to create a supply chain analytics dashboard to monitor service levels daily and enable quick responses to delivery issues.

## Problem Statement
AtliQ Mart faces customer churn due to gaps in service quality, with delays in delivery and incomplete orders being key contributors. To address these issues before expanding into new markets, AtliQ Mart's supply chain analytics team needs a solution to track:
- **On-Time Delivery (OT%)**
- **In-Full Delivery (IF%)**
- **On-Time In-Full Delivery (OTIF%)**

These metrics are measured against target service levels set for each customer. The insights will support proactive management of delivery performance to improve customer retention.

## Project Goals
1. **Develop Key Metrics**: Calculate OT%, IF%, and OTIF% for each customer on a daily basis.
2. **Create a Dashboard**: Visualize metrics and insights to enable the supply chain team to monitor and act on delivery performance.
3. **Generate Actionable Insights**: Highlight performance trends and customer segmentation insights to prioritize improvements.

![image](https://github.com/user-attachments/assets/59123c86-e91c-4e3d-8e4c-0bdf73f1973d) ![image](https://github.com/user-attachments/assets/a1e24771-77be-43e1-bcf1-d1485055992a) ![image](https://github.com/user-attachments/assets/8df47a69-6483-4ffd-b1b7-652a123e193b)  ![image](https://github.com/user-attachments/assets/e692b002-e593-41ec-92fb-bb5737dfc0a7)

## Key Insights

1. **Service Level Metrics**
On-Time Delivery (OT%): Currently at 59.03%, below the target of 86.09%, highlighting significant delays.
In-Full Delivery (IF%): At 52.78%, against a target of 76.51%, indicating frequent issues with incomplete orders.
On-Time In-Full Delivery (OTIF%): Low OTIF of 29.02% compared to the target of 65.91% shows challenges in meeting customer expectations for complete and timely deliveries.
Late Delivery (LD%): Stands at 40.97%, reflecting a high rate of delayed deliveries.
Line Fill Rate (LFR%): At 66%, suggesting partial fulfillment issues in some orders.
Volume Fill Rate (VFR%): At a high 96.59%, showing that while volume goals are mostly met, the timing and completeness of these deliveries remain problematic.

2. **City-Level Performance**
Ahmedabad: Shows the highest In-Full (IF) performance among the three cities but falls short on OT and OTIF metrics.
Surat: Achieves the highest OTIF% among cities, yet it remains below the target. Improvements in on-time and complete deliveries are needed.
Vadodara: Records the lowest performance in on-time deliveries, representing a significant area for improvement.

3. **Customer Segmentation**
Customers are segmented into three main clusters:

Bulk Buyers: Low order frequency but large order quantities. These customers buy in bulk infrequently and have unique needs for timely and complete deliveries.
High-Value Frequent Buyers: Customers with high order frequency and large average order sizes. These loyal and high-value customers, such as VIP or business accounts, require consistent service quality.
Steady Shoppers: Moderate frequency and order size, with predictable buying patterns. Maintaining service levels for these customers is essential for steady revenue.
Key At-Risk Customers:

Lotus Mart, Cool Blue, and Acclaimed Stores are high-value customers with high order volumes but exhibit low OTIF scores, frequent late deliveries, and significant delays. Their retention is crucial to revenue, and improving their service levels is a priority.

4. **Product Demand Insights**
High Demand Products: AM Butter (500g), AM Ghee (150g, 250g), and AM Milk (250ml) are in high demand, indicating customer preference.
Low Demand Products: Products like AM Tea (100g) and AM Ghee (50g) have lower demand, suggesting the need to adjust inventory strategy to prevent overstocking.
Delivery Delays by Product: High delay rates for dairy products, especially butter, milk, and curd, indicate areas for improvement in the delivery process to avoid stockouts and meet customer demand.

5. **Monthly Delivery Performance**
May: Records the highest number of late deliveries, with 2,874 occurrences, followed by a gradual decline to 2,678 in August. This trend suggests a need for seasonal performance analysis and improvements in logistics during peak months.

6. **Customer Lifetime Value (CLV)**
Estimated using order frequency and average order quantity, CLV analysis highlights Lotus Mart and Acclaimed Stores as top contributors to revenue, emphasizing the need for targeted retention efforts for these valuable clients.

## Getting Started

Clone or download this repository.
Open the .pbix file in Power BI to explore the interactive dashboard.
Review the insights and recommendations to understand and interact with the supply chain dashboard.
