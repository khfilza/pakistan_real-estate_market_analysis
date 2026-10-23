# Pakistan Real Estate Market Analysis

**Exploratory Data Analysis (EDA) of Zameen.com Property Listings**

## Overview

This project analyzes over 191,000 property listings from Zameen.com, Pakistan's leading real estate portal, to explore property pricing, regional differences, listing patterns, and market composition. The project uses Python-based exploratory data analysis to identify patterns and develop insights for property investors, buyers, sellers, and real estate agencies.

## Tools & Tech

- Python
- Pandas and NumPy
- Matplotlib and Seaborn
- Google Colab / Jupyter Notebook

## Methodology

The analysis covers five main areas:

1. **Data inspection:** Examining dataset structure, data types, descriptive statistics, and missing values.
2. **Data cleaning:** Handling missing values, removing irrelevant columns, standardizing property area measurements from Kanal to Marla, and extracting date features.
3. **Outlier detection:** Using boxplots, scatter plots, and the interquartile range (IQR) method to investigate unusual property prices and areas.
4. **Exploratory data analysis:** Performing univariate, bivariate, and multivariate analysis of prices, property types, cities, area, bedrooms, bathrooms, and listing purposes.
5. **Business analysis:** Investigating high-value listings, property preferences, agency and agent activity, monthly listing patterns, and sale-versus-rent distributions.

## Key Areas of Analysis

- Property price distributions and regional pricing differences
- Listing volumes by city and property type
- Relationships between price, area, bedrooms, and bathrooms
- Property type and pricing patterns across cities and provinces
- Listing activity over time and by month
- High-value property listings and agency representation

## Repository Contents

| File | Description |
|---|---|
| `zameen_com.ipynb` | Main notebook containing data preparation, visualizations, analysis, and business questions |
| `Pakistan Real Estate Market Analysis Report.pdf` | Summary of key findings and business recommendations |
| `Property.csv` | Property listings dataset, if included |

## Dataset

The dataset contains property listings from five major Pakistani cities: Karachi, Lahore, Islamabad, Rawalpindi, and Faisalabad. It includes property prices, locations, property types, area measurements, bedrooms, bathrooms, listing purposes, dates, agencies, and agents.

The notebook loads the semicolon-delimited CSV from Google Drive. To run it locally, update the dataset path to match your local environment and remove or replace the Google Colab-specific Drive mounting code.

## Key Takeaways

The analysis finds that houses dominate listing volumes, Karachi and Lahore lead in the number of listings, and property prices vary substantially across cities and property characteristics. It also examines relationships between property features and prices, temporal listing patterns, and opportunities related to agency representation.

For detailed results, visualizations, and business recommendations, see the **Pakistan Real Estate Market Analysis Report** and the analysis notebook.

## Limitations

The findings describe advertised listings within the dataset's coverage and time period. Listing prices do not necessarily represent completed transaction prices, and observed correlations do not establish causation.

---
