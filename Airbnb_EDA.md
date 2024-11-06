# Exploratory Data Analysis (EDA) on Airbnb Listings

## Project Overview
This project conducts an exploratory data analysis (EDA) on Airbnb listings to gain insights into the patterns and trends across various listing features. This repository contains the dataset, Jupyter notebooks with code, and visualizations.

**Project Objectives:**
1. Clean and preprocess the dataset to handle missing values and ensure data quality.
2. Perform descriptive and exploratory analysis on features such as price, availability, and reviews.
3. Generate visualizations to understand relationships between key attributes.

## Repository Structure
- `data/`: Contains the Airbnb dataset (or sample data) used for analysis.
- `notebooks/`: Jupyter notebook with all data cleaning, EDA, and visualizations.
- `images/`: Images and visualizations generated in the notebook.
- `video/`: A project overview video describing the process and findings.

## Dataset Overview
The dataset contains information on Airbnb listings, including attributes such as:
- `listing_id`: Unique identifier for each listing.
- `date`: Dates associated with availability.
- `price`: Price per night for each listing.
- `reviews_per_month`: Average monthly reviews for each listing.

## Installation
1. Clone the repository:
   ```bash
   git clone https://github.com/UtkarshaSakarekar/CODING-SAMURAI.git

# Data Insights 

## Price and Accommodation Features
The typical price, for properties varies widely ranging from 20 to 1000 with an average of $128. This shows that there is a range of options to suit different budgets. 

Most properties are priced towards the lower to mid range. There are also quite a few priced listings leading to a right skewed distribution. 

A noticeable trend is the connection between price and both the number of bedrooms (0.63) and the capacity, for guests (0.65) indicating that larger accommodations tend to come with price tags.

## Property and Room Types
When it comes to properties and the types of rooms available you'll find that houses and apartments are the choices, on Airbnb. This reflects a blend of what travelers prefer. A mix of accommodation and cozy, home like experiences.

Looking at the room preferences it's clear that most guests lean towards booking homes or apartments followed by private rooms. This suggests that privacy and having space are priorities for travelers.

In terms of pricing based on room type it's evident that entire homes or apartments tend to have prices compared to shared rooms. This aligns with the idea that people're willing to pay more, for privacy and spacious accommodations.

## Neighborhood Popularity

Capitol Hill, Downtown and the Central Area stand out as the sought, after neighborhoods based on the number of listings. This suggests they are quite popular among visitors. Looking at the availability data for each neighborhood it appears that some areas have short term rentals which could indicate either a higher turnover rate or lower demand. On the hand neighborhoods with availability might be more desirable or attract longer term guests. The average review scores are notably high 95 out of 100 showcasing guest satisfaction. This positive feedback likely plays a role, in drawing visitors to Airbnb listings in these neighborhoods.

## Occupancy and Availability

The estimated annual occupancy rate of about 33% provides a baseline understanding of how often properties are booked. This figure will vary greatly by neighborhood and property type. Availability seems to vary significantly between neighborhoods, suggesting localized differences in demand or seasonality that could influence hosts' pricing strategies.

## Correlation Insights

The correlation matrix reveals several expected relationships, such as the strong positive correlation between the number of bedrooms/bathrooms and the accommodation capacity. Interestingly, the number of reviews has a slightly negative correlation with price (-0.12), possibly indicating that more expensive listings attract fewer reviews, or that guests are less inclined to leave reviews for higher-priced stays. Minimum nights required for a booking show very little correlation with other features, indicating that this policy is likely set independently of the property’s characteristics or price.
