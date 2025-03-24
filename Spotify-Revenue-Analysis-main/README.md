# Spotify Revenue & Forecasting

## Project Overview

This repository contains a comprehensive data analysis and machine learning project focused on predicting Spotify's future revenue. The primary objective is to develop a predictive model that leverages historical data, including revenue, costs, user statistics, and key performance indicators (KPIs), to inform strategic decisions related to pricing, cost management, and marketing investments. By understanding historical trends and building accurate forecasting models, this project aims to support Spotify's financial planning and resource allocation.

The scope of the project includes a detailed descriptive analysis to uncover trends in revenue growth, costs, and user base expansion. Key features such as premium revenue, cost of revenue, monthly active users (MAUs), and advertising revenue will be analyzed and utilized in the predictive modeling process. The model will be evaluated using metrics like Mean Absolute Error (MAE) and Root Mean Squared Error (RMSE) to ensure accuracy. Additionally, scenario analysis will be conducted to forecast revenue under different conditions, providing valuable insights for Spotify's leadership teams.

This project will deliver a machine learning model capable of forecasting Spotify's revenue, alongside actionable visualizations and insights into the company's revenue structure, user engagement, and cost efficiency. These findings will support key stakeholders, including C-suite executives, sales, marketing, and product management teams, in making data-driven decisions to optimize profitability and strategic growth.

Tools and technologies utilized include Python for data processing and modeling, Tableau for visualization, and Scikit-learn for machine learning model development.

## Key Questions
1. Revenue Trends: How has total revenue evolved over time, and what are the
key drivers (premium revenue vs ad revenue)?
3. Cost Analysis: How do the costs of revenue (both total and premium) compare
to revenue trends?
4. Profitability: What is the gross profit margin for both premium and ad-supported
revenue streams, and how has it evolved?
5. User Engagement: What are the trends in Monthly Active Users (MAUs), and
how does user growth correlate with revenue changes?
6. Customer Segmentation: How has Premium Average Revenue Per User
(ARPU) changed over time, and are there noticeable trends in user
monetization?
7. Advertising Performance: How has advertising revenue performed compared
to premium revenue, and are advertising costs proportional to revenue gains?
8. Cost Efficiency: Are sales and marketing efforts yielding higher revenues, and
what is the return on investment?
9. Seasonality or Cyclicality: Are there specific periods where revenue or costs
fluctuate significantly?
10. Premium vs. Ad Model: Which business model (premium vs ad-based) is more
profitable over time, and how should the business balance these two streams?
11. Operational Costs: How do general administrative costs evolve over time, and
are they aligned with revenue growth?

## Data
Source: https://www.kaggle.com/datasets/mauryansshivam/spotify-revenue-expenses-and-its-premium-users

### Variables Descriptions:
Date: The date of each data entry.
Year, Month, Quarter: Temporal information, useful for time series analysis and trends.
Cost of Revenue: The cost associated with generating revenue (e.g., operational costs, royalties).
Gross Profit: Total revenue minus the cost of revenue.
Premium Revenue: Revenue generated from premium subscriptions.
Ad Revenue: Revenue generated from advertising.
Monthly Active Users: Total, Premium, and Ad-Supported Monthly Active Users (MAUs).
Premium ARPU: Average revenue per user (ARPU) for premium subscribers.
Sales, R&D, Admin Costs: Costs incurred in sales and marketing, research and development, and general and administrative functions.

## Tools & Technologies
● Data Cleaning & Processing: Excel, Python (Pandas, Numpy)

● Modeling: Scikit-learn, Time Series Forecasting T ools (e.g., ARIMA)

● Visualization: Tableau, Matplotlib, Seaborn

● Deployment: Jupyter Notebooks, GitHub, PowerPoint for presentation

## Folders
01 Project Management: Project Document

02 Data: Contains two subfolders 'Original Data' with original datasets, and 'Prepared Data' with cleaned datasets ready for analysis. (Data files not uploaded to GitHub due to size limitations.)

03 Scripts: Jupyter notebooks containing coding for the analysis.

04 Analysis: 'Visualizations' subfolder contains the visualizations used for developing and explaining insights.

05 Sent to Client: The project document and final report presented in powerpoint.

## Disclaimer
Note: This dataset does not reflect real Spotify data, as it was designed by a Kaggle.com user for data exploration purposes. The data has potential for bias and limitations as it was synthesized by a Kaggle.com user for learning purposes. ChatGPT was utilized for assistance with writing structure and grammar.
