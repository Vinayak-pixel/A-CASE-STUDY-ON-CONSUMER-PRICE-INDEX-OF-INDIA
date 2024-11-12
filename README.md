# A CASE STUDY ON CONSUMER PRICE INDEX OF INDIA | Time Series, Regression | Python, R, Excel |

## Introduction
This project analyzes the Consumer Price Index (CPI) of India, a crucial economic indicator reflecting the average change in prices paid by consumers for a basket of goods and services over time. CPI provides insights into inflation trends, impacting purchasing power. Our focus includes CPI components such as Food & Beverages, Clothing & Footwear, Medical Care, Transport & Communication, and Recreation & Amusement.

## Objectives
1. Develop time series models to forecast CPI and its major components.
2. Construct regression models for CPI to understand component impact on overall CPI.
3. Compare forecasts derived from time series and regression analysis to assess model accuracy.

## Tech Stacks

- Python
- R
- Excel
- Time Series Analysis
- Regression Analysis
- Data Cleaning & Preprocessing
- Data Visualization

## Techniques Learnt
- **Data Cleaning and Handling Missing Values**: Cleaning the CPI dataset and handling missing values appropriately.
- **Model Tuning and Hyperparameter Selection**: Tuning models to improve accuracy.
- **Time Series Decomposition**: Breaking down a time series into trend, seasonal, and residual components.
- **ARIMA Modeling for Forecasting**: Building and evaluating ARIMA models for time series forecasting.
- **SARIMA Modeling for Forecasting**: Building and evaluating SARIMA models for time series forecasting.
- **Multiple Regression Analysis**: Building a multiple regression model to predict CPI using various components (e.g., Food, Housing, etc.). This technique involves examining the relationship between CPI and its predictor variables.
- **Scree Plot**: Constructing a scree plot to visualize the variance explained by the principal components and decide the number of components to retain in PCA (Principal Component Analysis).
- **Correlation Plot**: Creating a correlation plot to visually represent the correlation between multiple variables. This helps in identifying relationships between CPI and its components, and the strength of these relationships.
- **Principal Component Analysis (PCA)**: Applying PCA to reduce dimensionality and extract key factors influencing CPI. PCA is a technique used to identify the most important variables (principal components) that explain the variance in the data.
- **PACF (Partial Autocorrelation Function)**: Using PACF to identify the number of lags in time series data that exhibit significant partial autocorrelation. This helps in selecting the appropriate lag value for AR models.
- **ACF (Autocorrelation Function)**: Using ACF to examine the autocorrelation of time series data and to identify patterns, such as seasonality or trends, in the data.
- **Data Visualization in Excel**: Visualizing trends and patterns in the CPI data using Excel charts.
- **Model Evaluation using AIC, RMSE**: Evaluating model performance with AIC (Akaike Information Criterion) and RMSE (Root Mean Squared Error).


##  Terms

- CPI (Consumer Price Index)
- Inflation Rate
- Forecasting
- Time Series Data
- Regression Coefficients
- Seasonal Adjustments
- Trend Analysis
- Residual Analysis

## Country’s Background

This project is focused on the Consumer Price Index (CPI) of India, which tracks the average price level of a basket of goods and services consumed by households. CPI is a critical economic indicator used to assess inflation. Government and financial institutions use CPI data for policy decisions, and businesses use it for forecasting and planning.

The analysis involves the Indian government’s CPI data and its five components, which include:
- Food and Beverages
- Medical Care
- Clothing and Footwear
- Transport and Communication
- Recreation and Amusement
## Dataset Understanding

The CPI dataset consists of historical monthly data on the Consumer Price Index, spanning several years. Key columns in the dataset include:

- Date (monthly data)
- CPI Value (overall index and component indices)
- Categories (Food, Housing, etc.)

For the analysis, I used the dataset provided by [India's Ministry of Statistics and Programme Implementation](http://www.mospi.gov.in).

## Importing Data

- Data is sourced from publicly available CPI data from India's Ministry of Statistics.
- The dataset was imported into Python using `pandas` for cleaning and processing.
- Used `Excel` for visualizing trends and final report presentation.

## Data Modeling

- **Time Series Modeling**: The primary analysis involved forecasting CPI using ARIMA and SARIMA models.
- **Regression Analysis**: Built a multiple regression model to study the relationship between CPI and its five components, providing insights into the factors affecting CPI.
- **Principal Component Analysis (PCA)**: Applied PCA to reduce dimensionality and identify the most important factors driving CPI.

## Results and Conclusion
This analysis enables better understanding of CPI trends in India, supporting inflation monitoring and decision-making. The project provides accurate forecasts and a comparative analysis of two distinct modeling approaches.

## Forecast Visualizations

- **Total CPI Forecast**:
  ![Total CPI Forecast](https://github.com/Vinayak-pixel/A-CASE-STUDY-ON-CONSUMER-PRICE-INDEX-OF-INDIA/blob/main/Resources/CPIT.png)

- **Food & Beverages Forecast**:
  ![Food & Beverages Forecast](https://github.com/Vinayak-pixel/A-CASE-STUDY-ON-CONSUMER-PRICE-INDEX-OF-INDIA/blob/main/Resources/CPIFB.png)

- **Clothing & Footwear Forecast**:
  ![Clothing & Footwear Forecast](https://github.com/Vinayak-pixel/A-CASE-STUDY-ON-CONSUMER-PRICE-INDEX-OF-INDIA/blob/main/Resources/CPICF.png)

- **Medical Care Forecast**:
  ![Medical Care Forecast](https://github.com/Vinayak-pixel/A-CASE-STUDY-ON-CONSUMER-PRICE-INDEX-OF-INDIA/blob/main/Resources/CPIH.png)

- **Transport & Communication Forecast**:
  ![Transport & Communication Forecast](https://github.com/Vinayak-pixel/A-CASE-STUDY-ON-CONSUMER-PRICE-INDEX-OF-INDIA/blob/main/Resources/CPITC.png)

- **Recreation & Amusement Forecast**:
  ![Recreation & Amusement Forecast](https://github.com/Vinayak-pixel/A-CASE-STUDY-ON-CONSUMER-PRICE-INDEX-OF-INDIA/blob/main/Resources/CPIRA.png)

---

**Note**: The full code and detailed explanations can be found in the project files.

# Project Report

For a comprehensive analysis, methodology, and findings, please refer to the complete project report. [Click here to view the report](https://github.com/Vinayak-pixel/A-CASE-STUDY-ON-CONSUMER-PRICE-INDEX-OF-INDIA/blob/main/Report/FINAL_REPORT.pdf).
