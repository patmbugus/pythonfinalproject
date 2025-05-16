# COVID-19 Global Data Tracker

This notebook analyzes global COVID-19 trends using real-world data. We will clean and process the data, perform exploratory data analysis (EDA), generate insights, and visualize trends across countries and time.

# 1. Import Required Libraries

We will use pandas for data manipulation, matplotlib and seaborn for visualization, and optionally plotly for interactive maps.

## 2. Load and Preview COVID-19 Dataset

Let's load the 'owid-covid-data.csv' file and preview its contents.

# 3. Explore Data Structure and Missing Values

We will inspect the dataset's shape, data types, and count missing values in each column.

## 4. Clean and Prepare Data

We will drop rows with missing critical values (like date or location), convert the 'date' column to datetime, and handle missing numeric values.

## 5. Filter Countries of Interest

Let's focus our analysis on Kenya, USA, and India.

# 6. Convert Date Column and Handle Missing Values

Ensure the 'date' column is in datetime format and handle missing values in key columns for our selected countries.

## 7. Plot Total Cases Over Time

We will visualize the total COVID-19 cases over time for Kenya, USA, and India.

## 8. Plot Total Deaths Over Time

Let's visualize the total deaths over time for the selected countries.

## 8. Plot Total Deaths Over Time

Let's visualize the total deaths over time for the selected countries.

## 10. Calculate and Visualize Death Rate

The death rate is calculated as total_deaths / total_cases. Let's plot this over time.

## 11. Bar Chart: Top Countries by Total Cases

Let's see which countries have the highest total cases as of the latest date in the dataset.

## 12. Visualize Vaccination Progress

We will plot cumulative vaccinations over time for Kenya, USA, and India.

## 13. Compare Percentage of Vaccinated Population

Let's calculate and visualize the percentage of the population vaccinated in each selected country.

## 14. (Optional) Choropleth Map of Cases or Vaccination Rates

We can visualize global case density or vaccination rates using a choropleth map.

 Insights & Summary

- The USA has consistently reported the highest total cases and deaths among the selected countries.
- India experienced significant surges in cases during mid-2021.
- Kenya's case and death counts are much lower, but vaccination rollout has been slower compared to the USA and India.
- The death rate has generally declined over time, likely due to improved treatments and vaccination.
- Vaccination progress varies widely across countries, with the USA leading among the three.

*Note: For more detailed insights, further analysis can be performed on age groups, variants, or regional trends.*
