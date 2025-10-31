# Olist E-Commerce Sales Performance Dashboard

## Objective
The goal of this 5-day intern project was to analyze Olist’s e-commerce sales, delivery performance, and customer satisfaction. An interactive 4-page Power BI dashboard was built to help Executives, Sales, Marketing, and Operations teams make data-driven decisions.

## Dataset
- **Source:** Brazilian E-Commerce Public Dataset by Olist (available on Kaggle)
- **Number of rows/columns:** 9 CSV files, ~100,000+ orders
- **Key columns:** `order_id`, `customer_id`, `order_status`, `order_purchase_timestamp`, `order_delivered_customer_date`, `order_estimated_delivery_date`, `payment_type`, `review_score`, `product_id`, `price`, `freight_value`

## Folder Structure
- **BRD/** - Business Requirements Document
- **FRD/** - Functional Requirements Document
- **Data/** - Raw dataset, cleaned data, and column assessment
- **Visuals/** - Dashboard mockups
- **PowerBI/** - Final `.pbix` file and PDF export
- **Reports/** - The final `Analysis_Report.pdf`

## Steps to Reproduce
1.  **Day 1: Requirements:** Loaded the dataset and documented business requirements in the `BRD.pdf`.
2.  **Day 2: Cleaning:** Assessed the dataset for quality and performed cleaning/transformation in Power Query.
3.  **Day 3: Design:** Defined functional requirements in the `FRD.pdf` and created dashboard mockups.
4.  **Day 4: Development:** Built the 4-page Power BI dashboard, created the data model, and wrote all DAX measures.
5.  **Day 5: Analysis:** Finalized the dashboard, exported reports, and prepared the final `Analysis_Report.pdf` with insights and recommendations.

## Key Insights / Learnings
-   **The "Faster but Later" Paradox:** The project's key finding was that Olist's `On-Time Delivery %` was decreasing even while its `Avg. Delivery Days` was improving. This proved the business problem was **inaccurate delivery estimates**, not slow shipping.
-   **Strategic Product Segmentation:** The Sales dashboard clearly segmented products into high-value (`watches_gifts`) and high-volume (`sports_leisure`), informing different sales strategies.
-   **Actionable Seller Performance:** The "Seller Report Card" on the Operations page provides a clear, data-driven list of low-performing sellers who are negatively impacting customer satisfaction.