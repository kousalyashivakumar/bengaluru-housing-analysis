# bengaluru-housing-analysis
This project analyzes residential housing prices in Bengaluru to identify the key factors influencing property prices across different localities.
The analysis focuses on understanding how features such as total square footage, number of bedrooms (BHK), bathrooms, balconies, and location affect housing prices. The project also identifies value-driven locations based on average price per square foot.

# Business Objective

Homebuyers and real estate investors often face difficulty evaluating whether a property is fairly priced.

The objective of this project is to:

* Analyze housing price distribution in Bengaluru
* Identify major pricing drivers
* Compare locality-wise pricing trends
* Discover locations offering better value for money

# Dataset

Source: Kaggle Bengaluru House Price Dataset

# Features Used
* Area Type
* Availability
* Location
* Total Square Footage
* Bathrooms
* Balconies
* Price

# Tools & Libraries Used

Python
Pandas
Matplotlib
Seaborn
Jupyter Notebook
Power BI

# Data Cleaning & Preprocessing

The dataset required extensive preprocessing before analysis.

# Missing Value Handling

* Removed society column due to high missing values
* Dropped rows with missing location and size
* Filled missing numerical values using median imputation

# Total Square Footage Standardization

Handled inconsistent square footage formats:

* Converted value ranges into average values
* Removed unsupported unit-based entries

# Outlier Treatment

Applied IQR-based filtering to remove extreme outliers from the price-per-square-foot metric.

This improved analytical reliability and visualization clarity.

Exploratory Data Analysis

# The project includes:

* Property price distribution analysis
* BHK vs Price comparison
* Total Square Footage vs Price analysis
* Locality-wise premium pricing analysis
* Best value locations analysis
* Feature correlation heatmap

# Key Insights
# 1. Bengaluru housing prices are right-skewed

Most properties fall within the mid-range price segment, while a smaller number of luxury properties create a long-tail distribution.

# 2. Total square footage is the strongest pricing driver

Property size showed the highest correlation with price.

# 3. Location significantly impacts pricing

Properties with similar square footage often showed substantial price variation across different localities.

# 4. BHK influences price, but is not the sole determinant

The number of bedrooms affects pricing, but location and property size have stronger influence.

# 5. Several localities offer better value per square foot

Locations such as Chandapura and Bommasandra Industrial Area emerged as relatively affordable options.

# This project also includes an interactive Power BI dashboard built using the cleaned housing dataset.

The dashboard provides:

Market overview metrics
Locality-wise pricing analysis
Property feature impact analysis
Interactive filtering for location-based exploration
Dashboard Highlights

# Market Overview

Total Listings
Average Property Price
Average Price Per Sqft
Average BHK

# Location Analysis

Premium localities
Best value locations

# Feature Analysis

Property size vs price
BHK-based pricing patterns
Feature correlation insights

# Conclusion

This analysis demonstrates how data-driven exploration can uncover meaningful housing market patterns.

# The findings can help:

* Homebuyers identify value-driven localities
* Investors compare pricing trends
* Analysts understand major residential pricing factors in Bengaluru
