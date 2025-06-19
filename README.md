# Project Overview

This project focuses on analyzing real estate data for Toulouse and its suburbs. Immo-Inv, a real estate agency, aims to gain a deep understanding of the local real estate market. The dataset spans five years and includes details of houses and apartment sales transactions in Toulouse and its surrounding areas.

The goal of this analysis is to explore various aspects of the real estate market, identify relationships between variables, uncover trends, and detect patterns or outliers. The analysis is designed to be scalable, allowing for application to larger datasets, such as the entire real estate market in France.

The project utilizes Apache Spark for big data processing and Python for visualization and result presentation.

# Dataset Details:
The dataset contains the following attributes for each transaction:

SaleDate: Date of the transaction.
SaleType: Type of sale (e.g., new sale, resale).
Price: Sale price of the property.
PostCode: Postal code of the property.
City: City where the property is located.
NbRooms: Number of rooms in the property.
NbLots: Number of lots associated with the transaction.
ResidenceType: Type of residence (e.g., house, apartment).
LivingArea: Size of the living area in square meters.
LandArea: Size of the land in square meters.

# Findings:
After running the analysis above the followed insights are highlighted:
  1. **Average Price Trends**: The analysis reveals that the average price per square meter in Toulouse is approximately 11838.16 euros. Notably, there is a considerable variation in prices for smaller apartments, indicating a diverse real estate market.
  2. **Regional Price Dynamics**: Postcode 31000 emerges as a standout area with the highest average price per square meter, while prices generally decrease from postcode 31400 onwards. This suggests distinct regional pricing dynamics within the city.
  3. **Property Size Preferences**: 4-room houses dominate the real estate landscape, constituting 81% of total house sales. On the other hand, customer preferences lean towards smaller apartments, with 1, 2, and 3-room units contributing to 82% of apartment sales.
  4. **Yearly Price Variability**: The analysis uncovers substantial year-over-year variability in house prices, marked by a notable drop in 2017 and a significant rise in 2019. Apartments exhibit a similar trend, with fluctuations in 2016, 2017, and 2018.
  5. **Correlation Insights**: The data suggests a weak positive correlation between the number of houses sold and the average price per square meter. In contrast, there is a moderately positive correlation between the number of apartments sold and their average price per square meter. These insights provide valuable information for understanding market trends and informing real estate decisions in Toulouse.

These insights provide a comprehensive understanding of the real estate market trends, regional variations, and customer preferences in Toulouse. The analysis indicates the importance of factors such as living area, number of rooms, and geographical location in influencing property prices and sales patterns.
