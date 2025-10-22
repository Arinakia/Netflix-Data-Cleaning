# **Netflix Data Cleaning**

This project demonstrates systematic cleaning and preprocessing of a Netflix dataset using Python in a Jupyter notebook. The notebook covers techniques for handling common real-world data issues and prepares the Netflix data for further analysis or modeling

## **Project Overview**

Loads original Netflix dataset (.csv).

Examines and corrects data types for all columns.

Handles missing values using type-appropriate strategies.

Removes duplicate records.

Cleans and standardizes columns like runtime, votes, and genres.

Fills missing runtimes using the median for each content type (movie or TV show).

Outputs a cleaned dataset ready for further analysis.

## **Features**

Data type corrections (e.g. numeric conversion for runtime, votes)

Duplicate row removal

Null/missing value analysis and imputation

Outlier filtering (e.g. impossible IMDb scores)

Statistical summaries (counts, medians, etc.)

Saves cleaned data to cleannetflixdata.xlsx

## **Libraries Used**

pandas

numpy
