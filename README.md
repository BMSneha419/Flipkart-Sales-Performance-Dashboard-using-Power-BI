# Flipkart-Sales-Performance-Dashboard-using-Power-BI
## Project Overview

This Power BI dashboard provides a comprehensive and interactive analysis of Flipkart's sales performance. It offers key insights into overall sales trends, product-level performance, and crucial customer and operational metrics. The dataset is sourced from Kaggle.

## Dashboard Pages & Insights

The dashboard is structured into three logical pages, each addressing specific business questions:

### Page 1: Sales Overview & Trends

**Purpose:** To provide a high-level summary of overall sales performance and identify key trends over time.

#### Visualizations & Insights:

1.  **KPI Cards (Total Sales (INR), Total Quantity Sold, Total Orders, Average Order Value)**
    * **Purpose:** Provide an at-a-glance summary of the most critical business metrics.
    * **Insights:**
        * **Total Sales:** The business generated **₹75 Million** in total revenue across the entire dataset period.
        * **Total Quantity Sold:** **3,097 individual units** were sold.
        * **Total Orders:** There were **1,000 unique customer orders**.
        * **Average Order Value:** The average customer transaction value is **₹75,210**. This indicates a solid typical spend per order, which can guide upselling strategies.

2.  **Monthly Sales Trend**
    * **Purpose:** To visualize sales performance over time, identifying patterns, seasonality, and significant changes.
    * **Insights:**
        * **Peak Performance:** Sales peaked in **July 2024**, reaching approximately **₹7.6 Million**. This could correspond to a major sale event or seasonal demand.
        * **Significant Decline:** A sharp drop is observed in **February 2025**, with sales plummeting to around **₹1.5 Million**. This represents a significant decline (approx. 74% from January 2025's apparent peak) and requires immediate investigation into potential causes (e.g., data cut-off, market conditions, operational issues).
        * **Seasonality:** A general pattern of strong sales from **March to July**, a slight dip, followed by a pickup towards **November-December**, suggests potential seasonal influences or holiday shopping patterns.

3.  **Sales by Day of Week**
    * **Purpose:** To understand sales distribution across different days of the week and identify peak/off-peak periods.
    * **Insights:**
        * **Top Sales Days:** **Saturday (₹12.1 Million)** and **Wednesday (₹11.7 Million)** are the highest-performing sales days, indicating strong weekend and midweek customer activity.
        * **Lowest Sales Day:** **Tuesday** records the lowest sales at **₹9.6 Million**, suggesting it's a potential day for targeted promotions to boost activity.


### Page 2: Product Performance

**Purpose:** To provide detailed insights into product and category sales, identify top performers, and analyze product characteristics.

#### Visualizations & Insights:

1.  **Sales by Category & Product**
    * **Purpose:** To visually represent the sales contribution of hierarchical data (categories and products within them).
    * **Insights:**
        * **Dominant Category:** **Electronics** is clearly the leading sales category, indicating its high revenue contribution.
        * **Top Products within Categories:** Within Electronics, **Laptop (approx. ₹4 Million)** and **Smartphone** are significant revenue drivers. This highlights key product lines for focused attention.
        * **Sales Distribution:** The treemap effectively illustrates that sales are concentrated in a few key categories and specific products, guiding strategic resource allocation.

2.  **Unit Price vs. Quantity Sold by Product**
    * **Purpose:** To explore the relationship between a product's average unit price and its sales volume, with bubble size representing total sales.
    * **Insights:**
        * **"Star" Products:** Identifies products with both high unit prices (e.g., approaching **₹30K**) and high quantity sold (e.g., **~190 units**), represented by larger bubbles. These are highly valuable products.
        * **Strategic Segmentation:** Reveals clusters of products, such as those in the mid-range price (₹20K-₹25K) with moderate quantities (100-120 units), helping to categorize products for different sales strategies.
        * **Outlier Detection:** Helps to spot products that deviate from typical price-volume relationships, warranting further investigation.

3.  **Top 10 Products by Sales**
    * **Purpose:** To provide precise, sortable numerical data for the highest-performing individual products.
    * **Insights:**
        * **Top Product:** **Educational Book** is the highest-selling product by value, generating **₹45,22,055** from **188 units sold**.
        * **Specific Performance:** Provides exact figures for other top products like **Headphones (₹37,22,765, 135 units)** and **Fiction Novel (₹31,73,000, 138 units)**.
        * **Contribution of Top Products:** The combined sales of the top 10 products exceed **₹3.69 Crore**, highlighting their significant contribution to overall revenue.


### Page 3: Customer & Operational Insights

**Purpose:** To understand customer satisfaction through ratings and analyze operational aspects like payment methods.

#### Visualizations & Insights:

1.  **Sales by Payment Method**
    * **Purpose:** To show the proportional contribution of each payment method to total sales.
    * **Insights:**
        * **Primary Payment Channels:** **Wallet (17.88%),** **Net Banking (17.58%)** and **UPI (17.01%)** are the most popular payment methods by sales contribution, indicating a strong customer preference for these digital options.
        * **Balanced Distribution:** Sales are relatively balanced across various payment methods (each contributing between 14-18%), suggesting robust support for diverse customer preferences.

2.  **Average Customer Rating**
    * **Purpose:** To provide a quick, visual indication of overall customer satisfaction against a set target.
    * **Insights:**
        * **Performance Gap:** The current average customer rating of **3.0** is below the target of **4.0**, clearly signaling an area that requires attention for improving customer satisfaction. The gauge's color (likely a warmer tone) further emphasizes this.

3.  **Sales by Customer Rating**
    * **Purpose:** To analyze the revenue contribution from products with different customer rating levels.
    * **Insights:**
        * **Value of High Ratings:** The majority of sales revenue is driven by products with **4-star ratings (approx. ₹2.8 Million)** and **3-star ratings (approx. ₹2.5 Million)**, directly demonstrating the financial benefit of high customer satisfaction.
        * **Impact of Low Ratings:** Products with **1-star ratings** contribute the sales (around **₹2.6 Million**), highlighting specific problem areas.

4.  **Orders by Customer Rating & Product**
    * **Purpose:** To provide a detailed breakdown of products within each customer rating category, showing specific items and their associated order counts.
    * **Insights:**
        * **Problem Identification:** Specific products like **Headphones (average rating 2.8, 44 orders)** and **Lipstick (average rating 2.8, 44 orders)** can be identified as having lower customer satisfaction, allowing for targeted product improvements or customer service interventions.
        * **Volume & Rating Correlation:** Allows deeper analysis into whether high-volume products are maintaining good ratings, or if popular items are causing satisfaction issues.
