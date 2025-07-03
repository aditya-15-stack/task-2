# task-2
Revenue Insight Dashboard for Hospitality Analytics
This project presents a comprehensive Power BI dashboard that provides valuable revenue insights for the hospitality industry. The dashboard helps hotel managers make smarter, data-driven decisions using key information on bookings, revenue trends, guest behavior, and room performance.

🔧 Tools Used
Microsoft Excel – For initial data cleaning, formatting, and quick data exploration.

Power BI Desktop – For creating interactive dashboards and visual reports.

Power Query – For advanced data transformation inside Power BI.

DAX (Data Analysis Expressions) – For building custom KPIs and calculations.

CSV Files – Primary data source files for the project.

📊 Dataset Overview
The project uses five well-structured datasets:

dim_date – Date dimension including weekday/weekend classification.

dim_hotels – Hotel details like city and hotel category (Business/Luxury).

dim_rooms – Room types and classifications (Standard, Premium, etc.).

fact_bookings – Booking history with revenue, guest count, ratings, and booking status.

fact_aggregated_bookings – Daily room capacity and successful bookings.

🛠️ Project Process
1. Data Cleaning (Excel + Power Query)
Removed null and duplicate entries.

Standardized text formatting and date structures.

Filtered out irrelevant columns for a cleaner dataset.

2. Data Modeling (Power BI)
Built a star schema linking fact and dimension tables.

Created proper relationships for accurate filtering and aggregation.

3. KPI Calculations (DAX)
Key performance indicators calculated include:

Revenue – Total revenue realized.

Total Bookings – Number of bookings made.

Occupancy Rate – Successful bookings vs. available rooms.

RevPAR – Revenue per available room.

ADR – Average daily rate per booked room.

Cancellation Rate – Percentage of cancelled bookings.

Average Rating – Guest satisfaction scores.

4. Dashboard Design (Power BI)
Slicers to filter by city, hotel category, room type, and booking platform.

Line charts to display trends in revenue and occupancy.

Bar charts to compare room and hotel performance.

KPI cards for quick highlights like total revenue, total guests, and average ratings.

📈 Results and Insights
Higher Revenue in Metro Cities: Premium rooms in metro cities consistently generated higher revenue.

Weekend Boost: Business hotels saw significant booking spikes during weekends.

Direct Bookings Rated Higher: Guests who booked directly gave better ratings than those who booked via third-party platforms.

Impact of Cancellations: High cancellation rates had a noticeable effect on revenue realization.

📌 Conclusion
This project demonstrates how combining Excel and Power BI can transform raw hotel data into meaningful, interactive dashboards. It enables quick, data-backed decisions to optimize revenue, enhance guest satisfaction, and plan future strategies effectively in the hospitality sector.

