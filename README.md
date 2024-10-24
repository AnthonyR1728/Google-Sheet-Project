# Airbnb Vacation Rental Market Analysis - Manhattan, NYC

# Project Overview
This project aims to help a client analyze the vacation rental market in Manhattan, New York City, with a focus on identifying the most promising types of properties for investment. The analysis is based on Airbnb listings data, including property characteristics, pricing, reviews, and occupancy. The goal is to provide actionable insights that will guide the client’s investment decisions.

# Project Objectives

1. Data Exploration and Cleaning: Review, clean, and document the Airbnb dataset to make it ready for analysis.

2. Target Property Types: Identify the property types and neighborhoods with the highest potential for vacation rental investment.

3. Occupancy Rate Analysis: Calculate occupancy rates based on the Airbnb calendar data.

4. Revenue Estimation: Estimate potential annual revenue for a given property type in a specific neighborhood.

5. Additional Insights (Optional): Explore other key property features that may impact rental performance, such as superhost status, instant booking, and amenities.

# Dataset

You can download the NYC Airbnb dataset from the following link: ![NYC Airbnb Dataset](https://docs.google.com/spreadsheets/d/1FEio_C-DoA8l4XYnPE80C_Z5Dv5zAQxgkGFePEBBAH4/edit?gid=146489528#gid=146489528)

The dataset contains the following key sheets:

data_dictionary: Provides an overview of column names and their descriptions.
listings: Contains details about the available Airbnb properties, such as price, location, number of bedrooms, and reviews.
calendar: Contains the availability and pricing data for each listing over a 30-day period.
Part 1 - Data Exploration and Cleaning
Review the Data: Spend time understanding each sheet, especially the listings and calendar data.
Data Cleaning: Document any data cleaning steps such as:
Removing irrelevant listings (e.g., inactive listings with no reviews).
Standardizing neighborhood names (e.g., "West Village", "WEST VILLAGE").
Creating new columns (e.g., bedrooms_clean, neighborhood_clean).
Part 2 - Property Targeting
Filter Listings: Identify relevant listings by focusing on properties with a minimum stay of 7 days or fewer, and listings that have reviews in the last 12 months as a proxy for rental activity.
Neighborhood Analysis: Clean and analyze neighborhood data to identify the top areas for vacation rentals.
Create a pivot table to determine which neighborhoods have the most active rentals based on the number of reviews.
Part 3 - Occupancy Rate Calculation
Convert Availability to Occupancy: Create a new column (occupied) in the calendar data to indicate whether a property was booked (1 for booked, 0 for available).
Pivot Table Analysis: Calculate the average occupancy rate for each listing and the top 10 most popular neighborhoods. Determine which property sizes are most in demand.
Part 4 - Revenue Estimation
Estimate Annual Revenue: Choose a representative neighborhood and property type based on the earlier analysis.
Calculate average price and occupancy rates using a pivot table.
Formula for annual revenue:
Annual Revenue = 365 days * Average Price * Average Occupancy Rate.
Part 5 - Optional Insights
Property Attributes: Analyze additional attributes such as superhost status, instant booking, and specific amenities (e.g., doorman) to determine if they impact pricing or occupancy rates.
Part 6 - Documentation and Spreadsheet Formatting
Executive Summary: Create a summary sheet with key recommendations and a table of contents for easy navigation.
Clear Formatting: Organize the spreadsheet with clear labels, standardized formatting, and consistent font styles. Ensure that all data cleaning steps are thoroughly documented.
How to Use This Project
Download the Dataset: Use the provided dataset link and explore the data in Google Sheets or Excel.
Follow the Steps: Work through each part of the analysis, documenting every data cleaning and transformation step.
Pivot Tables: Use pivot tables to calculate key metrics such as occupancy rates, top neighborhoods, and property sizes.
Revenue Estimation: Use the provided formulas to estimate potential earnings for selected property types.
Tools Used
Google Sheets: For data exploration, cleaning, and analysis.
Pivot Tables: Used to aggregate and summarize the data.
Formulas: Includes common spreadsheet formulas like VLOOKUP(), WEEKDAY(), CHOOSE(), and more.
Next Steps
Complete the optional analysis on property attributes.
Format and polish the spreadsheet for final client delivery.
Feel free to fork and customize this project to fit similar analyses in other markets.
