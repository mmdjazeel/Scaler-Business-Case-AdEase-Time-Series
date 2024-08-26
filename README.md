# Scaler-Business-Case-AdEase-Time-Series

### README for GitHub Repository

**AdEase: Optimizing Digital Advertising with AI**

AdEase is a marketing company focused on maximizing ad clicks at minimal cost. Our platform simplifies digital advertising by combining three AI modules—Design, Dispense, and Decipher—into a seamless, end-to-end solution for businesses.

As part of the Data Science team at AdEase, your task is to analyze page view data from 145,000 Wikipedia pages over 550 days. You'll be forecasting future views to enhance ad placement strategies for clients across different regions and languages.

**Dataset:**

You can access the dataset here: [Dataset Link](https://drive.google.com/drive/folders/1mdgQscjqnCtdg7LGItomyK0abN6lcHBb).

**Data Files:**

1. **train_1.csv:** Rows represent individual articles, columns represent dates, and values are the number of views on each date. The page names include details like language, access type, and origin (e.g., spider or browser).

2. **Exog_Campaign_eng.csv:** Contains data on significant events or campaigns affecting page views for English pages. The presence of a campaign is marked as '1,' and '0' otherwise. This data should be used as an exogenous variable when modeling and forecasting.

**Key Concepts:**

- Exploratory Data Analysis (EDA)
- Time Series Forecasting: ARIMA, SARIMAX, Prophet

This project involves leveraging these techniques to predict and optimize ad placements, ensuring effective and economical advertising for our clients.
