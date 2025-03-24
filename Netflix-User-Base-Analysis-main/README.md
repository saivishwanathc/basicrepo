# Netflix-User-Base-Analysis

## Project Summary
This repository contains an initial data and exploratory analysis of Netflix's revenue data, focusing on understanding how different subscription types, user behaviors, and account preferences impact revenue generation. As an analyst for Netflix, the objective is to derive insights that will inform strategies to enhance user engagement and optimize revenue streams. The analysis explores various factors that drive revenue growth and user retention, aiming to identify key trends and patterns. These insights will help Netflix develop more targeted offerings and improve its pricing strategies, ultimately maximizing revenue while enhancing the user experience.

## Key Questions
- Which Regions bring the most revenue?
- Which Countries in the highest performing regions bring the most revenue?
- What are the differences in membership costs by region and by country?
- Are there any trends in when (time of year) new users join Netflix?
- How old are the majority of Netflix users?
- How long do users generally continue their Netflix subscription?
- Which subscription type brings the most revenue?
- Are there any relationships between subscription type and user age?
- Are there any relationships between device type and user age?

## Data
- Netflix User Base: The dataset offers a sample of Netflix’s user base, highlighting different aspects of user subscriptions, revenue, account information, and activity. Each row corresponds to a unique user, identified by their User ID. The dataset details include the user's subscription plan (Basic, Standard, or Premium), the monthly revenue associated with their subscription, the date they joined Netflix (Join Date), the date of their most recent payment (Last Payment Date), and their country of residence. Other columns provide insights into customer behaviors and preferences, such as Device Type (e.g., Smart TV, Mobile, Desktop, Tablet).
- World-countries.json: This dataset was used in order to conduct a geospatial analysis.


## Tools
#### The data was analyzed using Python and the following supporting libraries:
- Pandas: for data analysis
- Numpy: for mathematical equations
- Seaborn: for data visualizations
- Matplotlib: for data visualizations
- SciPy: for mathematical equations
#### Data visualization was done using Tableau Public
- View Here: https://public.tableau.com/app/profile/kimberly.mizrahi/viz/NetflixUserBaseAnalysis_17313492202370/Story1

## Folders
The project files are stored in following folder structure:
- 01 Project Management: Project brief
- 02 Data: Contains two subfolders 'Original Data' with original datasets, and 'Prepared Data' with cleaned datasets ready for analysis. (Data files not uploaded to GitHub due to size limitations.)
- 03 Scripts: Jupyter notebooks containing coding for the analysis.
- 04 Analysis: 'Visualizations' subfolder contains the visualizations used for developing and explaining insights.

## Resources & Disclaimer
This dataset does not reflect real Netflix user data, as it was designed by a Kaggle.com user for data exploration purposes. The data has potential for bias and limitations as it was synthesized by a Kaggle.com user for learning purposes. 
ChatGPT was utilized for assistance with writing structure and grammar

#### Kaggle Links:
- https://www.kaggle.com/datasets/arnavsmayan/netflix-userbase-dataset
- https://www.kaggle.com/datasets/ktochylin/world-countries




