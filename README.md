# Interactive-Netflix-Insights-Dashboard
This project analyzes a Netflix dataset containing information about titles (movies and series) and cast members, using Power BI with DAX for data transformation, measures, and visualization.

Data Cleaning & Preparation:
Verified and corrected data types.
Standardized values in categorical fields (e.g., replaced "TV Show" with "Series" in the type column).
Split the genres column into a separate Genres table to normalize data and establish a one-to-many relationship with the Titles table.
Connected the Titles and Genres tables via the unique title ID.

Analysis & Measures:
Created DAX measures, including the percentage of movies vs. series.

Built visualizations to answer questions such as:
Total number of titles
Number of movies and series
Percentage of movies
Number of actors and directors
Changes in show duration over the years
Trends in production of movies vs. series
Highest-rated movie and series
Experimented with clustering to explore content grouping.

Dataset Metadata
Titles Table: Contains attributes such as title name, type, release year, age certification, duration, genres, production countries, number of seasons, IMDb score, and IMDb votes.
Cast Table: Contains actor/actress/director names, roles, and characters played.

Tools & Skills Demonstrated:
Power BI for data visualization and dashboard creation.
DAX for creating calculated measures and KPIs.
Data modeling (table relationships, normalization).
Data cleaning & transformation techniques.
