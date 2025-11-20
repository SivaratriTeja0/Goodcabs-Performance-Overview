🚖 GoodCabs: Transportation Performance Analysis

A complete end-to-end data analytics project for evaluating GoodCabs' performance across Tier-II Indian cities.

📘 Company Overview

GoodCabs, an imaginary but realistic cab service provider, has been operating for two years in India's growing Tier-II cities. The company focuses on:

Empowering local drivers

Providing smooth and safe travel experiences

Bridging service gaps in underserved markets

Strengthening its position as a reliable mobility partner in 10 cities

GoodCabs' community-driven business model helps support local employment while offering passengers a seamless and enjoyable ride experience.

🔎 Problem Statement

Despite strong early traction in Tier-II cities, GoodCabs is falling short of its 2024 strategic performance goals.
Key concerns include:

Slower-than-expected market penetration

Operational inefficiencies across cities

Lack of visibility into new vs repeat passenger trends

Inconsistent trip volume and ratings

Missed target achievement rates

To overcome these challenges, GoodCabs requires a data-backed performance evaluation to uncover insights, identify bottlenecks, and highlight growth opportunities.

🎯 Project Objective

The primary objective of this project is to conduct a holistic performance analysis across:

✔ Trip Volume
✔ Passenger Satisfaction
✔ Revenue Contribution
✔ New vs Repeat Passenger Mix
✔ Repeat Passenger Rate (RPR)
✔ City-wise Operational KPIs
✔ Target Achievement %

These insights help GoodCabs:

Improve strategic decision-making

Identify high- and low-performing cities

Optimize operations for better efficiency

Strengthen customer retention

Meet ambitious 2024 targets

🛢 Data Overview

This project included two SQL databases and eight CSV files.
SQL databases were used extensively, while CSVs were used for verification.

1️⃣ trips_db

Contains core fact and dimension tables:

fact_trips

fact_passenger_summary

dim_date

dim_city

dim_repeat_trip_distribution

2️⃣ targets_db

Contains monthly and city-level performance targets:

monthly_target_trips

monthly_target_new_passengers

city_target_passenger_rating

📅 Data Span:
January 1, 2024 → June 30, 2024

📚 Data source (Codebasics):
https://codebasics.io/challenge/codebasics-resume-project-challenge

🛠 Tools Used
🔹 Power BI

Dashboard building

Data modeling

DAX measures

🔹 MySQL

Data extraction

Ad-hoc business queries

🔹 Power Query

Used for:

Removing duplicates

Trimming spaces

Cleaning raw tables

Adding conditional columns

Creating a dim_month support table

Creating custom slicer tables:

passenger_type (new/repeated)

Set_BM (Benchmarks: PM / Target)

📑 Report Components
✔ Ad-hoc Business Requests

SQL-based analysis solving operational business queries.

✔ Power BI Dashboard

Includes:

Home/Login Page

Finance Dashboard

Sales Dashboard

Marketing Dashboard

Operations Dashboard

Executive Dashboard

✔ Data Model Overview

Clean star-schema model built using SQL + Power Query.

✔ Presentation Slides

Summarizes findings & insights for leadership.

For full interactive dashboard access, contact me.

📊 Key Insights
⭐ Top Revenue-Contributing Cities

Jaipur – ₹37.21M

Kochi – ₹17.00M

Chandigarh – ₹11.06M

➖ Bottom Revenue Contributors

Mysore – ₹4.05M

Vadodara – ₹3.80M

Coimbatore – ₹3.52M

📅 Monthly Revenue Contribution

Highest: February – 18.36%

Lowest: June – 14.19%

🚕 Top Cities by Trip Volume

Jaipur – 18.05%

Lucknow – 15.10%

Surat – 12.88%

🚫 Lowest Trip Volume

Visakhapatnam – 6.66%

Coimbatore – 4.96%

Mysore – 3.81%

💸 Fare & Trip Distance Insights

Highest avg fare: Jaipur – ₹483.92

Lowest avg fare: Surat – ₹117.27

Longest avg trip distance: Jaipur – 30.02 km

Shortest avg trip: Surat – 11 km

⭐ Passenger Ratings

Highest Rated (Tourist Cities):

Mysore – 8.70

Jaipur – 8.58

Kochi – 8.52

Lowest Rated (Business Cities):

Vadodara – 6.60

Lucknow – 6.40

Surat – 6.40

🔁 Repeat Passenger Rate (RPR)

Highest RPR: Surat (42.63%), Lucknow (37.12%)

Lowest RPR: Mysore (11.23%), Jaipur (17.43%)

📈 Trip Demand Pattern

Weekend Demand: Jaipur, Kochi, Mysore
Weekday Demand: Lucknow, Surat, Vadodara

📝 Recommendations
⭐ 1. Strengthen Passenger Experience

Improve comfort, safety, and wait times in low-rated business hubs.

⭐ 2. City-Specific Strategic Partnerships

Tourist cities → Partner with hotels, resorts, travel agencies

Business cities → Partner with tech parks, malls, offices

⭐ 3. Targeted Marketing

Use seasonal trends, local events, and geo-marketing to improve trip demand.

⭐ 4. Introduce Innovative Ride Options

Carpooling / shared rides

EV/Hybrid fleet for lower operational costs

⭐ 5. Trend Tracking

Align operations with peak-season and event-driven demand.

⭐ 6. Enhance Data Collection

Include:

Driver performance

Vehicle condition

Wait time & pickup time

Competitor pricing

Event calendars

🔗 LinkedIn Post -https://tinyurl.com/y3cf62an
📊 Live Power BI Dashboard-https://tinyurl.com/yazkuvh6
🖥 Presentation (PDF)-GoodCabs_Dashboard.pdf


🧠 Skills Gained

✔ Business KPI analysis
✔ DAX proficiency
✔ Power BI dashboard design (UI/UX)
✔ SQL for business analytics
✔ Storytelling with data
✔ Domain knowledge: Mobility as a Service (MaaS)
