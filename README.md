# nlp-webscraping-kmeans-clustering
## Overview

This project covers three applied data science topics such as time series analysis, 
natural language processing, unsupervised machine learning and
K-Means clustering task for customer segmentation.

---

## Question 1 — Petrol & Diesel Price Tracking (Time Series)

Analysed monthly petrol and diesel price data from January 2023 to December 2024 
using Pandas and Matplotlib.

- Loaded and preprocessed the dataset with a multi-level index (Year + Month)
- Made a `Price Difference` column (diesel minus petrol per month)
- Segmented data by year (2023 and 2024) into separate dataframes
- Visualised individual yearly trends, a combined 2-year trend, and the 
  monthly price difference over time
- Drew insights on fuel price fluctuation patterns across both years

**Key concepts:** Pandas indexing, time series visualisation, feature engineering

---

## Question 2 — Sentiment Analysis of Movie & Series Descriptions (NLP)

Applied sentiment analysis to a dataset of movie and series descriptions using 
a natural language processing library.

- Performed exploratory data analysis on rating distributions
- Computed sentiment polarity scores for each description using [TextBlob/VADER]
- Classified descriptions as Positive or Negative based on polarity score
- Visualised the distribution of sentiment labels
- Discussed limitations of rule-based NLP tools and methods to improve accuracy

**Key concepts:** NLP, TextBlob, sentiment classification, Pandas, Matplotlib

---

## Question 3 — Web Scraping Job Market Data

Built a Python web scraper to extract job postings from CareerJunction 
based on a user-supplied job title.

- Scraped job title, recruiter name, salary, position type, location, 
  and date posted from live search results
- Stored results in a structured Pandas dataframe
- Exported results to a CSV file named dynamically based on the search term
- Discussed challenges with dynamic websites and pagination strategies

**Key concepts:** requests, BeautifulSoup/Selenium, web scraping, CSV export

---

## Question 4 — K-Means Clustering for Customer Segmentation (ML)

Developed a clustering solution to segment over 1,000 customers based on 
income and spending behaviour.

- Cleaned the dataset by removing null values and isolating relevant features
- Applied the elbow method (WCSS) to determine the optimal number of clusters
- Fitted a K-Means model using the optimal k value
- Visualised clusters with colour-coded scatter plots and marked centroids
- Summarised cluster characteristics and discussed targeted marketing implications

**Key concepts:** Scikit-learn, K-Means clustering, elbow method, 
unsupervised ML, Matplotlib

---

## Tools & Libraries

- Python
- Pandas
- Matplotlib
- Numpy
- Seaborn
- TextBlob
- BeautifulSoup
- Scikit-learn
