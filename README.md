# Food-and-Restaurant-Data-Analysis
Zomato Bangalore Restaurant Trends Analysis
📝 Project Overview
This repository contains a data-driven analysis of restaurant trends in Bangalore using Zomato's real-world dataset. The project was developed as part of a hackathon and includes data cleaning, exploratory data analysis (EDA), geospatial visualization, and actionable insights. The analysis focuses on restaurant ratings, cuisines, costs, and spatial distribution across Bangalore.
🎯 Objectives
The primary objectives of this project are:

Clean and preprocess the Zomato dataset for analysis.
Perform exploratory data analysis (EDA) to uncover trends and patterns.
Merge geographical data for location-based insights.
Create geospatial visualizations, including restaurant density maps.
Extract actionable insights to understand Bangalore's restaurant landscape.

📊 Dataset
The dataset consists of two main files:

zomato_data.csv: Contains restaurant details such as:
online_order: Whether online ordering is available (Yes/No).
book_table: Whether table booking is available (Yes/No).
rate: Restaurant rating (out of 5).
votes: Number of votes received.
rest_type: Type of restaurant (e.g., Casual Dining, Cafe).
dish_liked: Popular dishes liked by customers.
cuisines: Types of cuisines offered.
approx_costfor_two_people: Approximate cost for two (in INR).
listed_intype: Listing type (e.g., Delivery, Buffet).
listed_incity: City area (e.g., Banashankari, BTM).


Geographical_Coordinates.csv: Contains latitude and longitude for each city area (listed_incity).


🚀 Usage

Data Cleaning: The notebook includes steps to handle missing values, convert data types, and preprocess columns like rate, approx_costfor_two_people, and votes.
Exploratory Data Analysis (EDA): Visualizations such as histograms, box plots, and correlation heatmaps are generated to explore ratings, costs, and restaurant types.
Geospatial Visualization: A restaurant density map is created using Folium, leveraging latitude and longitude data from the geographical coordinates.
Insights: The analysis provides insights into popular cuisines, high-rated restaurant types, and spatial distribution of restaurants in Bangalore.

📈 Key Findings

Ratings: Most restaurants have ratings between 3.5 and 4.0, with a median of 3.7.
Cost: The average cost for two people is around 554 INR, with a wide range (40–6000 INR).
Restaurant Types: Quick Bites and Casual Dining dominate, with Quick Bites being more affordable.
Cuisines: North Indian, Chinese, and South Indian cuisines are the most common.
Geospatial Trends: High restaurant density is observed in areas like BTM and Koramangala, indicating vibrant food scenes.


