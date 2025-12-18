# Project 4: Retail Sales Data Cleaning Project
## Project Description
- This project involves cleaning a retail sales transactions dataset containing date parsing issues, extreme outliers in sales and quantity, missing values, and inconsistent store and item identifiers. The goal is to produce a reliable dataset suitable for time-series analysis, demand forecasting, and business reporting.

## Sample Dataset
- <a href="https://github.com/kvkoushik875/Data-cleaning-projects_Intermediate_level/blob/main/train.csv">Retail Sales</a>

## Data Challenges Addressed
- Mixed and invalid date formats in transaction timestamps
- Extreme outliers in sales amount and item quantity
- Missing values in sales and quantity fields
- Inconsistent store IDs and item IDs
- Duplicate sales transactions

## Key Cleaning Techniques Applied
- Parsed and standardized date columns using pd.to_datetime()
- Detected and filtered outliers using logical thresholds and statistical rules
- Handled missing values using median and mode imputation
- Standardized categorical identifiers (store/item IDs)
- Removed duplicate transaction records
- Performed data validation using assertions


## Outcome
- A clean, consistent retail sales dataset ready for trend analysis, sales forecasting, and performance analytics.
- <a href="https://github.com/kvkoushik875/Data-cleaning-projects_Intermediate_level/blob/main/cleaned_retail_sales_data.csv">Cleaned Retail Sales</a>

# Project 5: Spotify Streaming History Data Cleaning Project

## Project Description
- This project focuses on cleaning Spotify streaming history data containing timestamp errors, missing track identifiers, inconsistent artist names, and duplicate listening records. The objective is to prepare user listening data for behavioral analysis and recommendation-based insights.

## Sample Dataset
- <a href="https://github.com/kvkoushik875/Data-cleaning-projects_Intermediate_level/blob/main/spotify_data_dictionary.csv">Spotify_data_dictionary</a>
- <a href="https://github.com/kvkoushik875/Data-cleaning-projects_Intermediate_level/blob/main/spotify_history.csv">Spotify_data_history</a>
## Data Challenges Addressed
- Invalid or missing timestamp values
- Missing track IDs
- Inconsistent artist and track name formatting
- Duplicate streaming events
- Mixed text casing and whitespace issues

## Key Cleaning Techniques Applied
- Converted timestamp columns into standardized datetime formats
- Removed records missing critical fields such as artist name and track name
- Normalized artist and track names (lowercase, trimming whitespace)
- Handled missing track IDs using conditional logic
- Removed duplicate listening events
- Applied quality checks to ensure data consistency

## Outcome
- A cleaned and validated Spotify streaming dataset suitable for listening behavior analysis, trend detection, and recommendation system development.
-<a href="https://github.com/kvkoushik875/Data-cleaning-projects_Intermediate_level/blob/main/cleaned_spotify_streaming_history.csv">Cleaned_Spotify_Streaming</a>
