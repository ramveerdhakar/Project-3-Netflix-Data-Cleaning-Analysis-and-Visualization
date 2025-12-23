## Netflix Data Cleaning, Analysis and Visualization

This project uses a cleaned Netflix titles dataset containing information about movies and TV shows available on Netflix from around 2008 to 2021, with original content years ranging from 1925 to 2021.  The dataset is designed to practice **data** cleaning, exploratory analysis, and visualization using tools like Python, SQL, and dashboarding tools.

### Dataset Description

- **Domain**: Streaming content analytics (Netflix catalog).
- **Size**: Approximately 8,790 rows and 10 columns.
- **Scope**: Titles available on Netflix with metadata about type, date added, country, rating, duration, and genres.

Main columns:  
- `show_id`: Unique identifier for each title.
- `type`: Movie or TV Show.
- `title`: Name of the content.
- `director`: Director of the title.
- `country`: Country or countries of production.
- `date_added`: Date when the title was added to Netflix.
- `release_year`: Original release year of the title.
- `rating`: Maturity rating (e.g., TV-MA, TV-14, PG-13).
- `duration`: Duration (minutes for movies or seasons for TV shows).
- `listed_in`: Genre(s) / categories (comma-separated).

The dataset is already cleaned to a large extent (duplicates treated and nulls handled) but can still be further processed for deeper analysis and ML use cases.

***

## Problem Statement

Streaming platforms like Netflix must understand their content library composition and viewer offerings to optimize catalog strategy, regional content mix, and content acquisition decisions.  This dataset provides historical information about titles on Netflix, including type, genres, country of origin, release year, and when they were added to the platform.

Using this data, the problem is to analyze how Netflix’s catalog has evolved over time (by type, genre, country, and rating), identify patterns such as dominant genres or key content-producing countries, and prepare the data for potential machine learning applications like recommendations and trend prediction.  The project focuses on robust data cleaning, exploratory analysis, and insightful visualizations that help understand Netflix’s content strategy and catalog trends.

***

## Project Tasks

- Data cleaning and preparation.
- Exploratory data analysis (EDA).
- Visualization and insight generation.
- Feature engineering and next steps (optional/advanced)
