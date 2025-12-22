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

Data cleaning and preparation:  
- Import the Netflix dataset (e.g., `netflix_titles.csv`) and inspect basic structure, shape, and data types.
- Identify and handle missing values (e.g., in `director`, `cast`, `country`) and treat or drop rows where critical fields are missing.
- Remove duplicate records to ensure each `show_id` is unique.
- Convert `date_added` to a proper datetime type and verify `release_year` as numeric.
- Standardize and, if needed, split multi-valued columns such as `listed_in` into usable structures for analysis.

Exploratory data analysis (EDA):  
- Analyze the distribution of **content** types (Movies vs TV Shows) and visualize with bar or pie charts.
- Explore the most common genres by splitting `listed_in` and counting genre frequencies.
- Study how much content is added over time (yearly and monthly) and visualize these trends.
- Identify top contributing countries and visualize the top 10 countries with the highest number of titles.
- Analyze rating distribution (e.g., TV-MA, TV-14, PG-13) and visualize frequency of ratings.

Visualization and insight generation:  
- Create bar charts and line charts to show monthly and yearly release trends for Movies vs TV Shows.
- Build visualizations for top genres of movies and TV shows separately.
- Highlight top directors with the highest number of titles on Netflix.
- Generate a word cloud of movie titles or genres to visually summarize catalog themes.

Feature engineering and next steps (optional/advanced):  
- Create time-based features such as year, month, and day extracted from `date_added`.
- Engineer features like number of genres per title or normalized duration for modeling tasks.
- Prepare the cleaned dataset as a foundation for future ML tasks such as recommendation systems or predicting content trends.
  

[1](https://ppl-ai-file-upload.s3.amazonaws.com/web/direct-files/attachments/94593639/2d8ac3e2-72e1-4c41-af51-a918171051e2/Netflix-Data_-Cleaning-Analysis-and-Visualization_-_-ML-_-FA-_-DA-projects.pdf)
