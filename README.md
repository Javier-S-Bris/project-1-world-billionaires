# Introduction

The goal of this project is to gain knowledge about the richest persons in the world. To do this, I'll analyze a dataset that can be found [here](https://www.kaggle.com/datasets/nelgiriyewithana/billionaires-statistics-dataset).

The dataset contains statistics about the world's wealthiest people: where they live, what are their sources of income, how wealthy they are as well as some economic indicators of their countries.

Data has some quality issues related to data types, missing and wrong values and irrelevant columns but overall, the quality is fine and with some cleaning and manipulation, it can be ready for analysis.

# Structure

The project contains two main notebooks:

- **v2_billions_eda** which is included in the main folder. It has the all the code related to Data Cleaning, Data Wrangling and Exploratory Data Analysis (basic, advanced and dashboards)

- **billions_dashboard** included in the *dashboard_code* folder. It uses a .CSV file that contains the cleaned data resulted from data preprocessing in the previous section to generate two dashboards that look at the data using country and industry dimensions to provide additional insights and visual clues into the billionaires' wealth distribution accross the globe.
  The code for the dashboards is also included in the first notebook, this one is just to generate the dasboards right away without preprocessing the data.

# Key insights discovered

## Dimensions

### Geospatial

- Top 5 countries with most billionaires are the United States, China, India, Germany and the UK. Between the first two, they account for nearly half of the total billionaires presented in the dataset.
- Despite having the same population, China has almost three times the number of billionaires than India; result from its economic development in recent decades.
- Wealth distribution is highly concentrated: the Top 5 countries account for ~62% of the total number of billionaires presented in the dataset.
- New York is the city with the highest count of billionaires, followed by Beijing and Hong Kong. Shanghai and London complete the Top 5.
- Looking at continents, Asia hosts the largest number of billionaires, followed by North America and Europe.

### Industry

- Finance & Investments is the industry that produces the most billionaires, followed by Manufacturing and Technology.
- Fashion & Retail and Food & Beverage completes the Top 5. All combined, they account for ~56% of the billionaires presented in the dataset.
- In the Top 5, the first three industries have more than 300 billionaires each, and the bottom two, more than 200.
- As geospatial, industry wealth distribution is highly concentrated.

### Age & Gender

- Most common age for billionaires is 59 years old. This is also the only value that appears more than 100 times.
- Other common values are 60, 58, 65 and 57 years old.
- Age wealth distribution is more even than spatial and industry distributions.
- ~87% of billionaires are male, and ~12% are female. Of the countries in the Top 5, Germany has the most equal distribution and India the less equal.
- The UK has the lowest number of male and female billionaires of the Top 5 countries in absolute terms, whereas the US has the highest.

### Wealth size

- US billionaires have the highest median wealth of countries in the Top 5 with $2,900 billions.
- The UK has the highest value for the third quartile followed by the US. This suggests a significant range of billionaire wealth in the higher end for these countries as well as potential outliers.
- China and India have similar distributions, with China's being slightly more unequal.
- Despite having a similar median wealth, Germany's distribution is much more concentrated around the mean than UK's. This suggests the presence of fewer individuals with extreme wealth and less outliers.

### Density

Billionaire density is defined as the frequency of being a billionaire in a country.

- Of the Top 5 countries, the highest density is located in the US, reflecting a more conductive environment for wealth creation and economic opportunities.
- Despite its economic growth, China has a lower billionaire density in comparison with advanced economies. This is not only because of its relatively recent development but of how populous the country is as well.
- India has the lowest density. This reflects an economy that has a lot of potential and has only beginning to growth in a consistent way in recent years.
