Airbnb Listings Analysis: Boston vs Seattle

This project analyzes Airbnb data from Boston and Seattle to understand the factors influencing listing prices, review scores, and occupancy rates. The goal is to extract actionable insights for hosts and compare overall listing performance between the two cities using data analysis and machine learning techniques.

Table of Contents

Project Motivation

Datasets

Used Frameworks

Questions Addressed

Results & Insights

File Descriptions

Acknowledgements

Project Motivation

After exploring the Airbnb datasets, the motivation behind this project was to:

Identify the key factors affecting listing prices and review scores

Understand the relationship between price, occupancy rate, and listing quality

Compare Boston and Seattle to determine which city performs better in terms of Airbnb listings

Datasets

The project uses Airbnb data from Boston and Seattle, consisting of the following large files:

calendar.csv

reviews.csv

listings.csv

⚠️ Since these files are very large, they could not be uploaded directly.
A dataset access link is provided instead.

Used Frameworks

The project was implemented using Python 3.9 via Anaconda.
The following libraries were used:

Pandas

NumPy

Matplotlib (v3.5)

Seaborn

Scikit-Learn

String

Warnings

Questions Addressed

Which city has better Airbnb listings? Which one is more expensive? Is there a connection?

What is the relationship between price and occupancy rate? How does listing quality fit in?

Which features influence review scores the most? What about listing prices?

Results & Insights
1. City Comparison: Boston vs Seattle

Seattle has better overall listings:

Higher average review score: 78.8 vs 72.1 (Boston)

Better positive/negative review ratio: 55.4 vs 31.9

Boston listings are more expensive:

Average price: $168.70

Seattle average price: $127.02

🔹 Higher prices do not guarantee better reviews.
🔹 Guests tend to be more demanding when paying higher prices, often leading to lower ratings.

2. Price vs Occupancy Rate

The correlation between price and occupancy rate is weak

Lowering prices does not necessarily increase occupancy

Listings priced above $400 often show extreme behavior:

Either very high or very low occupancy rates

3. Key Features Influencing Review Scores

Most important factors:

Price

Occupancy rate

Number of positive and negative reviews

Cleaning fee

🔹 High prices often lead to higher guest expectations
🔹 Guests are particularly sensitive to high cleaning fees

4. Key Features Influencing Listing Prices

Most important predictors:

Cleaning fee

Number of bedrooms

Accommodation capacity

🔹 Bigger houses → more bedrooms → accommodate more people → higher prices

File Descriptions

Boston/

calendar.csv

reviews.csv

listings.csv

Seattle/

calendar.csv

reviews.csv

listings.csv

Jupyter Notebook

Contains the complete project implementation

Follows the CRISP-DM methodology

Includes markdown documentation, visualizations, and modeling steps
