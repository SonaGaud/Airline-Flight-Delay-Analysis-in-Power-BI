## Project Overview:
(Power BI Link)[https://app.powerbi.com/view?r=eyJrIjoiOWNlNmQxMmEtZTcyYS00NTIyLWEzMjAtNjNiODliZmQxODAwIiwidCI6IjI1Y2UwMjYxLWJiZDYtNDljZC1hMWUyLTU0MjYwODg2ZDE1OSJ9]
#### This project analyzes flight delays and cancellations across major U.S. airports using a dataset of 2 million commercial flights.
#### The goal is to uncover trends and understand the factors influencing delays and cancellations. 
#### The project follows a structured Business Intelligence (BI) workflow, covering:
    1. Data Loading & Preparation
    2. Relational Data Modeling
    3. DAX Calculations
    4. Interactive Dashboard Creation

## What I Learned:
#### I learned this from Maven Analytics, which provided a structured and practical learning experience. This project helped me:
    ✔ Gain hands-on experience in Power BI
    ✔ Understand data transformation, modeling, and visualization
    ✔ Work with large datasets efficiently
    ✔ Create an interactive dashboard to derive actionable insights

## Steps Taken
    1️⃣ Data Loading & Preparation:
    --Imported flight data and related tables (Airlines, Airports, Cancellation Codes) from CSV files into Power BI.
    --Cleaned and transformed the dataset using Power Query, removing unnecessary columns and creating a flight status column (On-time, Delayed, or Canceled).
    
    2️⃣ Building a Relational Model:
    --Designed a Star Schema, linking the Flights table (fact table) with lookup tables (Airlines, Airports, Cancellation Codes).
    --Established one-to-many relationships for efficient filtering and analysis.
    
    3️⃣ Adding DAX Measures
    --Created key DAX measures:
    --Total Flights
    --Delayed, Canceled, and On-time Flights
    --Percentage Metrics (Delayed, Canceled, On-time)
    --Used CALCULATE and DIVIDE functions to compute dynamic insights.
    
    4️⃣ Designing a Dynamic Dashboard
    --Developed a flight status dashboard with key insights.
    --Used KPI cards for total, delayed, and canceled flights.
    --Implemented bar charts for airport and airline comparisons.
    --Used line charts to track trends over time.
    --Added pie and stacked bar charts for cancellations and flight status.
    --Applied Power BI interactions for advanced filtering and drill-down analysis.

## Why This Project Matters
    --Demonstrates real-world data analysis skills in Power BI.
    --Enhances problem-solving and data storytelling.
    --Strengthens BI workflow knowledge, crucial for professional projects.

## Next Steps
    --Enhance the dashboard with advanced visualizations
    --Optimize query performance for large datasets
    --Explore additional filtering and drill-through options
