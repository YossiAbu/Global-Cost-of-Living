# Global Cost of Living
Cost of living comparison between different countries around the world

## Problem Statement
The problem we aim to investigate is the disparities in the cost of living among countries and continents. Our goal is to analyze which countries pose challenges for their citizens in maintaining a standard of living and to understand Israel's position relative to the rest of the world. To achieve this, we will utilize data analysis techniques to extract insights from datasets related to the subject and create visualizations to showcase the variations in the cost of living across countries.

## Dataset Information

#### Global Cost of Living
The dataset used for this analysis can be found here. It consists of information about the cost of living in nearly 5000 cities worldwide. The data was sourced from the Numbeo website (Numbeo.com). The dataset comprises two general columns (country, city) and 55 numeric columns representing the cost of living in each city across various categories. Additionally, there is a column (data quality) indicating the reliability of the data. For the purpose of our analysis, we have chosen to ignore the data quality column and utilize the entire dataset, acknowledging that the reliability of some data may vary.

#### Population by Country 2020
This data set is basically one table that contains information about countries such as
names of countries, amount of population, area and more.
The use of this table is significantly smaller than the table describing the cost of
living, since in this table we only used the column describing the amount of the population
of a country and examined the relationship of the amount of people in the country
for the results we got.

## Repository Structure

- `Project.ipynb`: Jupyter Notebook containing the analysis code.
- `datasets/`: Directory containing datasets used for analysis.
  - `global-cost-of-living/`: Directory containing datasets related to the global cost of living.
    - [Dataset files for global cost of living analysis]
  - `population/`: Directory containing datasets related to population statistics.
    - [Dataset files for population analysis]
- `README.md`: Overview of the project, including problem statement and dataset information.
