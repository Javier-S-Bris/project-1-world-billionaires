Changelog

# version_1

billions_eda_part_1.ipynb file:

- Contained all data pre-processing to create a dataset ready to be analized

billions_eda_part_2.ipynb file:

- Contained EDA Q&A with 10 different questions (not included in the version reviewed in 1to1)

# version_2

Overall changes:

- Fixed typos and grammar spelling errors in comments.
- Eliminated space between comments and code in cells.
- Added comments in cells that didn't have them.
- Changed printed statements related to null values to only show columns with null values in descending order for better readability.

Started on 02-06-2024

- Single file called billions_eda_v2 that unifies billions_eda_part_1 and billions_eda_part_2

## Data dictionary

- Added a link to the data source.

## Part 1. Importing libraries, changing settings to display all columns and loading the dataset.

- No changes in this part.

## Part 2. Data cleaning.

- Minor changes to fix indentation in print statements located in the null values section.

### Dealing with null values section.

- Added explanatory sentences to provide context for the executed code.
- Changed number format to add thousands separator for better readability.
- Standardized columns' names to italics in markdown.
- Changed printed statements related to *organization* and *title* columns to only display some values instead of all.

## Part 3. Dataset structural enhancement.

- Added explanatory sentences to provide context for the executed code.

## Part 4. Data quality improvement.

### Looking for duplicate values in the dataset

- Added explanatory sentences to compare number of rows without duplicates with dataset's size.

### Data types adjustment

- Changed printed statements related to dates to only display some values instead of all.

### Feature engineering

- Replaced code to create *continent* column with a less verbose, more efficient and maintanable version.

### Advanced null values addressing

- Added explanatory sentences to provide context for the executed code.
- Added comments to code cells and outputs for better readability.
- Replaced code to address null values for *life_expectancy_country*, *gdp_country*, *population_country*, *latitude_country* and *longitude_country* with a less verbose, more efficient and maintanable version.
- Added explanatory sentences to provide context for the corresponding outputs.
- Replaced code to calculate and fill null values with continents' median values for tax and education related columns with a less verbose version.
- Added explanatory sentences to provide context for the corresponding outputs.

## Part 5. Creating the definitive dataset to perform EDA.

- No changes in this part.

## Part 6. EDA

### Q&A EDA section (basic exploration).

- Added introductory comments to summary tables in Questions 1-5.
- Changed indexes of summary tables to start from 1 instead of 0.
- Added data values in Question 6

### Advanced EDA

- New whole section.

## Part 7. Dashboard

- New whole section.

