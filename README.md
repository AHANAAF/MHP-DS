
This analysis of the Melbourne House Price dataset provides insights into the factors that influence house prices in different suburbs and regions of Melbourne. Here's a summary of the key points:

Data Overview:

The dataset includes 21 attributes related to house sales in Melbourne, such as suburb, address, number of rooms, price, type of property, distance from the CBD, and more.
Data Preprocessing:

The Bedroom2 attribute was found to be similar to the Rooms attribute and was therefore removed to avoid redundancy.
Missing values in attributes like BuildingArea and YearBuilt were handled by either filling or removing them, depending on the significance of the missing data.
Outliers such as houses with a BuildingArea of 0 were removed to improve data quality.
Exploratory Data Analysis:

Univariate Analysis: The price distribution was found to be positively skewed, with most houses priced around 1 million dollars. Log transformation was applied to normalize the price distribution.
Bivariate Analysis:
Suburb Analysis: Suburbs like Canterbury, Malvern, and Middle Park were identified as the most expensive.
Room Analysis: House prices tend to increase with the number of rooms, showing a linear relationship.
Region Analysis: Southern and Eastern Metropolitan regions were identified as the most expensive, while Northern and Western Metropolitan regions were more affordable.
Type of House: House types (e.g., villa, townhouse) significantly impact prices, with cottages and villas being the most expensive.
Method of Sale: Different methods of sale (e.g., auction, private sale) showed varying price distributions, with vendor bids often leading to higher prices.
Distance from CBD: A negative correlation was observed between house prices and distance from the CBD, meaning closer proximity to the city center leads to higher prices.
Council Area: Certain council areas, particularly those closer to the CBD, have higher house prices.
Correlation Analysis:

Positive correlations were found between house prices and attributes like the number of rooms, bathrooms, and building area.
A negative correlation was observed between house prices and distance from the CBD.
Region-Specific Insights:

Southern Metropolitan: Predominantly duplex and villa houses with 2-4 rooms and 1-2 bathrooms.
Northern Metropolitan: Similar trends with duplex and villa properties being common.
Eastern Metropolitan: Also follows similar trends in terms of common house types and amenities.
This analysis provides a comprehensive understanding of the Melbourne housing market, highlighting how various features like location, house type, and proximity to the CBD influence house prices.
