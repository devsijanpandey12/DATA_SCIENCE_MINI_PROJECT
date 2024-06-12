# DATA_SCIENCE_MINI_PROJECT

## 1. Project Overview(Analysis of NEPSE)
)
This project focuses on the analysis of the Nepal Stock Exchange (NEPSE) using a dataset obtained from the Nepal Rastra Bank website. The analysis includes the sectoral performance and market capitalization trends of NEPSE.

### Team Members
- Nishan Dahal (Roll No: 05)
- Tishya Dhakal (Roll No: 07)
- Ashim Shrestha (Roll No: 22)
- Sijan Pandey (Roll No: 11)

## 2. Dataset Overview
- **Source:** Nepal Rastra Bank website
- **Timeframe:** Begins from July 17, 2003
- **Content:**
  - Daily NEPSE index values
  - Market Capitalization (in million rupees) for various sectors

### Dataset Structure
- **Date/Month:** The date of the recorded index values
- **Sector Indices:** Values for different sectors:
  - Commercial Bank
  - Development Bank
  - Finance
  - Micro Finance
  - Hotel
  - Hydro
  - Manufacturing & Processing
  - Trading
  - Life Insurance
  - Non-Life Insurance
  - Mutual Fund
  - Investment and Others
- **NEPSE Indices:**
  - Sensitive Float
  - Sensitive Index
  - Overall NEPSE Index

### Data Preprocessing
- **Handling Missing Values:**
  - Due to the lack of digitization in the early years, many NULL values were present.
  - Solution: Replaced NULL values with 0s to signify unavailability of data.
- **Normalization:**
  - Data was normalized to ensure accuracy and comparability across different time periods and sectors.
- **Outlier Detection:**
  - Applied Z-score standardization to detect and handle outliers.

## 3. Objectives
- Analyze Nepal's stock market (NEPSE index & market capitalization)
- Collect data from reliable sources
- Preprocess data: handle missing values & inconsistencies, normalize for accuracy
- Visualize data with charts and graphs to find trends
- Provide insights to help investors and analysts make informed decisions
- Identify unusual patterns or outliers in NEPSE data to uncover significant market events

## 4. Key Questions
- How has the NEPSE index changed over time?
- What is the correlation between the NEPSE index and market capitalization?
- How sensitive are the NEPSE indices to external factors like inflation, interest rates, and exchange rates?
- Based on historical performance, which sectors should investors focus on for long-term growth?

## 5. Exploratory Data Analysis (EDA)
- Summarizes main characteristics of the dataset using visual methods
- Helps in understanding underlying patterns, spotting anomalies, and formulating hypotheses

## Visualizations Used
- **Line Charts:**
  - Growth of the NEPSE Index
  - Market Capitalization over time
  - NEPSE Indices of popular fields
- **Bar Charts:**
  - Market Capitalization by different sectors
  - NEPSE Indices by different sectors
- **Pie Charts:**
  - Distribution of Market Capitalization across sectors
  - Distribution of NEPSE Indices across sectors
- **Histograms:**
  - Distribution of NEPSE Index values
  - Distribution of Market Capitalization values
- **Box Plots:**
  - Analysis of NEPSE Index values by sector
  - Analysis of Market Capitalization by sector
- **Scatter Plots:**
  - Correlation between NEPSE Index and Market Capitalization
- **Heatmaps:**
  - Correlation matrix of different NEPSE Indices

###  Notable Findings
- **Growth of the NEPSE Index**
- **Market Capitalization Trends**
- **Sectoral Performance**
- **Anomaly Detection** (using Z-score method)

## 6. Anomaly Detection
- **Objective:** Identify unusual patterns or outliers in the dataset
- **Method:** Z-score standardization
- **Findings:** Significant anomalies detected in sectors like Hotel, Trading, and Investment

## 7. Challenges
- Dealing with NULL values due to lack of digitization in early years
- Solution: Replace NULL values with 0s to signify unavailability of data

## 8. Summary of Findings
- Highest Market Capitalization: Commercial Bank
- Lowest Market Capitalization: Trading
- Highest NEPSE Index: Life Insurance
- Most Volatile NEPSE Index: Commercial Bank
- Least Volatile NEPSE Index: Mutual Fund
- Industry with the most growth: Hydropower and Mutual Fund

## 9. Conclusion
The project successfully analyzed NEPSE indices and market trends, providing insights for investors and analysts. Significant anomalies and sectoral performance trends were identified, helping in making informed investment decisions.

## How to Run the Code

### Prerequisites
- Python 3.x
- Jupyter Notebook

### Required Libraries
```python
import pandas as pd
import numpy as np
import matplotlib.pyplot as plt
import seaborn as sns
```

# OUR POWERPOINT PRESENTATION(MINI PROJECT)

[![YouTube](https://t3.ftcdn.net/jpg/03/00/38/90/360_F_300389025_b5hgHpjDprTySl8loTqJRMipySb1rO0I.jpg)](https://youtu.be/sJ5HEnQy-NU)

## Click the image to watch the video on YouTube or [click this link](https://youtu.be/sJ5HEnQy-NU)


---

**NOTE**

All team members contributed equally to the project. Each member worked on different parts of the analysis and preprocessing. Finally, all the work was combined and pushed through one person to GitHub.






---







