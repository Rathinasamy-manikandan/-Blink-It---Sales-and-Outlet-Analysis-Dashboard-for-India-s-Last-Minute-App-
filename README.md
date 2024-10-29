# -Blink-It---Sales-and-Outlet-Analysis-Dashboard-for-India-s-Last-Minute-App-
Blink It! - India's Last-Minute Shopping App Dashboard


Overview
This Power BI project visualizes sales and outlet data for Blink It, India’s leading last-minute shopping app. The dashboard provides insights into key performance metrics, outlet sales distribution, item categories, customer ratings, and yearly sales trends. Designed for business analysts and company executives, this dashboard enables data-driven decision-making for better inventory management, customer satisfaction, and outlet performance.

Project Description
Title: Power BI Sales and Outlet Dashboard for Blink It

Overview: This dashboard for Blink It provides a comprehensive analysis of sales, customer ratings, and outlet performance across multiple tiers. It empowers stakeholders to monitor trends, optimize inventory, and enhance customer service based on insights derived from visualized data.


Key Features
Total Sales Overview:

Total Sales: A high-level metric showing total revenue generated.
Average Sales per Outlet: Insight into average sales, which helps in understanding performance across outlets.
Total Items Sold: Highlights the total number of items sold, useful for inventory and demand planning.
Customer Rating: Displays the average rating to gauge customer satisfaction.
Annual Sales Trends:

Year-by-year analysis of total sales, enabling stakeholders to observe growth patterns and identify peak performance years.
Outlet Sales Distribution:

Sales distribution across Tier 1, Tier 2, and Tier 3 outlets, helping management understand regional performance.
Outlet Sales Share: A pie chart indicating the sales proportion of each outlet tier.
Item Category Insights:

Breakdown of items sold by categories like snacks, frozen food, household, etc., enabling targeted promotions and inventory adjustments.
Fat Content Analysis:

Categorization of items by fat content (Low Fat, Regular, High Fat) to support health-related marketing and inventory decisions.
Filter Options:

Interactive filters for Item Type, Outlet Size, and Location to customize data views based on user needs.

Data Sources
The data for this dashboard is sourced from Blink It's internal sales records and includes:

Sales and revenue data for each outlet.
Item categories with details on fat content.
Customer ratings and feedback.
Outlet information categorized by tier, location, and size.
Technologies Used
Microsoft Power BI: Used for data modeling, visualization, and creating an interactive dashboard.
How to Use
Open the .pbix File: Download the Power BI file from the repository and open it in Power BI Desktop.
Explore Filters: Utilize filters for Item Type, Outlet Size, and Location to get specific insights.
Analyze Key Metrics:
Use the sales trends chart to view performance over the years.
Check customer ratings to understand user satisfaction and identify areas for improvement.
Examine the distribution of sales by outlet tier and item type for a better understanding of product demand.


Sample Data Format
If you're using your own data, ensure it is structured as follows:
OutletType, ItemType, Sales, Rating, OutletSize, Location, FatContent
Grocery, Snack Food, 200, 4.2, Tier 1, Mumbai, Regular
Supermarket, Dairy, 150, 3.8, Tier 2, Delhi, Low Fat
...

Usage
Open the Power BI dashboard and use the filters on the left to explore the data.

Example Code for DAX Calculations
If you need to replicate some calculations, here are a few DAX expressions that might be useful:

#Total Sales Calculation
Total Sales = SUM(SalesData[Sales])
#Average Sales Per Item
Avg Sales = AVERAGE(SalesData[Sales])
#Yearly Sales Growth
Yearly Sales Growth = 
VAR CurrentYearSales = SUM(SalesData[Sales])
VAR PreviousYearSales = CALCULATE(SUM(SalesData[Sales]), DATEADD(SalesData[Date], -1, YEAR))
RETURN 
DIVIDE(CurrentYearSales - PreviousYearSales, PreviousYearSales, 0)
Folder Structure
BlinkIt-Dashboard/
├── data/                   # Sample data (e.g., sample_data.csv)
├── images/                 # Dashboard screenshots
├── BlinkIt-Dashboard.pbix  # Power BI dashboard file
├── README.md               # Project README file
└── LICENSE                 # License file


Visuals and Insights
Slide 1: Overview with total sales, average sales, total items sold, and customer ratings.
Slide 2: Detailed visualizations of sales trends, outlet sales by tier, item category breakdown, and fat content segmentation.
Outcome
This dashboard offers actionable insights that can help Blink It optimize outlet performance, target inventory adjustments, and monitor customer satisfaction. By providing a data-driven overview of sales metrics, outlet distribution, and customer feedback, Blink It can better align its operations with business goals.

[Blinkit Slides.pptx](https://github.com/user-attachments/files/17560379/Blinkit.Slides.pptx)

address resource gaps, and make informed HR decisions.
image
![Slide1](https://github.com/user-attachments/assets/26243383-308e-40f8-8164-372c673719e6)
![Slide2](https://github.com/user-attachments/assets/5430a1fa-f8ad-4929-9478-f4e6fd8d9bb6)



Author
Manikandan Rathinasamy
[18me020manimurugan@gmail.com]
[manikandaneng03@gmail.com]
