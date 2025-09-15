# World Happiness Report: a Tableau Dashboard

You can find the dashboard published on my Tableau Public profile: [[Tableau Public Dashboard Link]](https://public.tableau.com/app/profile/gabriele.casarin/viz/WorldHappinessReport_17508864371150/Dashboard1)


### Table of Contents

- [Project Overview](#project-overview)
- [Data Sources](#data-sources)
- [Tools](#tools)
- [Techniques Used](#techniques-used)
- [Data Cleaning and Preparation](#data-cleaning-and-Preparation)
- [Analysis Results ](#analysis-results)
- [Links and Sources](#links-and-sources)


### Project Overview

This project is a Tableau dashboard that visualizes data from the World Happiness Report spanning 2015 to 2019. Its primary goal is to analyze the evolution and disparities of perceived happiness across various geographical regions and countries. This analysis serves as a foundational step to further investigate the impact of key factors such as economy, social support, life expectancy, freedom, absence of corruption, and generosity.


### Data Sources

The World Happiness Report is a survey on the state of global happiness, published annually on the occasion of the International Day of Happiness, which is celebrated on March 20.
It ranks more than 150 countries based on their happiness levels and continues to receive global recognition, as governments, organizations, and civil society use these indicators to inform their policy decisions.

The report is based on happiness scores and rankings derived from data collected by the Gallup World Poll. These scores are based on the answers to the main question about life quality posed in the survey. The Report's dataset includes happiness index data for various countries from 2015 to 2019.

You can find the original dataset, divided year, [[here]](https://github.com/GabryGit/Tableau_Project-World-Happiness-Report/tree/main/Dataset/Raw%20Data)


### Tools

- Excel - Data Cleaning (with Power Query)
- Tableau - Data Visualisation


### Techniques Used

- Tableau Data Modeling
- Filters
- Parameters
- Calculated Fields
- Actions

  
### Data Cleaning and Preparation

The original dataset was cleaned, and two separate datasets were created. The first, titled "World Happiness Report," contains all the features from the report, organized by year. The second, "Countries & Continents," maps each country to its corresponding continent, which enables analysis to be segmented by continent.

After importing into Tableau, the two datasets were connected using data blending.

You find the datasest ready to be imported in Tableau [[here]](https://github.com/GabryGit/Tableau_Project-World-Happiness-Report/tree/main/Dataset/Data%20Cleaned)


### Analysis Results 

The project features a suite of interactive visualizations:

- Interactive Controls: Users can filter the data by geographical region and year.

- Choropleth Map: A color-coded map displays the happiness scores of nations, with detailed tooltips revealing the values of the contributing factors for each country.

- Ranked Table: Below the map, a table highlights the top and bottom 10 countries in terms of happiness.

- Trend Analysis: A bar chart illustrates the happiness score trend over the five-year period, allowing users to identify countries with significant improvements or declines.

- Distribution Analysis: A box plot visualizes the distribution of happiness scores, showing the median, quartiles, and any outliers.

- Categorization: A pie chart categorizes countries into three happiness levels, based on the dataset's median score.

This dashboard offers a clear and intuitive way to explore complex data, providing actionable insights for policymakers and anyone interested in understanding the dynamics of global well-being.


### Links and Sources

[[Tableau Public Dashboard Link]](https://public.tableau.com/app/profile/gabriele.casarin/viz/WorldHappinessReport_17508864371150/Dashboard1)

[[Data Analytics Master-Start2Impact University]](https://www.start2impact.it/master/data-science-analytics/)

