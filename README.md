![artem-gavrysh-F6-U5fGAOik-unsplash](https://github.com/Md-Kaif-Tahir/Madhav-Store-Dashboard-On-PowerBI/assets/110182266/1ac710a0-1ba9-47fa-ac87-be0c9e32626d)


# Madhav Store Dashboard on PowerBI 🚀
_**Empowering Growth: Dynamic Sales Dashboard**_

## Author
- [@Mohammad Kaif Tahir](https://github.com/Md-Kaif-Tahir) ☕🌟

## Table of Contents
- [Project Scope](#project-scope) 🎯
- [Data Source](#data-source) 📂🔍
- [Data Overview](#data-overview) 📊
- [Method](#method) 📈
- [Selection Of KPIs](#selection-of-kpis) 🎯
- [Quick Glance At The Dashboard](#quick-glance-at-the-dashboard) 👀🚀
- [Charts and Visualisation Options](#charts-and-visualisation-options) 📊🎨
- [Steps in Data Cleaning](#steps-in-data-cleaning) 🛠️🧹
- [Data Filters](#data-filters) 🗺️🔍
- [Business Suggestions](#business-suggestions) 💡🚀

## Project Scope
The visionary team at **Madhav Store** has collaborated to create a vibrant dashboard, dissecting online sales across India. With a commitment to leveraging technology, the management aims to empower decision-making for growth. 📊🌐

## Data Source
- [Madhav Store Dataset](https://www.kaggle.com/datasets/mohammadkaiftahir/madhav-store-dataset) 📂🔍

## Data Overview
- **Orders CSV Dataset**<br>
  - Key insights into order processes, including order ID, date, customer details, state, and city.

| **Column**            | **Description**            |
|-----------------------|----------------------------|
| Order ID              | Unique identifier for each order. |
| Order Date            | Date of order placement.    |
| Customer Name         | Customer's name.            |
| State                 | Customer's residing state.  |
| City                  | Customer's residing city.   |

- **Details CSV Dataset**<br>
  - Detailed order information, including order ID, amount, profit, quantity, category, sub-category, and payment mode.

| **Column**            | **Description**            |
|-----------------------|----------------------------|
| Order ID              | Matches order ID from "Orders CSV" dataset. |
| Amount                | Total order amount.         |
| Profit                | Profit generated from the order. |
| Quantity              | Quantity of products ordered. |
| Category              | Broad category of the product. |
| Sub-Category          | Specific sub-category of the product. |
| Payment Mode          | Payment method used for the order. |

## Method
- Exploratory data analysis _(EDA)_ 📈📉

## Selection Of KPIs
- **Total Amount of Sales:** Overview of store revenue.
- **Total Profit:** Net profit earned by the store.
- **Order Quantity:** Insights into customer demand.
- **Average Order Value:** Reveals customer spending patterns.

## Quick Glance At The Dashboard 👀🚀
![Screenshot 2023-10-15 175445](https://github.com/Md-Kaif-Tahir/Madhav-Store-Dashboard-On-PowerBI/assets/110182266/5873aadc-2ecd-4060-9e3f-7e7f2d449191) 

## Charts and Visualisation Options 📊🎨

### 1. Profit By Month - Vertical bar chart
- Visualizes monthly profit distribution, aiding resource allocation and strategy planning. The bar format enhances the comprehension of financial performance across different months.

### 2. Profit By Sub-Category - horizontal bar chart
- Highlights the top 5 profitable subcategories for inventory and promotion decisions. The horizontal bar chart offers a clear comparison of subcategories, assisting in optimizing operations.

### 3. Sales Quantity By Category - Donut chart
- Represents the distribution of ordered categories based on total order quantity for strategic planning. A Donut chart provides a quick snapshot of category popularity and consumer preferences.

### 4. Top Performing States - Vertical bar chart
- Highlights top revenue-generating states for targeted marketing. A bar graph provides a visual representation of the performance of different states.

### 5. Sum of Quantity By Payment Method - Donut chart
- Displays customer choices among payment methods, emphasizing the popularity of COD and UPI. Understanding payment preferences is vital for a seamless customer experience.

### 6. Top Customer - Vertical Bar chart
-Customers with the highest number of sales done. Top 3 are Harivansh, Madhav, and Madan mohan.

## Steps in Data Cleaning 🛠️🧹
1. **Date Column Optimization:** In the 'orders' table, modified the 'order date' column data type from text to date. This enhances chart presentation, shifting the focus from daily to monthly profit analysis.

2. **Average Order Value Calculation:** Added a new column labeled 'Average Order Value' in the 'details' table, providing insights into customer spending patterns. The equation *AOV = [Amount] / [Quantity]* was applied, and the data type was adjusted to whole numbers.

## Data Filters 🗺️🔍

### Quarter Filter
Focus on specific quarters for detailed analysis and insights. This filter empowers users to zoom in on particular time segments.

### States Filter
Examine data on an individual state level for regional trends and preferences. This filter enhances the ability to understand regional variations.

## Business Suggestions 💡🚀

1. **Strategic Focus on Top States:** Direct marketing efforts and inventory strategies towards top-performing states. Tailoring promotions based on regional preferences could drive higher sales.

2. **Optimize Product Mix:** Leverage the dominance of the 'Clothing' category. Consider expanding product ranges and introducing new collections to cater to diverse consumer tastes.

3. **Leverage Profitable Months:** Plan campaigns and promotions during high-profit months, such as November. Further analysis during low-profit months can inform strategies to mitigate challenges.

4. **Cultivate Customer Relationships:** Engage with top customers through personalized offers and loyalty programs. Building strong relationships with key customers can lead to increased sales.

5. **Payment Method Diversity:** Ensure a seamless experience for popular payment methods like COD and UPI. Incentivize less-used methods such as Credit Card and EMI to increase profitability through reduced transaction fees.

6. **Optimize Top Selling Items:** Focus on consistent availability and explore bundling options for top-selling items. Analyzing customer feedback and preferences ensures these products continue to meet expectations. 💡📈
