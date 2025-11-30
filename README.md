# Business-Intelligence-Learning
# **Power BI & Tableau Dashboards – Global Superstore and Chocolate Sales**
This repository showcases four dashboards built in Power BI and Tableau using two datasets:

•	Global Superstore (retail sales across categories, regions, and time)

•	Chocolate company sales and shipments (products, months, and countries)

The goal of these projects is simple: practice turning raw sales data into clear, decision ready insights.

<h3>What Data Analytics Is</h3>

Data analytics is the process of collecting, cleaning, transforming, and interpreting data so it becomes useful information instead of just rows in a spreadsheet. In practice, that means checking data quality, exploring patterns, and visualizing results so they answer real questions like “Which products drive profit?” or “Why did revenue drop this quarter?”
For businesses, analytics reduces guesswork: it helps identify growth opportunities, find underperforming areas, optimize inventory, and react faster to market changes.

<h2>Project 1 – Global Superstore (Tableau: Furniture, Office Supplies, Technology)</h2>


![Screenshot 2025-11-29 235851](https://github.com/user-attachments/assets/27797d27-0545-48df-a61a-2d967019d3bb)



**Dataset:** Global Superstore sales for three main categories across the US.

**What I built:**

•	A US sales map, monthly trend lines, and category/sub category sales views.

**Key analysis and insights:**

•	Monthly Sales over Years: All three categories show stronger sales towards the end of the year, with November and December consistently peaking, while Technology is the most volatile with sharp spikes and dips across months.


![Screenshot 2025-11-29 235531](https://github.com/user-attachments/assets/d86285fa-2578-4388-a09b-8d987df618bf)



•	Category Wise Sales: Inside each category, a few sub categories dominate—Chairs and Tables in Furniture, Binders and Storage in Office Supplies, and Accessories in Technology—meaning these are the levers that will move total revenue the most.


![Screenshot 2025-11-30 000220](https://github.com/user-attachments/assets/f9f56bf3-033f-4ac2-ac0b-f0fbf57cb32d)


![Screenshot 2025-11-29 235427](https://github.com/user-attachments/assets/eb064351-30d4-4d85-9d98-e8fa5affc2ab)


•	Product Category Sales: Technology edges out Furniture and Office Supplies slightly in total sales, suggesting tech products are the main growth area but the business still relies on all three categories for stability.

**What this taught me:**

•	How to structure a Tableau dashboard so a user can move from high level (category totals) down to detailed sub category performance.

•	How seasonality and product mix combine to create the full sales picture, not just one chart in isolation.

<h2>Project 2 – Beverage Sales Dashboard (Power BI: Soft Drinks)</h2>


![Screenshot 2025-11-30 003822](https://github.com/user-attachments/assets/460c042b-d6f1-4270-91e7-868221469c5c)


**Dataset:** A drinks company’s sales in the US, with brands like Coca Cola, Diet Coke, Sprite and more.

**What I built:**

•	**A Power BI dashboard with:**

o	Map: Sum of Revenue by State

o	Bar chart: Sum of Units Sold by Month Name


![Screenshot 2025-11-30 003747](https://github.com/user-attachments/assets/2dd6099c-62f1-43f9-9a79-adef217e8c81)



o	Donut chart: Sum of Revenue by Month Name


![Screenshot 2025-11-30 003807](https://github.com/user-attachments/assets/225c7336-cffc-4c06-acb1-36a7264152b3)



o	KPI cards for total revenue, total units, and average price per unit.

**Key analysis and insights:**

•	Sum of Units Sold by Month: Units sold are steady but clearly higher mid year, with July, August, and December standing out as the strongest months, which likely aligns with holidays and warm weather demand.

•	Sum of Revenue by Month (donut): Revenue share is also heavier in those same months, confirming real seasonality rather than random variation—great months to double down on promotions and stock planning.

•	Combined with the map, it becomes easy to see which states are both high volume and highly seasonal, helping the business plan region specific campaigns instead of treating the whole country the same.

**What this taught me:**

•	How to use Power BI to tie KPIs, maps, and time series charts into a single, clean story.

•	How small differences in monthly units and pricing roll up into big revenue swings over a year.


<h2>Project 3 – Chocolate Sales & Shipments (Power BI)</h2>


![Power BI](https://github.com/user-attachments/assets/67da664a-4f9e-4cfd-90de-4f35e53a0344)


**Dataset:** A chocolate company’s boxes shipped and revenue by product, country, and month.

**What I built:**

•	Bar chart: Sum of Boxes Shipped by Country

•	Bar chart: Sum of Boxes Shipped by Product


![Screenshot 2025-11-30 133742](https://github.com/user-attachments/assets/73e3e76f-544b-4005-a8f4-f9c152e269e8)


•	Line chart: Sum of Amount by Year, Quarter, and Month

•	Waterfall chart: Sum of Amount by Year, Quarter, Month, and Product

**Key analysis and insights:**

•	Sum of Boxes Shipped by Product: A small group of chocolates—like 50% Dark Bites and other top bars—account for most of the shipped boxes, while many flavours sit in a long lower volume tail, which is classic 80/20 behaviour in product portfolios.

•	Line chart (Amount by Month): Revenue starts strong in January, dips around February–April, then peaks again around June before easing off—so the quarter isn’t flat, it has clear ups and downs.

•	Waterfall chart (Amount by Product within the Quarter): The waterfall view explains the “why” behind the dip: early gains come from items like Milk Bars and 85% Dark Bars, but later in the quarter some products contribute much smaller increases or even pull the total down, and the “Other” segment drags overall revenue further. That points directly at which SKUs need better pricing, promotion, or even replacement.


![Screenshot 2025-11-30 133858](https://github.com/user-attachments/assets/e3877334-4eaf-46e9-be82-565e3fb8202f)


**What this taught me:**

•	How to combine trend (line) and explanation (waterfall) charts so the dashboard doesn’t just say “revenue fell” but shows which products caused it.

•	How to think like an operations/marketing partner: using product level insight to suggest specific actions instead of just reporting totals.


<h3>What I’ve Learned Overall (Tools + Mindset)</h3>

**Across these projects, I learned how to:**

•	Clean and model data for analysis, then design dashboards that answer “so what?” not just “what happened?”.

•	Use Tableau for fast visual exploration and geographic views, and Power BI for interactive business dashboards with measures, slicers, and DAX.

•	Read patterns like seasonality, product mix, and regional differences and translate them into practical ideas a business could actually use.


<h2>Future Expectations</h2>

**Going forward, I plan to:**

•	Add SQL and Python to my workflow to handle larger datasets and build predictive models on top of these descriptive dashboards.

•  Extend these reports with profitability analysis (margins per product/month) and customer segmentation to move from “what happened” to “what we should do next.”

•  Keep using projects like this to build a portfolio that proves I can move from raw data to clear, actionable insight for any organization.

