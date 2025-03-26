# Airbnb Seattle Data Analysis Dashboard

## Overview
This Tableau dashboard provides an in-depth analysis of Airbnb listings in Seattle, focusing on pricing, bedroom count, zip codes, and revenue trends. The visualization is designed to help users understand pricing patterns, geographical distribution, and revenue growth over time.

## Key Insights

### 1. **Average Price Per Bedroom**
- Shows the average price of Airbnb listings segmented by the number of bedrooms.
- Key values:
  - 1 Bedroom: $96.2
  - 2 Bedrooms: $175.4
  - 3 Bedrooms: $249.7
  - 4 Bedrooms: $315.4
  - 5 Bedrooms: $450.0
  - 6 Bedrooms: $584.8

### 2. **Count of Bedroom Listings**
- Displays the number of listings available per bedroom category:
  - 1 Bedroom: 1,811 listings
  - 2 Bedrooms: 483 listings
  - 3 Bedrooms: 206 listings
  - 4 Bedrooms: 55 listings
  - 5 Bedrooms: 20 listings
  - 6 Bedrooms: 5 listings

### 3. **Zip Codes with Number of Guests**
- A geographical map representing different zip codes in Seattle.
- Provides insights into which zip codes have the highest number of guest accommodations.

### 4. **Price by Zip Code**
- A bar chart comparing the average price of listings across different zip codes.
- Some key findings:
  - The highest average price is in zip code 98119.
  - Other high-priced zip codes include 98109, 98199, and 98105.
  - The lowest-priced zip codes are 98177 and 98133.

### 5. **Revenue of the Year 2016**
- A time-series analysis showing the revenue trend across the year 2016.
- Revenue started at approximately $6M and peaked above $8M mid-year before stabilizing.

## Technologies Used
- **Tableau**: For data visualization
- **Mapbox (OSM)**: For geographical data representation
- **Dataset**: Airbnb listings data for Seattle, 2016

## How to Use
1. **Explore Price Trends**: Identify how pricing varies by bedroom count and zip codes.
2. **Locate High-Demand Areas**: Use the map to find zip codes with the highest guest numbers.
3. **Analyze Revenue Trends**: Examine how revenue changed throughout the year to understand seasonality.

## Future Enhancements
- **Predictive Analysis**: Incorporate machine learning to forecast pricing trends.
- **More Filters**: Add interactivity for filtering by amenities, host type, and guest reviews.
- **Expanded Dataset**: Include data from multiple years for trend comparison.

## Repository Contents
- `dashboard.twbx`: Tableau Workbook containing the full dashboard.
- `data/airbnb_seattle.csv`: Raw dataset used for visualization.
- `images/dashboard_screenshot.png`: Screenshot of the dashboard.
- `README.md`: This documentation file.

