# Airbnb New York City Expansion Analysis

This repository contains a collection of Jupyter notebooks developed during the "Python to Data Science" course offered by Comunidade DS. The course simulated a real-world data science project where we were tasked with assisting Airbnb CEO in making informed decisions regarding the company expansion into the New York City market.

## Project Overview

Airbnb's expansion into New York City is a significant undertaking with both opportunities and risks. To minimize those risks, we employed data analysis to answer key questions posed by the CEO, ultimately guiding strategic commercial and marketing decisions.

## Dataset

We utilized the ["New York City Airbnb Open Data"](https://www.kaggle.com/datasets/dgomonov/new-york-city-airbnb-open-data) dataset sourced from Kaggle. This dataset provides comprehensive information about Airbnb listings in New York City, including:

- `id`: A unique identifier for each Airbnb listing.
- `name`: The title or name that the host has given to their listing.
- `host_id`: A unique identifier for each Airbnb host.
- `host_name`: The name of the Airbnb host.
- `neighbourhood_group`: The broader borough or area of New York City where the listing is located (e.g., Manhattan, Brooklyn, Queens).
- `neighbourhood`: The more specific neighborhood within the neighbourhood_group where the listing is situated (e.g., Harlem, Kensington, Midtown).
- `latitude`: The geographic latitude coordinate of the listing.
- `longitude`: The geographic longitude coordinate of the listing.
- `room_type`: The type of accommodation being offered (e.g., "Private room," "Entire home/apt").
- `price`: The price per night for the listing, in US dollars.
- `minimum_nights`: The minimum number of nights a guest must book for the listing.
- `number_of_reviews`: The total number of reviews the listing has received.
- `last_review`: The date of the most recent review for the listing.
- `reviews_per_month`: An estimate of the average number of reviews the listing receives per month.
- `calculated_host_listings_count`: The estimated number of listings the host has in total.
- `availability_365`: The number of days in the next 365 days that the listing is available for booking.

## Objectives

The primary objective of this project was to answer a series of questions posed by the CEO concerning the New York City Airbnb market. These questions, divided into three rounds, addressed key aspects such as average rent, regional variations, property types, host distribution, price fluctuations, review distribution, and the geographic distribution of listings.

## Methodology

We adopted a structured three-step approach for tackling each round of questions:

1. **Final Product Planning:** Defining the format in which the answer will be delivered to CEO and how we will present the answers.
2. **Process Planning:** Outlining the steps required to reach the answer (e.g., data cleaning, transformation, analysis).
3. **Tool Planning:** Selecting the appropriate Python libraries and tools to implement the process (e.g., Pandas, NumPy, Matplotlib, Plotly).

## Analysis and Results

Each Jupyter notebook within this repository corresponds to a specific round of questions from the CEO. Within each notebook, we:
- Loaded and cleaned the Airbnb dataset using Pandas.
- Performed exploratory data analysis using NumPy and Pandas to calculate descriptive statistics, identify trends, and uncover insights.
- Visualized the data using Matplotlib, Plotly and Folium to create informative charts, histograms, and maps.

Detailed explanations and interpretations of the results are provided within each notebook, alongside the corresponding Python code.

**OBS - In addition to answering the CEO's questions, this repository also includes supplementary files containing exercises designed to reinforce the understanding of key Python concepts and data manipulation techniques used throughout the project.**

## Libraries
The following Python libraries were instrumental in this project:
- `Pandas`: for data manipulation and analysis.
- `NumPy`: for numerical computing.
- `Matplotlib`: for creating static, interactive, and animated visualizations.
- `Plotly`: for creating interactive web-based visualizations.
- `Folium`: for creating leaflet maps.

--------------------------

To explore the analysis and findings, simply navigate through the Jupyter notebooks within this repository. Each notebook is self-contained and provides a comprehensive walkthrough of the data analysis process for each round of CEO questions.
