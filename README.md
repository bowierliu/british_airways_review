# British Airways Customer Review Analysis

## Project Overview

This project focuses on analyzing customer reviews for British Airways (BA) by exploring and visualizing the data through a combination of Excel and Tableau. The goal is to extract insights related to customer satisfaction, identify trends in reviews, and determine how different factors such as customer location may influence their review ratings.

The project leverages the dataset provided in `ba_reviews.csv` and additional country information from `Countries.csv`. Data visualization is done using Tableau in the workbook `British Airways Review.twb`.

## Files in the Repository

- **ba_reviews.csv**: This CSV file contains customer review data, including:
  - `Review ID`: A unique identifier for each review.
  - `Rating`: The rating given by the customer (out of 5).
  - `Review Text`: The text content of the customer review.
  - `Date`: The date the review was written.
  - Other features related to the customer’s experience with British Airways.

- **Countries.csv**: This CSV file contains information about the countries where the reviewers are located. It includes:
  - `Country Name`: The name of the country.
  - `Country Code`: The ISO code for the country.
  
- **British Airways Review.twb**: This Tableau workbook contains data visualizations that provide insights into the customer review data. It includes various interactive dashboards that allow for an in-depth analysis of review trends, satisfaction ratings, and geographic breakdowns of reviewer sentiments.

## Project Goals

1. **Review Analysis**: Explore customer reviews to identify key themes, analyze sentiment, and detect common complaints or praises.
   
2. **Data Visualization**: Create insightful visualizations in Tableau to help uncover trends in customer satisfaction, differences in reviews based on customer location, and how ratings vary over time.

## Getting Started

### Prerequisites

- **Tableau**: Required to open the `British Airways Review.twb` file. You can download Tableau [here](https://www.tableau.com/products/desktop).
  
- **Spreadsheet Software**: Use Excel or another spreadsheet program to explore and preprocess the data in `ba_reviews.csv` and `Countries.csv`.

### Instructions

1. **Data Exploration**:
   - Open the `ba_reviews.csv` file in Excel or any other spreadsheet software.
   - Review the data columns to understand customer ratings, reviews, and the dates the reviews were submitted.

2. **Country Data**:
   - Use the `Countries.csv` file for additional information about the reviewer’s country location, which can be joined with the reviews data.

3. **Data Visualization**:
   - Open the `British Airways Review.twb` file in Tableau.
   - Explore various visualizations, including sentiment analysis, rating trends, and geographical review breakdowns.

### Installation

There is no specific installation required for this project aside from having the necessary tools to open the files:
- **Tableau** for data visualization.
- **Excel or Google Sheets** to open and preprocess the CSV files.

## Visualizations

The Tableau workbook includes the following visualizations:

- **Customer Rating Distribution**: A distribution of customer ratings across all reviews.
- **Sentiment Analysis**: A word cloud and other text analytics to extract common themes and sentiments from the review text.
- **Geographic Insights**: A map showing the distribution of review ratings based on the customer’s location (linked with the `Countries.csv` file).
- **Time Series Analysis**: A line chart that tracks customer ratings over time to detect trends in customer satisfaction.

## Acknowledgments

- Customer review data provided by British Airways public reviews.
- Visualization tools and analysis provided by Tableau.
