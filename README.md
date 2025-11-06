# Cars-Sales-Analysis
SQL-based data analysis project exploring car market trends through advanced queries. Includes insights on pricing, ratings, performance, and customer preferences using normalized relational models, ER diagrams, and analytical SQL operations.


📘 Project Overview

The Meta Car SQL Project explores car market data to uncover insights about pricing, ratings, performance, and customer preferences. Using SQL queries, this project performs a detailed data analysis on the car dataset to identify trends, relationships, and actionable insights.
It aims to understand which models perform best, how pricing aligns with performance, and how customer feedback correlates with technical specifications such as fuel type, engine power, torque, and transmission.

🎯 Objective

The main goal of this project is to analyze and interpret trends within the car dataset by studying:

Price segmentation (Budget, Mid-Range, Premium)

Customer ratings and reviews

Performance metrics like engine power, torque, and displacement

Market preferences across fuel type, transmission, and body type

The final outcome is to generate data-driven insights that guide product positioning, marketing strategies, and inventory planning, while identifying potential opportunities for value-based and high-performance vehicles.

🧩 Tools and Technologies Used

SQL – for querying and analyzing relational data

Relational Database Design – using normalized tables (Cars, Engine, FuelType, Transmission, BodyType)

ER Diagram – to establish one-to-many relationships between tables

Microsoft PowerPoint – for presentation and visualization of results

📊 Key Analysis and Queries Performed

Below are the main SQL analyses executed in the project, along with the insights derived:

#	Analysis	Description	Insights
1	Top 5 Most Reviewed Cars	Identified cars with the highest number of reviews.	Showed which models are most popular among customers.
2	Average Rating by Body Type	Calculated average ratings for each car body style.	Helped rank segments by customer satisfaction.
3	Cars by Price Range	Segmented cars into Budget, Mid-Range, and Premium categories.	Highlighted affordability distribution.
4	Highest and Lowest Priced Cars per Fuel Type	Compared price variation across fuel types.	Useful for pricing strategies.
5	Average Starting Price by Transmission Type	Calculated how transmission type affects average cost.	Showed demand for automatic vs manual.
6	Most Powerful Engines	Ranked top cars by horsepower (BHP).	Helped identify performance-focused models.
7	Fuel Efficiency Proxy	Analyzed tank-to-power ratio for efficiency.	Revealed most fuel-efficient designs.
8	Average Engine Displacement by Body Type	Measured engine size trends by body category.	Showed how engine capacity varies across segments.
9	Most Popular Fuel Type	Counted vehicles per fuel type.	Showed market preference for fuel type.
10	Transmission Preference by Body Type	Compared automatic vs manual by car segment.	Helped identify body type & transmission relationships.
11	Ratings by Fuel Type	Averaged ratings per fuel type.	Linked performance and customer satisfaction.
12	Best Value for Money Cars	Filtered high-rated but low-priced models.	Highlighted cost-effective choices.
13	Luxury Performance Cars	Listed high-power and high-price models.	Defined the luxury vehicle segment.
14	High Torque at Low RPM Cars	Found cars with strong low-end torque.	Useful for off-road and heavy-duty analysis.
🧠 Entity–Relationship (ER) Model

The database design consists of:

Cars Table: Core details (name, price, rating, etc.)

Engine Table: Engine specs (displacement, power, torque)

FuelType Table: Categorical fuel types

Transmission Table: Transmission classification

BodyType Table: Defines body structure

Relationships:

Each car is linked to one fuel type, one transmission type, and one body type, but each category can map to many cars (one-to-many relationships).

The structure is normalized to reduce redundancy and maintain scalability.

⚙️ SQL Features Used

CREATE, INSERT, and SELECT statements

Joins (INNER JOIN) to merge tables for multi-attribute analysis

Aggregate Functions (AVG, MAX, MIN, COUNT, ROUND)

Grouping and Sorting (GROUP BY, ORDER BY)

Conditional Segmentation using CASE WHEN

📈 Key Performance Indicators (KPIs)

Average Customer Rating – measures satisfaction per body/fuel type

Total Cars by Price Range – determines market distribution

Most Popular Fuel Type – identifies leading energy preference

Average Engine Power (BHP) – measures performance strength

Best Value Cars (Rating vs Price) – balances cost and satisfaction

Top 10 Most Powerful Cars – highlights premium performance offerings

🧾 Findings & Insights

Petrol cars dominate the dataset, followed by diesel and electric.

SUVs and Sedans received the highest average ratings, showing customer preference.

Automatic transmissions are gaining popularity in premium categories.

High-torque models are mostly found in off-road and SUV segments.

Value-for-money cars are primarily concentrated in the mid-range price bracket.

🧠 Conclusion

This SQL-based analysis provides a deep understanding of automotive market behavior, uncovering relationships between price, performance, and consumer feedback.
It delivers actionable insights for manufacturers, marketers, and analysts to:

Optimize product positioning and marketing strategies.

Improve inventory planning and pricing models.

Identify high-value and high-performance vehicle opportunities.

The project successfully demonstrates how structured SQL queries can transform raw car data into strategic insights for the automotive industry.
