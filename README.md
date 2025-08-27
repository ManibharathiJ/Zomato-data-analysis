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

Load the dataset into a pandas DataFrame

## Data Cleaning: 
Convert ratings from string format to numeric and check for missing or null values.

## Exploratory Data Analysis (EDA):
1.	Analyze the distribution of restaurant types using count plots.
2.	Calculate and visualize total customer votes by restaurant type.
3.	Explore rating distributions via histograms.
4.	Examine spending preferences of couples through cost analysis.
5.	Compare ratings for online vs offline ordering options with box plots.
6.	Investigate online order availability by restaurant type using pivot tables and heatmaps.

## Summary Insights:
1.	Identify the most popular restaurant types among customers.
2.	Determine the restaurant type with the highest votes.
3.	Understand the common rating ranges and spending limits.
4.	Evaluate if online or offline ordering receives better ratings.
5.	Pinpoint restaurant types with predominantly offline orders for targeted offers.

## Visualizations
1.	Count plots showing restaurant type frequencies.
2.	Bar charts displaying votes by restaurant type.
3.	Histograms presenting restaurant rating distributions.
4.	Box plots contrasting ratings between online and offline orders.
5.	Heatmaps illustrating online order availability across restaurant categories.

## Results and Key Insights
1.	The most common restaurant type.
2.	Restaurant types with the greatest customer engagement (votes).
3.	Typical rating range most restaurants receive.
4.	Average spending tendencies for couples ordering online.
5.	Online ordering tends to receive higher/lower ratings than offline.
6.	Restaurant types primarily ordering offline, potential targets for promotional offers.

## How to Run
1.	Clone or download the repository.
2.	Open the Jupyter Notebook file (Zomato-data-analysis.ipynb).
3.	Run the notebook cells sequentially to see data loading, cleaning, visualization, and analysis.
4.	Explore the generated plots and insights.

## License
This project is for educational and analytical purposes.

## Acknowledgements
•	Dataset sourced from Zomato.
•	Libraries: Pandas, NumPy, Matplotlib, Seaborn.









