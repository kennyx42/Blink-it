# Blink-it

## Table of Content

- [Overview](#overview)
- [About the Business](#about-the-business)
- [Aim of the Project](#aim-of-the-project)
- [Process](#process)
- [Insights](#insights)
- [Key Opportunities for Optimization](#key-opportunities-for-optimization)

  
## Overview
The project showcases hands on expeinece in designing end-to-end data anlysis solution using PowerBI to address problems statement in retail store industry.

![picture](https://github.com/user-attachments/assets/f3787771-4cd6-4cfc-b451-61bb9441f198)


# About the Business
The business is committed to offering high-quality food products while prioritizing consumer health. As part of its strategy, it carefully curates a limited assortment of food items, focusing on those with moderate fat content to promote a balanced diet. Its goal is to provide nutritious options that support customers' well-being without compromising on taste.

Strategically, the business operates across three key regions in the country: Tier 1, covering the mainland; Tier 2, serving the coastal areas; and Tier 3, catering to customers on the island. This structured approach ensures accessibility and convenience for a diverse customer base.

# Aim of the Project
Blinkit is seeking to conduct a comprehensive analysis on its sales performance and customer satisfaction to identify key insights and opportunity for optimization using various KPIs.

The analysis is designed to deliver a comprehensive view of Blinkit's operational performance by addressing several key business questions. It will:
- Evaluate Total Sales by Fat Content: Determine how different levels of fat content in products contribute to overall revenue, thereby linking product quality with consumer health outcomes.
- Analyze Total Sales by Item Type: Break down revenue streams according to product categories, ensuring that the product assortment aligns with consumer preferences.
- Examine Fat Content Impact on Outlet Sales: Assess how the fat content of products sold varies by outlet, providing insight into regional or demographic differences in purchasing behavior.
- Investigate Sales by Outlet Establishment: Compare performance metrics across various outlet establishments to identify operational strengths and areas for improvement.
- Assess Sales by Outlet Size: Understand how outlet size correlates with sales performance, informing decisions on resource allocation and operational scaling.
-- Study Sales by Outlet Location: Analyze sales data by geographic location to identify market trends across mainland, coastal, and island regions.
- Integrate All Metrics by Outlet Type: Combine these insights to develop a detailed profile of each outlet type, ensuring that strategic decisions are data-driven and aligned with Blinkit's commitment to quality and customer well-being.


# Process
## Step 1 : Data Transformation
 _Tools used : Power Query_
 - Renamed columns to give better context.
 - Standardized fat content column by repalcing instances of _LF_ to Lowfat and _Reg_ to Regular
  
## Step 2 : Data Modelling
  _Tools used : Power BI DAX_
 - Created measures (Total sales, Average sales, Average rating, Item counts) to serve as  KPIs.
 - Craeted Parameter table around the KPIs to serve better as Slicers for other visualizations

## Step 3 : Analysis and Dashbord creations
  _Tools used : Power BI Visualization Features_
 - Used Donut charts, Cards, stacked barcharts and clustered bar charts to visualize Fat contents across the KPIs
 - Captured the year of outlet establishment against Total sales to see how revenue had grown over time on a line graph
 - Used a Funnel map, depicited outlet location ( Tier 1, Tier 2 and Tier 3) and how they each grown sales.
 - Tabularized outlet Type (supermarket and Grocery stores)  to these their numbers across the 4 Key performance indicators.

# Insights 

1. Overall Sales Performance
Total Sales (N1.2M): The business has generated a cumulative total sales figure of around N1.2M, reflecting substantial demand across its product lines.
Item Count (9K): There is a wide variety of items or SKUs (around 9,000), suggesting a broad assortment strategy.

2. Customer Satisfaction
Average Rating (3.9): The overall rating is moderately high, indicating generally positive customer experiences. However, there is still room for improvement to reach a higher benchmark (e.g., 4.0+).

3. Fat Content Breakdown
Donut Chart (Low, Regular, High Fat):
A significant share of sales appears to come from Low Fat items, aligning with the company’s emphasis on healthier options.
Regular Fat items also hold a considerable share, indicating balanced consumer demand.
High Fat items have the smallest proportion, but they still contribute to overall sales—an opportunity for niche targeting or product reformulation if health positioning is a priority.

4. Top-Selling Product Categories
Bar Chart by Item Type: Certain categories—like Household Items, Frozen Foods, or Meats—seem to dominate sales, each potentially exceeding hundreds of thousands in total revenue.
This suggests that everyday essentials and protein-based products are central to consumer demand.
Categories such as Fruits, Vegetables, and Snacks also exhibit strong performance, underscoring the need for variety in meeting diverse customer preferences.

5. Outlet Type and Size Performance
Outlet-Level Metrics: Different outlet types (e.g., Supermarket Type1, Grocery Store, Supermarket Type2, Supermarket Type3) show varying levels of sales and ratings.
Supermarket Type1 might be the top revenue generator, but further analysis could reveal whether its customer ratings lag behind smaller, more specialized stores.
Outlet Size: Larger outlets could be driving higher volumes, yet smaller outlets might offer a more personalized experience, potentially boosting ratings. Balancing assortment and service across outlet sizes can optimize both sales and satisfaction.

6. Regional Insights
While not explicitly shown in the screenshot, the business operates across Tier 1 (Mainland), Tier 2 (Coastal), and Tier 3 (Island) regions. Tracking how sales vary by location can uncover:
Product Preferences by Region: Mainland vs. coastal vs. island consumers may have different tastes (e.g., higher demand for seafood in coastal regions).
Operational Opportunities: Certain tiers might require targeted marketing or inventory strategies to improve penetration and customer satisfaction.

# Key Opportunities for Optimization
- **Enhance Product Mix**: With Low Fat items performing well, there may be an opportunity to introduce new health-oriented products or reformulate existing items.
- **Boost Ratings**: A 3.9 average rating is respectable but leaves room for improvement—perhaps via better customer service, promotions, or quality enhancements.
- **Target High-Potential Outlet Types**: Outlets showing the highest sales but lower ratings could benefit from targeted improvements to retain and attract customers.
- **Refine Regional Strategies**: Tailor assortment and marketing to regional preferences to maximize local market share.

