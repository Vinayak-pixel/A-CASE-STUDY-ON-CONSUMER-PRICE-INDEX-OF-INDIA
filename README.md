# Time Series and Regression Analysis of the Consumer Price Index (CPI) in India

## Introduction
This project analyzes the Consumer Price Index (CPI) of India, a crucial economic indicator reflecting the average change in prices paid by consumers for a basket of goods and services over time. CPI provides insights into inflation trends, impacting purchasing power. Our focus includes CPI components such as Food & Beverages, Clothing & Footwear, Medical Care, Transport & Communication, and Recreation & Amusement.

## Objectives
1. Develop time series models to forecast CPI and its major components.
2. Construct regression models for CPI to understand component impact on overall CPI.
3. Compare forecasts derived from time series and regression analysis to assess model accuracy.

## Methodology
### 1. Time Series Analysis
   - Time series techniques like ARIMA were applied to model and forecast the CPI and individual components.
   - Key goals included analyzing trends, seasonality, and making accurate predictions.

### 2. Regression Analysis
   - Multiple Linear Regression (MLR) was used to quantify the impact of CPI components on the overall CPI.
   - Regression coefficients provide insights into the influence of each component on inflation.

### Data Source and Description
- **Source**: CEIC Data
- **Period**: January 2011 - January 2024
- The dataset consists of CPI data and its five components, calculated using Laspeyres’s price index with 2012 as the base year.

### Tools Used
- **Programming Language**: Python
- Libraries for statistical analysis, data visualization, and model evaluation were utilized.

## Results and Conclusion
This analysis enables better understanding of CPI trends in India, supporting inflation monitoring and decision-making. The project provides accurate forecasts and a comparative analysis of two distinct modeling approaches.

## Forecast Visualizations

- **Total CPI Forecast**:
  ![Total CPI Forecast](./images/total_cpi_forecast.png)

- **Food & Beverages Forecast**:
  ![Food & Beverages Forecast](./images/food_and_beverages_forecast.png)

- **Clothing & Footwear Forecast**:
  ![Clothing & Footwear Forecast](./images/clothing_and_footwear_forecast.png)

- **Medical Care Forecast**:
  ![Medical Care Forecast](./images/medical_care_forecast.png)

- **Transport & Communication Forecast**:
  ![Transport & Communication Forecast](./images/transport_and_communication_forecast.png)

- **Recreation & Amusement Forecast**:
  ![Recreation & Amusement Forecast](./images/recreation_and_amusement_forecast.png)

---

**Note**: The full code and detailed explanations can be found in the project files.
