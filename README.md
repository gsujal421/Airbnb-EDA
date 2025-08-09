Airbnb Exploratory Data Analysis


🎯 Objective
The goal of this project is to:

Analyze room types, prices, and availability across different neighborhoods.

Understand host behavior and listing patterns.

Detect potential outliers in prices.

Provide actionable recommendations for guests and hosts based on insights.

📂 Dataset
The dataset contains 20,765 entries and 22 features, including:

id → Unique identifier for each listing

name → Title of the Airbnb listing

host_name → Name of the host

neighbourhood_group → Borough where the listing is located

latitude / longitude → Geolocation of listings

price → Nightly rental price

room_type → Type of accommodation (e.g., entire home, private room)

reviews_per_month → Average monthly reviews for the listing

availability_365 → Number of available days in the year

🛠 Technologies Used
Python

Google Colab

NumPy

Pandas

Matplotlib

Seaborn

📊 Project Workflow
1️⃣ Data Loading & Cleaning
Removed missing values and duplicates

Converted date columns to proper datetime format

Handled outliers using the Interquartile Range (IQR) method

Created Price per Bed metric for fairer comparison

2️⃣ Exploratory Data Analysis
Price distribution and outlier detection

Price comparison across neighbourhood groups and room types

Seasonal trend analysis of review activity

Correlation analysis between numerical features

3️⃣ Visualizations
Boxplots → Price vs Neighbourhood Group & Room Type

Barplots → Average Price & Price per Bed by Neighbourhood Group

Line Plots → Reviews over time (seasonal trends)

Scatter Plots → Geographical distribution of listings

Heatmaps → Feature correlations

📈 Key Insights
Manhattan and Brooklyn are the most expensive neighbourhood groups, even when adjusted for number of beds.

Seasonal review activity peaks between October and December.

Room type significantly impacts pricing — Entire home/apartment listings are priced highest.

Price distribution is highly skewed, with a few high-value outliers.

🚀 Future Work
Develop a Machine Learning model to predict listing prices.

Create an interactive dashboard in Tableau or Plotly for real-time exploration.
