 Uber Fares Dataset Analysis using Power BI
 Project Overview
This project is a comprehensive data analysis of the Uber Fares dataset using Python and Power BI. The goal is to uncover fare trends, ride patterns, and temporal insights, and to visualize them through an interactive dashboard. The analysis is conducted as part of the AUCA Introduction to Big Data Analytics (INSY 8413) course.

🎯 Objectives
Load and explore the Uber Fares dataset
Clean and enhance the data using Python (Pandas)
Generate time-based features for deeper insights
Visualize ride and fare patterns in Power BI
Present findings in a structured report and dashboard

📁 Dataset
Source: Kaggle – Uber Fares Dataset
https://www.kaggle.com/datasets/yasserh/uber-fares-dataset

Columns Included:
fare_amount, pickup_datetime, pickup_longitude, pickup_latitude,
dropoff_longitude, dropoff_latitude, passenger_count

🧹 Data Preparation
Data was cleaned and processed using Python:
Removed rows with null values
Filtered invalid fares and passenger counts
Ensured geographical coordinates are within NYC bounds
Created time-based features: hour, day, month, weekday
Saved final output to uber_cleaned.csv

📊 Visualizations in Power BI
The following charts and visuals were created in Power BI:
 Fare Distribution: Histogram & Boxplot
 Time Patterns: Hourly, daily, monthly ride trends
 Fare vs. Distance Correlation

🗺️ Map Visualization: Geographic pickup density

📅 Busiest Periods: Analysis of peak ride times

💡 Key Insights
Most fares fall between $5 and $25
Friday and Saturday nights are peak ride periods
Fares increase during night hours and weekends
Clear correlation between distance and fare amount
Central NYC is the most active ride zone

📦 Folder Structure
Uber-Fares-PowerBI-Analysis/
├── cleaned_dataset/
│ └── uber_cleaned.csv
├── dashboard/
│ └── uber_dashboard.pbix
├── screenshots/
│ ├── data_loading.png
│ ├── cleaning_steps.png
│ ├── dashboard_build.png
├── report/
│ └── AUCA_Uber_Report.pptx
├── README.md

🧰 Tools & Technologies Used
Python (Pandas) – Data cleaning & feature creation
Power BI – Data visualization & dashboard
GitHub – Project tracking & submission

✅ Status
 Data cleaned
 Features created
 Dashboard built
 Report written
 Submission complete

 Author
Teta Uwase Huguette
Software Engineering Student – AUCA
Student ID: 25513

ALL RESULT IMAGES 

<img width="746" height="337" alt="uber cleaned" src="https://github.com/user-attachments/assets/caa23592-1ddc-4269-a1b3-22eb01282ed2" /><img width="556" height="343" alt="dashboard3" src="https://github.com/user-attachments/assets/0c7efd56-f690-4726-8749-ad6a1355a8d5" />

