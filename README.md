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

The dataset contains the following key sheets:

1. data_dictionary: Provides an overview of column names and their descriptions. [Data_Dictionary](https://github.com/AnthonyR1728/Google-Sheet-Project/blob/990bab563007b31b30d2434c5137c2e50458ae25/Anthony%20Rappa's%20%20nyc_airbnb_data%20project%20-%20data_dictionary.pdf)

2. listings: Contains details about the available Airbnb properties, such as price, location, number of bedrooms, and reviews.

3. calendar: Contains the availability and pricing data for each listing over a 30-day period.

# Part 1 - Data Exploration and Cleaning

1. Review the Data: Spend time understanding each sheet, especially the listings and calendar data.

2. Data Cleaning: Document any data cleaning steps such as:

    A. Removing irrelevant listings (e.g., inactive listings with no reviews).

    B. Standardizing neighborhood names (e.g., "West Village", "WEST VILLAGE").

    C. Creating new columns (e.g., bedrooms_clean, neighborhood_clean).


# Part 2 - Property Targeting

1. Filter Listings: Identify relevant listings by focusing on properties with a minimum stay of 7 days or fewer, and listings that have reviews in the last 12 months as a proxy for rental activity.

2. Neighborhood Analysis: Clean and analyze neighborhood data to identify the top areas for vacation rentals.

    A. Create a pivot table to determine which neighborhoods have the most active rentals based on the number of reviews. [Top Neighborhoods](https://github.com/AnthonyR1728/Google-Sheet-Project/blob/57d950cbb0e240e7dab0b782087abe136fd83935/Anthony%20Rappa's%20%20nyc_airbnb_data%20project%20-%20top%20ten%20neighborhoods%20(1).pdf)

# Part 3 - Occupancy Rate Calculation

1. Convert Availability to Occupancy: Create a new column (occupied) in the calendar data to indicate whether a property was booked (1 for booked, 0 for available).

2. Pivot Table Analysis: Calculate the average occupancy rate for each listing and the top 10 most popular neighborhoods. Determine which property sizes are most in demand.
[Top Ten Property Sizes](https://github.com/AnthonyR1728/Google-Sheet-Project/blob/9e77b0f4b477cf55dc1ad8539afc0078f957f4f0/Anthony%20Rappa's%20%20nyc_airbnb_data%20project%20-%20top%20ten%20property%20sizes%20(1).pdf)

# Part 4 - Revenue Estimation

1. Estimate Annual Revenue: Choose a representative neighborhood and property type based on the earlier analysis.

    A. Calculate average price and occupancy rates using a pivot table. [Occupancy Rates](https://github.com/AnthonyR1728/Google-Sheet-Project/blob/2c20a4eb79a73560e2708e037176fced35be2f89/Anthony%20Rappa's%20%20nyc_airbnb_data%20project%20-%20Lower%20East%20Side%20Average%20price%20and%20occupancy%20table.pdf)

    B. Formula for annual revenue:
     Annual Revenue = 365 days * Average Price * Average Occupancy Rate.

# Part 5 - Optional Insights

1. Property Attributes: Analyze additional attributes such as superhost status, instant booking, and specific amenities (e.g., doorman) to determine if they impact pricing or occupancy rates.

# Part 6 - Documentation and Spreadsheet Formatting

1. Executive Summary: Create a summary sheet with key recommendations and a table of contents for easy navigation.[Executive Summary](https://github.com/AnthonyR1728/Google-Sheet-Project/blob/aa99c31acc99e5f841e2e1be99f73d12ae6993dc/Anthony%20Rappa's%20%20nyc_airbnb_data%20project%20-%20Executive%20Summary.pdf) [Table of Contents](https://github.com/AnthonyR1728/Google-Sheet-Project/blob/c06d1a2677e25db5df2b874be76e7791ffa324cf/Anthony%20Rappa's%20%20nyc_airbnb_data%20project%20-%20Table%20Of%20Contents%20-%20Copy.pdf)

2. Clear Formatting: Organize the spreadsheet with clear labels, standardized formatting, and consistent font styles. Ensure that all data cleaning steps are thoroughly documented.

# Tools Used
Google Sheets: For data exploration, cleaning, and analysis.
Pivot Tables: Used to aggregate and summarize the data.
Formulas: Includes common spreadsheet formulas like VLOOKUP(), WEEKDAY(), CHOOSE(), and more.
Data: Supplied by Tripleten 
