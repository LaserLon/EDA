# Global Greenhouse Gas Emissions and Temperature Change Analysis

## Introduction

This project aims to analyze the relationship between greenhouse gas emissions and temperature changes globally. By exploring data from various sources, we aim to understand if there is a correlation between the increase in greenhouse gas emissions and temperature changes over time.

This project is for educational and non-commercial purposes.

## Data Sources

The data used in this analysis were obtained or review from the following sources:
- **FAO**: [FAO Temperature Change Data](https://www.fao.org/faostat/en/#data/ET)
- **Kaggle**: [International Greenhouse Gas Emissions](https://www.kaggle.com/datasets/unitednations/international-greenhouse-gas-emissions)
- **UNdata**: [UNdata Explorer](http://data.un.org/Explorer.aspx)

## Data-Source Terms and Conditions of Use
- **Temperature Change on land Dataset**: Provided by the Food and Agriculture Organization of the United Nations (FAO) is licensed under the Creative Commons Attribution-NonCommercial-ShareAlike 3.0 IGO (CC BY-NC-SA 3.0 IGO)

- **Greenhouse Gas Emissions Data**: This dataset is provided by the United Nations on the UNData site and is hosted on Kaggle. According to the UNData terms of use all data provided on UNData’s website are available free of charge and may be copied freely, duplicated, and further distributed, provided that UNData is cited as the reference.

## Goals and Objectives

The primary goal of this project is to determine whether there is a significant correlation between the increase in greenhouse gas emissions and global temperature changes. Specifically, we aim to:

1. Explore and clean the datasets.
2. Merge datasets to create a comprehensive dataset for analysis.
3. Perform exploratory data analysis (EDA) to identify trends and patterns.
4. Visualize the data to understand the relationship between greenhouse gas emissions and temperature changes.
5. Draw conclusions based on the analysis.

## Data Description

- **Greenhouse Gas Inventory Data**: Contains data on greenhouse gas emissions by country and year.
- **Temperature Change Data**: Contains data on temperature changes by country, month, and year.
- **Continent Country List**: Provides a list of countries categorized by continent.

## Methodology

1. **Data Cleaning**: Handle missing values and convert data types as necessary.
2. **Data Transformation**: Pivot temperature change data to align with the structure of the greenhouse gas inventory data.
3. **Data Merging**: Merge the datasets on common keys (country and year).
4. **Exploratory Data Analysis**: Perform EDA to identify trends and patterns in the data.
5. **Visualization**: Create visualizations to illustrate the relationship between greenhouse gas emissions and temperature changes.

## Findings

From the analysis, we observed that:
- There is a noticeable trend of increasing greenhouse gas emissions over the years.
- Temperature changes vary significantly across different regions and months.
- Preliminary analysis suggests a correlation between increased emissions and temperature changes.

## Conclusion

The analysis provides insights into the potential relationship between greenhouse gas emissions and global temperature changes. While the preliminary findings suggest a correlation, further in-depth analysis and consideration of other factors are necessary to draw definitive conclusions.

## How to Run the Analysis

1. Clone the repository to your local machine.
2. Ensure you have all the necessary dependencies installed (see below).
3. Run the Jupyter Notebook `EDA.ipynb` to reproduce the analysis.

## Dependencies

- Python 3.x
- Pandas
- Matplotlib
- Prophet
- Jupyter Notebook


## Project Team
- Chelsey Hay
- Lonnie Aldredge
- Giselle Gomez