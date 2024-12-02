# Sales Data Analysis Using Python
This project involves analyzing a dataset of customer sales for a clothing company, applying advanced data analytics and business intelligence techniques to uncover insights that drive business decision-making. The project highlights how data analysis can solve business challenges such as improving sales performance, identifying top-performing regions and products, reducing cancellations, and optimizing inventory. The goal is not only to explore the data but to propose actionable strategies based on data insights

![](how-to-choose-the-right-e-commerce-agency.jpeg)
---

### Introduction
The goal of this analysis is to leverage data analytics to generate business insights that can inform strategic decisions. By identifying trends in sales data, understanding customer preferences, and detecting operational inefficiencies, the analysis aims to help the company improve sales, customer satisfaction, and operational efficiency. The project combines technical data processing with business intelligence to propose strategies for growth and optimization.


### Tools
- Programming Language: Python
- Libraries Used:
- pandas for data manipulation
- numpy for numerical operations
- matplotlib and seaborn for data visualization

Academic Rigor: Applied robust data analysis techniques, including exploratory analysis, trend identification, and correlation analysis.

Practical Impact: Delivered actionable insights for inventory optimization, seasonal marketing, and operational improvements.

### Dataset Overview
The dataset consists of the following fields:

- Order Details: Order ID, Status, Fulfillment, Sales Channel
- Product Details: Category, Size, Qty, Amount
- Shipping Information: ship-city, ship-state, ship-country
- Temporal Details: Month extracted from date fields
- Additional Fields: B2B indicator, courier details, and more

  ### Key Steps and Workflow
1. Data Cleaning
- Checked and removed duplicate records.
- Addressed missing values by excluding or imputing where appropriate.
Converted Date column to datetime format and extracted the Month column for temporal analysis.
2. Exploratory Data Analysis (EDA)
#### State-Wise Sales
- Maharashtra was identified as the top-performing state, contributing 16% of total sales.
- Karnataka and Delhi followed in second and third place, respectively.
- This highlights Maharashtra’s importance for marketing and inventory strategies.
#### Category Analysis
- T-shirts dominated sales, outperforming all other categories significantly.
- The high demand for T-shirts suggests focusing marketing efforts and optimizing inventory levels for this product line.
#### Size Preferences
- Large (L) and Extra-Large (XL) were the best-selling sizes, accounting for the majority of sales volume.
- Medium (M) saw increased demand during April, which could indicate seasonal preferences.

#### Monthly Sales Trends
- April emerged as the highest-grossing month, exhibiting a significant spike in sales.
##### The spike in April is attributed to:
- Increased sales of T-shirts.
- A noticeable preference for Medium-sized items.
#### Status Analysis
- The "Shipped - Delivered to Buyer" status dominated by a wide margin, reflecting efficient order fulfillment processes.
- Lower statuses, such as "Cancelled" and "Returned," were minimal but could indicate areas for customer satisfaction improvement.

#### 3. Correlation Analysis
_- The analysis focused on numerical relationships (e.g., between Amount, Qty, and other fields)_
- Amount and Qty showed a strong positive correlation, as expected (0.87), confirming higher quantities lead to higher sales.
- Non-numerical variables such as ship-state and Category were also encoded for potential exploration but were excluded for simplicity.

#### 4. Visualizations
Barplots for categorical data (e.g., ship-state, Category, and Size) revealed the top-performing segments.
Line and bar graphs for temporal trends demonstrated April's spike in sales.
Heatmaps for correlation highlighted relationships between numerical fields.
