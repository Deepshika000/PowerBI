# IndiaKart E-Commerce Performance Analytics (Power BI)

## 📌 Project Overview

The **IndiaKart Analytics Dashboard** is a comprehensive Business Intelligence solution built in Power BI to analyze end-to-end e-commerce operations. This project integrates multiple operational domains—including customer behavior, inventory health, order fulfillment, product revenue, and supplier efficiency—into an interactive multi-page dashboard designed to drive data-informed decision-making.

---

## 🛠️ Key Dashboard Pages & Features

### 1. Customer Performance

* **Demographic & Geographical Analysis:** Tracks active customer distribution across 18 states and 50 cities, highlighting top regions like Uttar Pradesh ($1,860$ active customers).


* **Customer Segmentation & Spend:** Categorizes user bases into *Regular*, *Premium*, *Budget*, *New*, and *Inactive* segments alongside gender-based expenditure breakdowns.


* **Top Customer Tracking:** Pinpoints top individual buyers by total order volume.



### 2. Inventory Performance

* **Warehouse Availability:** Monitors stock quantities distributed across regional fulfillment centers (Chennai, Delhi, Kolkata, Hyderabad, Bengaluru, Mumbai).


* **Stock Health & Re-Order Tracking:** Segregates inventory statuses (*In Stock*, *Low Stock*, *Out of Stock*) to prevent supply chain bottlenecks.


* **Category Inventory:** Analyzes reserved vs. available quantities across major product categories like *Electronics*, *Sports & Fitness*, and *Grocery*.



### 3. Order Item Performance

* **Taxation & Pricing Dynamics:** Evaluates average GST rates (averaging $12.30\%$), unit prices, and total price distribution across product lines.


* **Revenue vs. Profit Margin:** Identifies top revenue-generating categories (e.g., *Electronics* leading at $1520\text{M}$) against low-performing SKUs needing promotional re-alignment.


* **Discount Impact:** Tracks discount percentages ($\text{Avg D}\%$) across categories to measure profit margin preservation.



### 4. Order Performance & Logistics

* **Fulfillment & Channels:** Compares sales channel distribution (*App*, *Website*, *Mobile Web*) and order fulfillment statuses (*Delivered*, *Cancelled*, *Shipped*, *Returned*, *Processing*).


* **Payment Method Preferences:** Analyzes consumer adoption across payment modes (UPI, Credit/Debit Cards, Cash on Delivery, EMI, Wallets).


* **Shipping & Partner Logistics:** Tracks monthly order trends alongside logistics workload distributed across primary shipping partners (e.g., Amazon, BlueDart, Delhivery, DTDC).



### 5. Product Performance

* **SKU & Brand Breakdown:** Evaluates over $1,000$ products across $40$ brands, tracking cost price, selling price, total revenue, and overall profit percentage.


* **Rating & Customer Reviews:** Correlates review counts and average customer ratings ($3.20$ to $4.90$) with subcategory profitability.



### 6. Supplier Performance

* **Vendor Efficiency:** Evaluates vendor cost contributions, profit yield, and total revenue across $200$ suppliers.


* **Payment Terms Analysis:** Analyzes vendor payment terms (ranging from $90$ to $135$ days) to optimize cash flow management.



---

## 📈 Key Business Insights & Problem Solved

* **Targeted Marketing:** Identified key demographic drivers (e.g., Uttar Pradesh contributing $18.60\%$ of total customer base), enabling optimized regional ad spend.


* **Stock Optimization:** Established clear visibility into stock-out risks across regional warehouses to balance re-order thresholds.


* **Margin Preservation:** Highlighted high-volume, low-margin products to refine discounting and pricing strategies.


* **Operational Efficiency:** Pinpointed fulfillment bottlenecks by tracking cancellation and return rates across payment and channel metrics.


* **Supplier Risk Management:** Streamlined procurement decisions by analyzing top-performing suppliers vs. extended payment terms.



---

## 💻 Tech Stack & Tools

* **BI Tool:** Power BI Desktop
* **Data Modeling:** DAX (Data Analysis Expressions), Star Schema Modeling
* **Data Transformation:** Power Query ETL
* **Data Source:** E-Commerce Operational Datasets (CSV / SQL)

---

## 🚀 How to View the Report

1. Clone this repository to your local machine:
```bash
git clone https://github.com/your-username/indiakart-powerbi-analysis.git

```


2. Open the `.pbix` file using **Power BI Desktop**.
3. Use the page navigation arrows at the bottom right of each screen to navigate between performance dashboards.
