# Restaurant Dataset Analysis

## Project Overview
This project analyzes a dataset of restaurant information, aiming to uncover insights about cuisine popularity, top-rated restaurants, and locality-based trends. The dataset, `Rest.csv`, includes details like restaurant names, cuisines, ratings, cost for two, and more. The analysis focuses on understanding customer preferences and identifying patterns in the food industry.

---

## Dataset Description
The dataset consists of the following key columns:

- **Restaurant Name**: The name of the restaurant.
- **Cuisines**: The types of cuisines offered.
- **Aggregate Rating**: The overall rating based on customer reviews.
- **Votes**: The number of votes for the restaurant.
- **Cost for Two**: Average cost for two people.
- **Locality**: Location of the restaurant.

---

## Objectives
1. Clean and preprocess the dataset for analysis.
2. Perform exploratory data analysis (EDA) to identify trends and patterns.
3. Visualize key insights for better understanding.

---

## Tools and Technologies
- **Python Libraries**: pandas, matplotlib, seaborn, numpy
- **Visualization Tools**: Matplotlib for charts and plots

---

## Analysis Steps
1. **Data Loading**:
   - Read the `Rest.csv` file using pandas.
   - Inspect the data structure with methods like `.head()` and `.info()`.

2. **Data Cleaning**:
   - Handle missing values and duplicates.
   - Standardize textual data (e.g., `Cuisines` column).

3. **Exploratory Data Analysis (EDA)**:
   - Analyze distribution of ratings and votes.
   - Identify popular cuisines and their average costs.
   - Examine locality-based restaurant trends.

4. **Visualization**:
   - Create bar charts for cuisine popularity.
   - Generate scatter plots for ratings vs. cost.
   - Plot pie charts for rating distribution.

---

## Key Insights
- **Cuisine Popularity**: Identified the top 5 most popular cuisines based on occurrence.
- **Top-Rated Restaurants**: Highlighted restaurants with the highest aggregate ratings.
- **Locality Trends**: Pinpointed localities with the highest density of highly-rated restaurants.

---

## Conclusion
This analysis provides actionable insights for stakeholders in the food industry, such as restaurant owners and food aggregators, to optimize their offerings and target customer preferences effectively.

For further details, refer to the accompanying notebook containing the code and visualizations.

