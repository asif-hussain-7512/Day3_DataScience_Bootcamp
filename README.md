# Day3_DataScience_Bootcamp

# Used Car Price Prediction - Data Preprocessing

## Dataset Overview
This project performs Exploratory Data Analysis (EDA), Data Cleaning, and Feature Engineering on a used car price prediction dataset.

## Data Quality Issues
- Missing values
- Duplicate records
- Outliers
- Incorrect data types

## Cleaning Techniques
- Filled missing numerical values with median
- Filled missing categorical values with mode
- Removed duplicate rows
- Removed outliers using IQR
- Corrected data types

## Feature Engineering
- Car Age
- Mileage Per Year
- Has Accident
- Clean Title Flag
- Luxury Brand Indicator

## Key Insights
1. The dataset contains a diverse range of used cars from multiple brands, with popular manufacturers contributing the majority of listings, indicating a varied and competitive used car market.
2. Most vehicles are relatively recent models, with a higher concentration of cars manufactured after 2015, suggesting that newer vehicles dominate the dataset.
3. Mileage has a noticeable impact on price. Cars with higher mileage generally have lower selling prices, indicating a negative relationship between mileage and vehicle value.
4. Luxury brands tend to command higher prices than economy brands, even for used vehicles, highlighting the influence of brand reputation on resale value.
5. Vehicles with a clean accident history and clean title generally have higher prices than those with reported accidents or title issues, showing that vehicle condition significantly affects resale value.

## Files
- task-3.ipynb
- cleaned_used_cars.csv
- README.md
