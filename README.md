Zomato Restaurants – Exploratory Data Analysis

This project explores the global Zomato restaurant dataset to understand food trends, customer preferences, ratings, cuisines, and country-wise patterns. Using real-world data and Python-based analysis, the project walks through how raw data is cleaned, processed, and transformed into meaningful insights.

📁 Datasets Used
🔹 zomato.csv

The main dataset containing detailed information about restaurants across different countries.
It includes:

Restaurant names & locations

Cuisines offered

Ratings, votes, and review details

Price range and average cost

Online delivery and table booking availability

🔹 Country-Code.xlsx

A simple mapping file used to convert Country Code → Country Name, helping us understand the geographic distribution of restaurants.

🔹 exploratory-data-analysis.ipynb

A Jupyter notebook containing the entire workflow:

Importing and cleaning the datasets

Handling missing or inconsistent values

Merging datasets

Performing EDA

Creating visualizations and insights

🛠️ What Was Done (Human-Friendly Overview)
✔️ Data Cleaning

Before exploring anything, the data needed polishing:

Removed duplicates

Filled or handled missing values in cuisines and ratings

Fixed inconsistent text (like extra spaces or mixed formats)

Converted columns to proper data types

✔️ Data Processing & Merging

Added country names using the Country-Code.xlsx file

Extracted useful new fields (like primary cuisine)

Categorized restaurants by price range and rating color

✔️ Exploration & Insights

Once the data was ready, the fun part began:

Which countries and cities have the most restaurants?

Which cuisines dominate globally?

How do customer ratings vary across countries?

Is higher price linked to better ratings?

Do people prefer restaurants that offer online delivery?

Which places have extremely high or low-rated restaurants?

✔️ Visualizations

Created clear visual representations such as:

Pie charts for country distribution

Bar plots for cuisine popularity

Rating heatmaps

Price vs. rating comparisons

Vote vs. rating scatter plots

These visuals help transform numbers into stories.

📈 Key Outcomes

By the end of the analysis, you understand:

Global restaurant behavior across multiple countries

How food habits differ by region

Which cuisines are universally liked

How pricing affects customer ratings

Patterns in online delivery and table booking trends

This project makes the dataset easier to interpret and perfect for anyone exploring data analysis or the food industry.

🚀 How to Use the Project

Clone the repository

Install dependencies (Pandas, NumPy, Matplotlib, Seaborn, etc.)

Open the notebook

Run the cells to reproduce the analysis step-by-step

💡 Why This Project?

This EDA project is a great example of how real-world data can be turned into insights. It’s ideal for:

Portfolio building

Learning data cleaning

Understanding EDA workflows

Exploring food & restaurant trends
