#Airbnb Exploratory Data Analysis (EDA)

📌 Overview
This project performs an Exploratory Data Analysis on Airbnb listings to uncover insights into pricing, location trends, room types, and seasonal booking patterns.
The analysis was conducted in Google Colab using Python libraries NumPy, Pandas, Matplotlib, and Seaborn.

The dataset underwent thorough cleaning, statistical analysis, and visualization to identify meaningful patterns that can be used for further predictive modeling or dashboard creation.

---

#🛠️ Technologies Used
•	Python
•	Google Colab
•	NumPy
•	Pandas
•	Matplotlib
•	Seaborn

---

#📊 Key Steps in the Project
1) Data Loading & Cleaning

•	Removed missing values and duplicates

•	Converted date columns to proper datetime format

•	Handled outliers using the Interquartile Range (IQR) method

•	Created a new metric: Price per Bed for fair comparisons between listings

2) Exploratory Data Analysis

•	Price distribution and outlier detection

•	Price comparison across neighbourhood groups and room types

•	Seasonal trend analysis of review activity

•	Correlation analysis between numerical features

3) Visualizations

•	Boxplots: Price vs Neighbourhood Group & Room Type

•	Barplots: Average Price & Price per Bed by Neighbourhood Group

•	Line plots: Reviews over time (seasonal trends)

•	Scatter plots: Geographical distribution of listings

•	Heatmaps: Feature correlations

---

#📈 Key Insights
•	Manhattan and Brooklyn are the most expensive neighbourhood groups, even when adjusted for number of beds.

•	Seasonal review activity peaks between October and December.

•	Room type significantly affects pricing — Entire home/apartment listings are priced highest.

•	Price distribution is highly skewed, with a small number of high-value outliers.

---

#Future Work

•	Develop a Machine Learning model to predict listing prices.

•	Create an interactive dashboard in Tableau or Plotly for real-time exploration.


