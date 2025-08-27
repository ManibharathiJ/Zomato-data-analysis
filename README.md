# Zomato Data Analysis Project
This project analyzes the Zomato restaurant dataset to extract meaningful insights about restaurant types, customer preferences, ratings, cost, and online vs offline ordering trends. The analysis utilizes Python libraries such as Pandas, NumPy, Matplotlib, and Seaborn for data processing and visualization.

# Project Overview
The aim of this project is to analyze restaurant data collected from Zomato, a popular restaurant discovery and food delivery platform. The dataset contains information including restaurant names, availability of online orders, table booking options, ratings, votes, approximate cost for two people, and the type of restaurant.
Using this data, the project uncovers customer preferences and behaviors through various analytical perspectives and visualizations, aiding business decisions and marketing strategies.

# Dataset
The dataset consists of the following columns:
•	name: Restaurant name
•	online_order: Availability of online ordering (Yes/No)
•	book_table: Availability of table booking (Yes/No)
•	rate: Rating of the restaurant (out of 5)
•	votes: Number of votes received
•	approx_cost(for two people): Approximate cost for two people in local currency
•	listed_in(type): Type/category of the restaurant (e.g., Dining, Cafes, Buffet, etc.)

# Environment Setup
1.	Install Python (preferably Python 3.x).
2.	Install Jupyter Notebook to run the analysis interactively.
3.	Install required libraries

# Step-by-Step Analysis Procedure
1.	Load the dataset into a pandas DataFrame.
2.	Data Cleaning: Convert ratings from string format to numeric and check for missing or null values.
3.	Exploratory Data Analysis (EDA):
	Analyze the distribution of restaurant types using count plots.
	Calculate and visualize total customer votes by restaurant type.
	Explore rating distributions via histograms.
	Examine spending preferences of couples through cost analysis.
	Compare ratings for online vs offline ordering options with box plots.
	Investigate online order availability by restaurant type using pivot tables and heatmaps.
4.	Summary Insights:
	Identify the most popular restaurant types among customers.
	Determine the restaurant type with the highest votes.
	Understand the common rating ranges and spending limits.
	Evaluate if online or offline ordering receives better ratings.
	Pinpoint restaurant types with predominantly offline orders for targeted offers.




