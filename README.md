# Car Market Trends Analysis with CarDekho Data

## Project Overview

This project focuses on analyzing used car market data from CarDekho to identify important trends and patterns in car selling prices.

The analysis uses Python and data visualization techniques to understand how factors such as car year, fuel type, and transmission type are related to selling prices.

## Problem Statement

Used car prices can vary depending on different factors such as the car model, manufacturing year, fuel type, and transmission type.

The main aim of this project is to analyze the available CarDekho data and identify useful patterns in used car selling prices.

## Objectives

- Analyze the used car dataset.
- Clean and prepare the data for analysis.
- Identify the cars with the highest selling prices.
- Study the trend of average selling prices across different years.
- Compare average selling prices by fuel type.
- Compare average selling prices by transmission type.
- Present the findings using clear data visualizations.

## Dataset

The dataset contains information about used cars, including:

- Car Name
- Year
- Selling Price
- Present Price
- Kilometers Driven
- Fuel Type
- Seller Type
- Transmission
- Owner

The dataset was checked for missing values and duplicate records before performing the analysis.

## Data Cleaning

The following steps were performed during data preparation:

1. Loaded the dataset using Pandas.
2. Checked the structure and dimensions of the dataset.
3. Checked for missing values.
4. Checked for duplicate records.
5. Removed duplicate records from the dataset.
6. Prepared the cleaned data for visualization and analysis.

## Technologies Used

- **Python** – Main programming language
- **Pandas** – Data loading and data cleaning
- **NumPy** – Data processing
- **Matplotlib** – Data visualization
- **Seaborn** – Statistical visualization
- **Jupyter Notebook** – Analysis and execution environment

## Data Visualizations

The project includes the following visualizations:

### 1. Top 10 Cars by Selling Price

This visualization identifies the 10 cars with the highest selling prices in the dataset.

### 2. Average Selling Price Trend by Year

This visualization shows how the average selling price changes across different manufacturing years.

### 3. Average Selling Price by Fuel Type

This visualization compares the average selling prices of Petrol, Diesel, and CNG cars.

### 4. Average Selling Price by Transmission

This visualization compares the average selling prices of Manual and Automatic cars.

## Key Findings

- Land Cruiser has the highest selling price among the top 10 cars analyzed.
- The average selling price generally shows an increasing trend for newer car years, although some fluctuations can be observed.
- Diesel cars have the highest average selling price among the fuel types analyzed.
- Automatic cars have a higher average selling price than manual cars in this dataset.

## Project Files

- `CarMarketTrendAnalysis.csv` – Dataset used for the analysis
- `cardekho.ipynb` – Python/Jupyter Notebook containing the analysis and visualizations
- `TOP10Cars_bySellingPrice.png` – Top 10 cars by selling price
- `AvgSellingPrice_byYear.png` – Average selling price trend by year
- `AvgSellingPrice_byFuel.png` – Average selling price by fuel type
- `AvgSellingPrice_byTransmission.png` – Average selling price by transmission
- `README.md` – Project documentation

## Conclusion

The analysis provides a simple overview of used car selling price patterns using CarDekho data.

The visualizations help in understanding differences in selling prices across car years, fuel types, transmission types, and individual car models.

This project demonstrates how Python-based data analysis and visualization can be used to extract meaningful insights from a real-world dataset.
