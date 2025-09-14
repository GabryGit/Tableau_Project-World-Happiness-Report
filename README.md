# Tableau Project: World Happiness Report
!!!!!!!!!!!!!!!!!!!!!!!!!!!!
### Table of Contents

- [Project Overview](#project-overview)
- [Data Sources](#data-sources)
- [Tools](#tools)
- [Techniques Used](#techniques-used)
- [Data Cleaning and Preparation](#data-cleaning-and-Preparation)
- [Exploratory Data Analysis](#exploratory-data-analysis)
- [Analysis Results ](#analysis-results)
- [Limitations](#limitations)
- [Links and Sources](#links-and-sources)



### Project Overview

Leveraging various datasets —including the primary Global Country Information Dataset (2023), Global Data on Sustainable Energy, and the Global Missing Migrants Dataset— we will analyze key indicators across countries.  The main goal is to identify meaningful insights and trends related to economic, demographic, and environmental factors.
The findings will support non-profit organization's mission by providing data-driven evidence to inform policy recommendations and raise public awareness about critical development challenges worldwide.

![Q6-Chart](https://github.com/GabryGit/SQL-Project-Global-sustainable-development/blob/main/Charts/Q6.png)



### Data Sources

To analyze and compare countries on key topics like economy, population, and CO₂ emissions, I got access to several datasets.
- The main dataset is the 'Global Country Information Dataset', which contains 2023 data on economic, demographic, and environmental indicators.
- 'Global Data on Sustainable Energy': This dataset provides a deeper look into how various countries have progressed on sustainable energy.
- 'Global Missing Migrants Dataset': This dataset offers data on missing migrants globally.



### Tools

- Excel - Data Cleaning
- PostgreSQL - Data Analysis



### Techniques Used

- CTE (Common Table Expression)
- Subqueries
- Views
- Window Functions (aggregate/ranking window functions)
- Joins


  
### Data Cleaning and Preparation

In the initial data preparation phase, we performed Data cleaning and formatting with Power Query in Microsoft Excel - before importing it in PostgreSQL.
You can find cleaned datasets [[here]](https://github.com/GabryGit/SQL-Project-Global-sustainable-development/tree/main/Clean_datasets).



### Exploratory Data Analysis

EDA involved exploring the data to answer key questions, such as:

- Q1. "What are the top 10 countries that emitted the highest percentage of global CO₂ in 2023?"
- Q2. "Is there a correlation between CO₂ emissions and the amount of agricultural land in a country?"
- Q3. "Assessment of the impact of fossil fuel energy and clean energy (nuclear and renewables) on CO₂ emissions, averaged over the last 10 years."
- ...
- Q7. "Comparison between average GDP growth and average energy consumption per capita growth from 2000 to 2020."
- ...
- Q10. "Comparison of population aging between developed and developing countries."
- ...
- Q12. "Correlation between a country's economy and its healthcare situation."
- ...
- Q13.2 "Number of victims and missing migrants per year, divided by category."
- ...
  


### Analysis Results 

The answers to the various analysis questions are within the [[SQL script]](https://github.com/GabryGit/SQL-Project-Global-sustainable-development/blob/main/SQL_Project-Global_Sustainable_Developement.sql), at the end of each query used to extract the necessary data. The resulting charts/tables from the various queries are also stored in this [[folder]](https://github.com/GabryGit/SQL-Project-Global-sustainable-development/tree/main/Charts). 

![Q5-Chart](https://github.com/GabryGit/SQL-Project-Global-sustainable-development/blob/main/Charts/Q5.png)
![Q13.2-Chart](https://github.com/GabryGit/SQL-Project-Global-sustainable-development/blob/main/Charts/Q13.2.png)

### Limitations

Missing values spotted on 'Global Data on Sustainable Energy' dataset to be cleaned.



### Links and Sources
[SQL script](https://github.com/GabryGit/SQL-Project-Global-sustainable-development/blob/main/SQL_Project-Global_Sustainable_Developement.sql)

[[Data Analytics Master-Start2Impact University]](https://www.start2impact.it/master/data-science-analytics/)

