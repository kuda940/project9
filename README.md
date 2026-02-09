# project9

Pizza Sales Data Analysis
📌 Project Overview

This project analyzes pizza sales data to uncover trends in customer orders, revenue, and product performance. The goal is to use data analysis to help a pizza business make better decisions about menu items, pricing, and sales strategies.

🎯 Objectives

Analyze total sales and revenue

Identify best-selling and worst-selling pizzas

Understand peak ordering days and times

Explore customer ordering patterns

Provide data-driven business insights

🛠 Tools & Technologies

Python (Pandas, NumPy)

Matplotlib & Seaborn for data visualization

Jupyter Notebook

Excel/CSV dataset

📊 Key Analysis Performed

Merged 3 tables: the orders table, pizza, and pizza type
✔ Data cleaning and preprocessing
✔ Revenue and sales trend analysis
✔ Top-performing pizza categories and sizes
✔ Busiest days and hours for orders
✔ Visualization of sales performance
Visualized sales by Quater


📈 Key Insights

🍕 The highest revenue comes from Thai Chicken

📅 Sales peak on [on Fridays]

⏰ Most orders are placed around [12pm to 5pm]

📉 Some pizza types have low sales and could be reviewed

(Replace these with your actual findings)

📂 Dataset

The dataset contains pizza order details including:

Order ID

Pizza name & category

Size

Quantity

Price

Date and time of order

🚀 How to Run This Project
pip install pandas numpy matplotlib seaborn


Then open the notebook:

jupyter notebook


Run all cells to reproduce the analysis.

💡 Future Improvements

Build a sales dashboard (Power BI / Tableau)

Add demand forecasting

Create a recommendation system for best-selling combos( ## Summary:

### Data Analysis Key Findings
*   Individual pizza items within orders were standardized into `(pizza_type_id, size)` tuples and aggregated by `order_id`.
*   These aggregated lists were further standardized into sorted tuples to represent unique, order-independent combos, stored in a `combo` column.
*   The frequency of each unique standardized combo was counted and ranked.
*   The top 10 best-selling pizza combos were identified, with the leading combos being predominantly single-pizza orders:
    *   `((big_meat, S),)` occurred 319 times.
    *   `((five_cheese, L),)` occurred 243 times.
    *   `((thai_ckn, L),)` occurred 230 times.
    *   `((four_cheese, L),)` occurred 213 times.
    *   `((spicy_ital, L),)` occurred 213 times.
    *   Other top sellers included `((classic_dlx, L),)`, `((pepperoni, L),)`, `((bbq_ckn, L),)`, `((cali_ckn, L),)`, and `((supreme, L),)`.

### Insights or Next Steps
*   **Menu Optimization & Promotions**: The prevalence of single-pizza orders among the top sellers suggests that these individual pizzas are highly popular. The business could focus on promoting these specific pizzas, potentially offering discounts on larger sizes or creating complementary side item bundles.
*   **Investigate Combo Potential**: While single-item "combos" dominate, further analysis could involve looking beyond the top 10 to identify multi-pizza combinations that, while less frequent, show consistent popularity, indicating potential for new bundled offerings.
future Improvements are:
1. Optimize Product Offerings and Promotions:

Focus on Top Performers: Continue to heavily promote and ensure consistent availability of top-selling pizza types like 'Thai Chicken', 'BBQ Chicken', 'California Chicken', 'Classic Deluxe', and 'Spicy Italian'. These are your revenue drivers.
Leverage Large Sizes: Since Large (L) pizzas generate the most revenue, consider strategies that encourage upsizing, such as attractive family deals or slight discounts on larger sizes.
Re-evaluate Low Performers: Review pizza types like 'Brie Carre' and 'Green Garden'. Consider rebranding, ingredient changes, bundling them with popular items, or even removing them from the menu if they consistently underperform and don't contribute significantly to variety or niche appeal.
Explore Combo Potential: While single-pizza orders dominate the top combos, investigate multi-pizza combinations that appear frequently, even if outside the top 10. These could be untapped opportunities for new bundled offerings.
2. Strategic Marketing and Operations by Time & Season:

Capitalize on Peak Hours (Lunch: 12-1 PM, Dinner: 5-7 PM):
Ensure maximum staffing in kitchen and delivery during these times to handle high volume efficiently and maintain service quality.
Run targeted promotions for quick lunches or family dinners that emphasize speed and value.
Pre-order incentives could smooth demand peaks.
Boost Off-Peak Hours (Morning, Late Night, Mid-Afternoon):
Introduce "Happy Hour" discounts or special offers on specific pizza types/combos during these slower periods to drive traffic.
Target specific customer segments (e.g., offices for early afternoon snacks, late-night study groups).
Address Off-Peak Months (October, November, December):
Develop seasonal menus or limited-time offers (LTOs) that align with cooler weather comfort food themes. Our analysis showed top off-peak sellers often include hearty, chicken-based options.
Increase marketing spend or run special holiday promotions to stimulate demand in these months.
Consider loyalty program bonuses for purchases made in off-peak months to build customer retention.
3. Data-Driven Decision Making & Further Research:

Investigate Sales Drivers: Conduct further research into why certain pizzas perform well in specific periods. This could involve:
Customer Surveys: Ask customers about their preferences for ingredients, flavors, and sizes, and how these change with seasons or mood.
External Factors: Actively integrate and analyze external data such as local events, holidays, and weather patterns (as discussed, this requires external data acquisition) to understand their correlation with sales.
Competitor Analysis: Monitor competitor pricing and promotions during peak/off-peak times and for similar pizza types.
Profitability Analysis: Beyond just total sales, analyze the profitability of each pizza type, size, and combo to ensure that high-revenue items are also high-profit items.
By implementing these recommendations, the pizza business can better align its strategies with customer behavior and market dynamics, leading to increased revenue and operational efficiency.



👤 Author

Your Name
Kudakwashe Nyamatendedza | Turning data into business insights

 🔥
