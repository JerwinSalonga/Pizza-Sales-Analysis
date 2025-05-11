## **Table of Contents**

>[!SUMMARY] Table of Contents

>- [[README#Pizza Sales Analysis|Pizza Sales Analysis]]
>   - [[README#Project Background|Project Background]]
>   - [[README#Executive Summary|Executive Summary]]
>   - [[README#Insights Deep-Dive|Insights Deep-Dive]]
>       - [[README#Monthly Revenue Analysis|Monthly Revenue Analysis]]
>       - [[README#Revenue by Pizza Category|Revenue by Pizza Category]]
>       - [[README#Pizza Size Analysis|Pizza Size Analysis]]
>       - [[README#Order Volume Analysis|Order Volume Analysis]]
>       - [[README#Peak Order Times|Peak Order Times]]
>       - [[README#Top Selling Pizzas|Top Selling Pizzas]]
>       - [[README#Least Selling Pizzas|Least Selling Pizzas]]
>       - [[README#Ingredient Usage Analysis|Ingredient Usage Analysis]]
>   - [[README#Recommendations|Recommendations]]
>       - [[README#Maximize Peak Period Performance|Maximize Peak Period Performance]]
>       - [[README#Enhance Revenue from Underperforming Categories|Enhance Revenue from Underperforming Categories]]
>       - [[README#Optimize Pizza Size Selection|Optimize Pizza Size Selection]]
>       - [[README#Strengthen Pizza Category Focus|Strengthen Pizza Category Focus]]
>       - [[README#Reinforce Customer Engagement on Peak Order Days|Reinforce Customer Engagement on Peak Order Days]]
>       - [[README#Inventory and Ingredient Optimization|Inventory and Ingredient Optimization]]
>   - [[README#Assumptions and Caveats|Assumptions and Caveats]]

## Project Background

This project analyzes the sales data of a pizza restaurant, examining factors such as revenue trends, pizza popularity, order volume, and time-specific ordering patterns. The goal is to derive actionable insights that will help optimize inventory management and improve menu offerings. By focusing on pizza categories, sizes, and peak order times, the project aims to guide operational improvements, identify underperforming products, and uncover opportunities to boost revenue through targeted marketing strategies.


---
## Executive Summary

An analysis of pizza sales data from 2015 reveals strong revenue performance with a peak in July, reaching $72,000. Total revenue for the year amounted to $817,860, with an average monthly revenue of approximately $68,155. The Classic pizza category leads in both sales volume and revenue, while Supreme pizzas show a strong revenue performance due to higher pricing. However, Chicken and Veggie pizzas, despite their popularity, are underperforming due to their lower pricing. The largest pizza sizes (L) contribute the most to revenue, with Fridays and Saturdays being the busiest days for orders. Additionally, peak order times occur during lunch and dinner hours. Classic Deluxe, Barbecue Chicken, and Hawaiian pizzas are the top sellers, while Brie Carre and Mediterranean pizzas see the lowest sales. Garlic and tomatoes are the most used ingredients across the pizzas, emphasizing the importance of these items in managing inventory effectively.


![[pizza_sales_page1.png]] 

![[pizza_sales_page2.png]]

--- 
## Insights Deep-Dive

### Monthly Revenue Analysis

Looking at the chart, we see that monthly revenue generally remains strong, with a noticeable peak in July 2015. This month stands out as the period with the highest sales, reaching over $72,000. However, after this peak, there is a subtle but steady decline in revenue toward the end of the observed period. The total revenue across all months is $817,860.05, and the average monthly revenue is about $68,155.00. Despite the strong performance in the middle of the year, the overall growth from the first to the last month is actually negative, with a decrease of 7.3%. 

The number of orders and the average order value follow similar patterns. Orders are highest during the peak months, and while the average order value remains relatively stable, it does not compensate for the drop in total orders later in the year.

![[pizza_sales_trend.png]] 

### Revenue by Pizza Category

The data reveals that the "Classic" category leads in revenue, followed by "Supreme," "Chicken," and "Veggie." This is visually represented in the chart below, which clearly shows the dominance of the Classic pizzas in terms of sales revenue. 

This suggests that customers have a strong preference for traditional flavors, making the Classic category a cornerstone of the business. Focusing marketing efforts and menu innovation around these popular classics could further boost overall sales.

![[pizza_category_revenue.png]] 

### Pizza Size Analysis

The data shows that large pizzas (L) are the top revenue generators by a significant margin, followed by medium (M) and small (S) sizes. Extra-large (XL) and double extra-large (XXL) sizes contribute only a small fraction to the total revenue. This pattern suggests that customers prefer larger pizzas, likely for sharing or better value per slice.

![[pizza_size_revenue.png]]

### Order Volume Analysis

Fridays and Saturdays see the highest order volumes, with a noticeable dip on Sundays and Mondays. This pattern aligns with typical dining-out behavior, where weekends are peak times. Staffing and inventory should be optimized for these busy days, and targeted marketing (like weekend specials) could further capitalize on this demand.

![[order_trend_per_day.png]] 

### Peak Order Times

Orders spike sharply around lunchtime (12–13h) and again in the evening (17–18h). These are your critical service windows. Ensuring fast service and adequate staffing during these hours will help maintain customer satisfaction.

![[order_heatmap.png]] 

### Top Selling Pizzas

The Classic Deluxe Pizza leads the pack, closely followed by the Barbecue Chicken, Hawaiian, Pepperoni, and Thai Chicken pizzas. These favorites consistently attract customers, driving both high sales volume and substantial revenue. Their popularity likely stems from familiar flavors, broad appeal, and perhaps effective promotion or placement on the menu.

![[top_selling_pizza.png]] 

### Least Selling Pizzas

On the other end, pizzas like the Brie Carre, Mediterranean, Calabrese, Spinach Supreme, and Soppressata see much lower sales. These options may cater to more niche tastes, have less visibility, or simply don't resonate as strongly with the customer base.

![[least_selling_pizza.png]]

### Ingredient Usage Analysis

Garlic and tomatoes are the most heavily used ingredients, each used in over 27,000 pizzas. Basic ingredients (garlic, tomatoes, red onions) dominate the top usage, suggesting they're crucial for inventory management

![[most_used_ingredients.png]]

### What are the least used ingredients?

The least used ingredients are all associated with the Brie Carre Pizza (490 uses each), confirming its status as the lowest-selling pizza

![[least_used_ingredients.png]]

--- 
## Recommendations
### Maximize Peak Period Performance
* **Resource Planning & Staffing:** Ensure adequate staff training and resource allocation for peak periods, especially around lunch (12–1 PM) and dinner (5–6 PM) hours when order volumes spike. This will improve service efficiency and minimize customer wait times. 
* **Menu Optimization During High-Demand Hours:** During peak hours, promote quick-selling items like Classic and Supreme pizzas to manage kitchen load. Offering time-sensitive promotions can help manage customer demand during busy periods. 
* **Forecast and Prepare for High Revenue Months:** Since July shows a notable peak in sales, plan for targeted marketing efforts or special promotions leading up to and during peak periods, ensuring enough inventory and staff support.

### Enhance Revenue from Underperforming Categories
* **Marketing Focus on Chicken and Veggie Pizzas:** Despite their popularity, Chicken and Veggie pizzas contribute lower revenue due to their pricing. Develop targeted marketing campaigns to boost sales in these categories, such as bundle offers or loyalty discounts.
* **Review Pricing Strategy:** Consider adjusting the pricing of Chicken and Veggie pizzas slightly to better align with their perceived value while ensuring competitiveness against higher-priced categories like Classic and Supreme. 
* **Highlight Popularity in Menus:** Increase the visibility of Chicken and Veggie pizzas in the menu, leveraging their popularity for upselling.

### Optimize Pizza Size Selection
* **Promote Large Pizzas (L):** Since large pizzas are the top revenue generators, increase marketing and promotional efforts around these sizes, such as combo deals that offer larger pizzas for a slightly higher price to increase average order value.
* **Evaluate Smaller Sizes (S, XL, XXL):** Smaller pizza sizes and extra-large pizzas contribute little to total revenue. Analyze customer demand and consider either adjusting prices or phasing out underperforming sizes.
* **Size-Specific Discounts:** Use targeted discounts for medium or smaller-sized pizzas to increase sales while maintaining overall revenue.

### Strengthen Pizza Category Focus
* **Invest in Classic and Supreme:** With Classic pizzas dominating in both sales and revenue, and Supreme pizzas being a close second, further expand marketing efforts on these categories to drive customer preference. Consider creating "signature pizza" lines under these categories.
* **Introduce Seasonal or Regional Specials:** Use data to identify potential areas where Veggie and Chicken pizzas can gain more traction by experimenting with new toppings or seasonally relevant ingredients.

### Reinforce Customer Engagement on Peak Order Days

* **Weekends and Fridays:** Since Fridays and Saturdays see the highest order volumes, continue focusing marketing and special offers on these days. Consider adding limited-time weekend specials to increase customer engagement and traffic.
* Reduce Order Time Delays: Ensure that peak-order times (12 PM–1 PM, 5 PM–6 PM) are well-supported by adequate staffing, kitchen capacity, and delivery personnel to prevent delays and improve customer experience.

### Inventory and Ingredient Optimization

* **Garlic and Tomatoes as Core Ingredients:** Given that Garlic and Tomatoes are the most frequently used ingredients across pizzas, optimize procurement and storage of these items to ensure they are always in stock. Forecast demand based on seasonal and sales trends.
* **Track Ingredient Waste:** Analyze waste data for ingredients like garlic and tomatoes to minimize costs while ensuring availability. Implement just-in-time inventory for ingredients with high usage.

---
### Assumptions and Caveats

* This analysis assumes that the sales and order data are accurate, consistent, and fully reported. Since guest count data is not available, the analysis focuses on sales and order quantities. Any discrepancies in data logging or reporting may impact the conclusions drawn
* The dataset used in this analysis includes only transactions recorded, so it may not fully represent the entire customer base or sales across all platforms (e.g., online, in-store, or delivery).
* While correlations between specific pizza types and revenue, as well as peak ordering times, are observed, the results do not imply causality. Other factors, such as customer behavior, regional preferences, or promotions, may also influence these patterns.
* This analysis prioritizes high-revenue pizza categories and times, meaning less frequent but potentially important factors (e.g., specific toppings, niche pizza types) are not fully considered.
