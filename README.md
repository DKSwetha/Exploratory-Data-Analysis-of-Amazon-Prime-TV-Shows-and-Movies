Project Overview-

This project performs Exploratory Data Analysis (EDA) on the Amazon Prime Video Movies and TV Shows dataset to uncover insights related to content distribution, trends over time, genre popularity, audience ratings, and content performance. The goal is to transform raw streaming data into actionable business insights that support content strategy, recommendation systems, and market expansion decisions.

Business Objectives-

The key objectives of this analysis are:
Analyze the distribution of Movies vs TV Shows on the platform

Identify content release trends over time

Understand genre popularity and audience preferences

Analyze country-wise content representation

Study audience ratings and popularity metrics

Support data-driven business decision-making

Dataset Description-

The project uses two datasets:
titles.csv contains information about movies and TV shows such as title, type, release year, runtime, genres, production countries, IMDb and TMDB ratings, and popularity metrics.
credits.csv contains cast and crew information including person name, role, and character associated with each title.
The datasets were accessed directly from Google Drive within the Google Colab environment.

Tools & Technologies Used-

Python

Google Colab

Pandas

NumPy

Matplotlib

Seaborn

Methodology-

The analysis followed a structured EDA workflow:

Data Loading: 

Mounted Google Drive and loaded datasets using Pandas.

Data Cleaning & Wrangling:

Removed duplicate records

Handled missing values using context-based logic

Validated and corrected data types

Converted list-like string columns (e.g., genres, production countries) into usable formats

Retained missing IMDb values as NaN to avoid analytical bias

Exploratory Data Analysis:

Univariate analysis (distribution of individual variables)

Bivariate analysis (relationships between two variables)

Multivariate analysis (combined effect of multiple variables)

Visualization:

Bar charts, histograms, box plots

Scatter plots and bubble charts

Correlation heatmap

Pair plot for multivariate relationships

Key Insights-

The platform is heavily movie-dominated, with TV shows forming a smaller portion.
Content production has increased significantly after 2010, peaking between 2015–2020.
Drama, Comedy, and Action are the most common genres, while Crime and Thriller show more consistent ratings.
IMDb and TMDB ratings show strong agreement, validating ratings as a quality indicator.
Popularity metrics do not strongly correlate with ratings, indicating popularity ≠ quality.
Runtime, release year, and number of seasons have minimal impact on audience ratings.

Business Recommendations-

Increase investment in high-quality TV shows to improve user retention.
Balance content acquisition between popular titles and high-rated titles.
Expand region-specific and local-language content to improve market reach.
Use a multi-factor decision framework combining ratings, popularity, genre, and region instead of relying on a single metric.

Conclusion-

This project demonstrates how exploratory data analysis can effectively uncover meaningful insights from streaming platform data. The findings support a balanced, data-driven content strategy that emphasizes quality, diversity, and regional representation, helping improve audience engagement and business decision-making.
