# Netflix Data Analysis Report

## Introduction

This project explores Netflix's catalog to uncover trends in content type, genres, countries of production, and movie durations. The analysis uses a cleaned dataset and visualizes key insights.

## Data Cleaning

- Replaced missing values in `director`, `cast`, and `country` columns with `'Unknown'`.
- Converted the `date_added` column to datetime format.
- Extracted numeric values from the `duration` column for movies as `duration_minutes`.

## Analysis & Visualizations

### 1. Content Type Distribution

- **Bar plot**: Shows the count of Movies vs TV Shows.
- **Pie chart**: Visualizes the proportion of each content type, with percentages on the chart and labels in a legend for clarity.

### 2. Content Addition Trends

- **Line plot**: Displays how many titles were added each year, separated by content type.
- Reveals growth patterns and peak years for new content.

### 3. Top Countries by Content Production

- **Bar plot**: Top 10 countries producing Netflix content.
- Shows the global diversity of Netflix's catalog.

### 4. Genre Distribution

- **Bar plot**: Top 10 genres.
- Highlights the most popular genres on Netflix.

### 5. Movie Duration Analysis

- **Histogram** and **boxplot**: Show the distribution of movie durations.
- Most movies are between 80 and 120 minutes.

## Key Insights

- Movies are more prevalent than TV Shows in the dataset.
- The number of titles added to Netflix has increased over time, with some fluctuations.
- The United States and India are among the top content-producing countries.
- Drama, Comedy, and Documentary are the most common genres.
- Movie durations mostly fall within the standard feature-length range.

## Conclusion

This analysis provides a comprehensive overview of Netflix's content library, revealing trends in content type, genre, country, and duration. The visualizations make it easy to understand