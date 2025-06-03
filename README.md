# task-2
README - Revenue Insight Dashboard for Hospitality Analytics
This project is a Power BI dashboard that provides revenue insights for hotels. It helps hotel managers make better decisions using data on bookings, revenue, guest behavior, and room types.
🔧 Tools Used
- Power BI Desktop – For building dashboards and reports
- Power Query – For cleaning and transforming the data
- DAX (Data Analysis Expressions) – For creating custom calculations
- CSV Files – Used as the main data source
📊 Dataset Overview
The project uses five datasets:
- dim_date: Dates and weekday/weekend flags
- dim_hotels: Hotel info like city and category (Business/Luxury)
- dim_rooms: Room types and their classifications
- fact_bookings: Detailed booking history including guests, revenue, and ratings
- fact_aggregated_bookings: Daily room capacity and successful bookings
🛠️ How the Dashboard Was Made
1. Data Cleaning
   - Removed null values
   - Formatted text and dates
   - Removed unnecessary columns
2. Data Modeling
   - Created a star schema in Power BI
   - Linked fact tables with dimension tables for better filtering
3. DAX Measures
   Calculated important KPIs such as:
   - Revenue
   - Total Bookings
   - Occupancy Rate
   - RevPAR (Revenue per Available Room)
   - ADR (Average Daily Rate)
   - Cancellation Rate
   - Average Rating
4. Dashboard Design
   - Used slicers to filter by city, hotel type, and time
   - Line charts for trends (Revenue, Occupancy)
   - Bar charts for performance by room type and hotel
   - Cards for total revenue, guests, and ratings
📈 Results and Insights
- Higher Revenue in Metro Cities: Hotels in metro areas with premium rooms earned the most.
- Weekend Boost: Business hotels saw more bookings on weekends.
- Ratings & Platforms: Guests who booked through direct channels gave better ratings than OTA users.
- Cancellations Matter: Cancellation rates had a visible impact on the actual revenue realized.
🔮 Future Scope
- Add real-time data connection
- Predict occupancy and revenue using machine learning
- Implement dynamic pricing models
- Perform customer segmentation and sentiment analysis
📌 Conclusion
This project shows how Power BI can be used in the hospitality industry to get meaningful business insights. It helps in planning, improving guest satisfaction, and optimizing revenue using simple yet powerful dashboards.
