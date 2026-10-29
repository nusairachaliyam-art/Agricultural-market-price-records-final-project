# Agricultural-market-price-records-final-project
Analysis of agricultural commodity prices across Indian markets using Python, Pandas, NumPy, Matplotlib, and Seaborn, including data cleaning, exploratory data analysis, and visualization.
# Agriculture Market Price Records Analysis

## 1. Project Overview
This project analyzes agricultural commodity prices across different states, districts, and markets in India. The analysis uses daily mandi price data to understand price variations, compare average modal prices, identify frequently reported commodities, and examine relationships between minimum, maximum, and modal prices.

The project was completed using Python in Google Colab.

## 2. Project Objectives
- Analyze the minimum, maximum, and modal prices of agricultural commodities.
- Compare average modal prices across states and markets.
- Identify commodities with the highest and lowest average modal prices.
- Study the distribution of modal prices and identify unusual price records.
- Compare average modal prices across the two available dates.
- Examine the relationship between minimum, maximum, and modal prices.
- Visualize important patterns and findings using charts.

## 3. Dataset Description
- **Dataset name:** Current Daily Price of Various Commodities from Various Markets (Mandi)
- **Source:** Government of India Open Government Data Platform
- **Number of records:** 28,268
- **Number of columns:** 10
- **Number of unique commodities:** 256
- **Dates covered:** 13 October 2026 and 16 October 2026

### Dataset Columns
1. `State`
2. `District`
3. `Market`
4. `Commodity`
5. `Variety`
6. `Grade`
7. `Arrival_Date`
8. `Min_Price`
9. `Max_Price`
10. `Modal_Price`

The dataset contains information about agricultural commodities and their reported prices in different markets.

## 4. Tools and Technologies
- **Python** – Programming language used for analysis.
- **Pandas** – Data loading, cleaning, and manipulation.
- **NumPy** – Numerical operations.
- **Matplotlib** – Data visualization.
- **Seaborn** – Statistical charts and correlation heatmap.
- **Google Colab** – Notebook development and execution.
- **GitHub** – Project version control and file sharing.

## 5. Data Cleaning
The following data-cleaning activities were performed:
- Checked the dataset structure, column names, and data types.
- Converted the arrival-date column to a suitable date format.
- Checked for missing values and duplicate records.
- Removed unnecessary leading and trailing spaces from text values.
- Standardized selected inconsistent category labels.
- Checked price columns for invalid and unusual values.
- Compared minimum, modal, and maximum prices for consistency.
- Examined potential outliers without automatically deleting valid high-price records.

## 6. Exploratory Data Analysis
Exploratory data analysis was performed to understand the distribution and variation of agricultural commodity prices.

The analysis included:
- Summary statistics for minimum, maximum, and modal prices.
- Average modal price by commodity.
- Average modal price by state.
- Market-level price comparisons.
- Commodity frequency analysis.
- Comparison of average modal prices between the two dates.
- Identification of unusually high and low price records.
- Correlation analysis of price columns.

## 7. Data Visualizations
The project includes visualizations such as:
- Top 10 commodities by average modal price.
- Top 10 states by average modal price.
- Histogram of modal prices up to ₹20,000.
- Box plot of modal prices up to ₹20,000.
- Scatter plot comparing minimum and maximum prices.
- Comparison of average modal prices between the two dates.
- Correlation heatmap.
- Comparison of average modal prices for Bitter Gourd across selected markets.

## 8. Key Findings
- Cardamom had the highest average modal price among the commodities analyzed, at approximately ₹315,000.
- Manipur had the highest average modal price among the states shown in the top-10 comparison.
- The average modal price was approximately 5,464.88 on 13 October 2026 and 5,445.03 on 16 October 2026.
- Tomato, Brinjal, Onion, and Potato were among the most frequently reported commodities.
- Minimum, maximum, and modal prices showed strong positive correlations.
- Some unusually low and high price records were identified for further verification.

**Note:** These findings describe the available dataset and do not necessarily represent long-term price trends.

## 9. Limitations
- The dataset covers only two dates.
- The number of records differs across states, commodities, and markets.
- Some unusual price values require verification with the original source.
- The dataset does not include additional factors such as weather, transportation costs, production, or demand.

## 10. Future Scope
Future work could include:
- Analyzing daily prices over a longer period.
- Comparing the same commodities across states and markets.
- Investigating unusual price records.
- Combining price data with weather, production, and supply information.
- Developing an interactive dashboard.
- Applying forecasting techniques when sufficient historical data is available.

## 11. Dataset Source
Government of India Open Government Data Platform:

https://www.data.gov.in/resource/current-daily-price-various-commodities-various-markets-mandi

## 12. Project Files
This repository contains:
- **Jupyter Notebook (`.ipynb`)** – Python code, data cleaning, analysis, and visualizations.
- **Original Dataset** – The dataset used for the project.
- **README.md** – Project overview, objectives, methods, and findings.
