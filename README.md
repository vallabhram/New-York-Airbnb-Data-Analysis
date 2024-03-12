# New-York-Airbnb-Data-Analysis

This repository contains Python code for analyzing the New York Airbnb dataset. The analysis explores various aspects of the dataset to gain insights into pricing trends, location popularity, host behavior, and customer ratings.


**Dataset Overview**

The dataset used in this analysis is sourced from the New York Airbnb listings for the year 2024. It includes various features such as:

listing_id: Unique identifier for each listing.

host_id: Unique identifier for each host.

borough: Borough where the listing is located (e.g., Manhattan, Brooklyn).

neighbourhood: Neighborhood where the listing is situated.

room_type: Type of room offered (e.g., Entire home/apt, Private room).

price: Price per night for the listing.

availability_365: Number of days the listing is available in a year.

rating: Average rating of the listing.

license: License status of the listing.

last_review: Date of the last review for the listing.


**Analysis Highlights**


**Data Preprocessing**

Excluded rows with zero availability to focus on available listings.

Handled missing values in the dataset.


**Exploratory Data Analysis (EDA)**

Explored basic statistics and distributions of numerical features.

Investigated the distribution of ratings and correlations between numerical features.

Analyzed the count of listings and average prices per borough using bar plots and box plots.

Examined the percentage of listings with high ratings (4+ and 4.5+) across different boroughs.

Investigated the impact of licensing status on average ratings.

Explored the distribution of review dates to understand recent activity.


**Insights and Findings**

Identified the top 10 hosts with the most listings and their average ratings.

Explored the distribution of bedrooms and beds per listing.

Conducted regression analysis on price and rating variables to understand their relationships.


**Requirements**

Python 3.x

Pandas

Matplotlib

Seaborn


**Future Work**

Further exploration of host behaviors and their impact on listing ratings.

Time-series analysis to identify trends in availability and pricing over time.

Sentiment analysis on reviews to understand customer satisfaction trends.


**Contributing**

Contributions to this project are welcome. If you have any suggestions, feedback, or new analyses to add, please open an issue or submit a pull request.


**License**

This project is licensed under the MIT License - see the LICENSE file for details.
