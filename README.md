swiggy  Dashboard
I am excited to share that my latest swiggy  sales Dashboard 
## Dataset  
<a href="https://github.com/gauravSingh0106/Analyst-Project/blob/main/BlinkIT%20Grocery%20Data%20(1).xlsx">Swiggy Dashboard</a>

**Dashboard Link**
 <a href="https://github.com/gauravSingh0106/Analyst-Project/blob/main/PBIDesktop_G6BAyKjkXr.png">Dashboard Image</a> 


<image width="1374" height="771" alt="PBIDesktop_G6BAyKjkXr" src="https://github.com/user-attachments/assets/7934a9e6-7d83-4436-916e-2e54fa318dcf" />

## Project Overview
This project focuses on analyzing customer purchasing patterns, outlet performance, and product category sales for **Swiggy's Grocery Segment (2026 Analysis)**.<br>
The goal was to transform raw transactional data into an interactive visual dashboard in Power BI, 
<br>enabling stakeholders to evaluate revenue drivers, store expansion trends, customer ratings, and item distribution.
<br>
##  Key KPI Summary <br>
* **Total Sales Revenue:** $1.20M<br>
* **Average Order Value / Item Sales:** $141<br>
* **Total Line Items Processed:** 8,523 <br>
* **Average Customer Rating:** 3.97 ★ (~ 4.0 Stars)<br>
* **Maximum Item Sale:** $266.89<br>
* **Minimum Item Sale:** $31.29<br>
* **Total Active Outlets:** 10 Outlets <br>
* **Unique SKUs:** 1,559 (~2K unique items)<br>

## Business Questions Addressed
1. What is the total revenue generated across all product categories and outlet types? <br>
2. How do sales vary across different store locations (Tier 1, Tier 2, and Tier 3 cities)?<br>
3. Which outlet types (Supermarkets vs. Grocery Stores) deliver the highest revenue and volume?<br>
4. How has outlet establishment evolved over time, and what is its historical impact on revenue?<br>
5. Which product categories (e.g., Fruits & Vegetables, Snack Foods, Household) contribute the most to top-line sales?<br>
6. Does customer preference lean toward Low Fat vs. Regular fat content products across location tiers?<br>

### 3. Key DAX Measures Used
 1. Total Sales Revenue<br>
Total Sales = SUM('BlinkIT Grocery Data'[Sales])<br>

 2. Average Sales per Item<br>
Avg Sales = AVERAGE('BlinkIT Grocery Data'[Sales])<br>

 3. Total Items Sold<br>
No of Items = COUNT('BlinkIT Grocery Data'[Item Identifier])<br>

4. Average Customer Rating<br>
Avg Rating = AVERAGE('BlinkIT Grocery Data'[Rating])<br>

 5. Max Item Sale<br>
Max Sales = MAX('BlinkIT Grocery Data'[Sales])<br>

6. Min Item Sale<br>
Min Sales = MIN('BlinkIT Grocery Data'[Sales])<br>

**Key Business Insights**
**Top Revenue Generators:**

Fruits & Vegetables ($0.18M) and Snack Foods ($0.18M) are the highest-selling categories,<br> followed closely by Household Goods ($0.14M) and Frozen Foods ($0.12M).<br>

Low-margin/low-demand items like Seafood ($0.01M) and Breakfast items ($0.02M) contribute minimal share.<br>

**Outlet Type Dominance:**<br>

Supermarket Type 1 accounts for the vast majority of total sales ($787.5K out of $1.20M),<br> driving over 65% of overall business volume.<br>

Grocery Stores generate $151.9K with higher transaction volume relative to size,<br> while Supermarket Type 2 ($131.5K) and Type 3 ($130.7K) maintain steady baseline performance.<br>

**Geographic Distribution** (City Tiers):<br>

Tier 3 cities yield the highest overall sales revenue ($0.51M total across formats),<br> driven heavily by high product volume.<br>

Tier 2 ($0.45M) and Tier 1 ($0.25M) show strong concentration of high-value items,<br> indicating higher average basket values in urban clusters.<br>

**Customer Health Preferences**:<br>

Products classified as Low Fat generate roughly $776K (64.6%) of sales compared to Regular products ($425K / 35.4%),<br> reflecting clear consumer preference for healthy/low-fat packaged goods.<br>

**Historical Establishment Trend**:<br>

Peak store expansion occurred around 2018–2019 (reaching $0.20M contribution),<br> after which sales stabilized at a healthy baseline of ~$0.13M per establishment cohort.<br>











