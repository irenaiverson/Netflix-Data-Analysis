# Netflix Data Analysis in Tableau

## Project Overview

This Tableau dashboard provides an interactive analysis of Netflix's content library, offering insights into the distribution of movies and TV shows, genre popularity, content ratings, and trends over time. Users can dynamically filter the data to explore specific titles, content types, and country distributions.

## Link to Tableau Dashboard

Explore the interactive visualization here: https://public.tableau.com/app/profile/irena.iverson/viz/NetflixDataAnalysis_17418238822870/Netflix

## Dataset & Data Fields

This analysis is based on Netflix's catalog data, containing key attributes for Movies and TV Shows. The dataset includes:

- show_id – Unique identifier for each title.

- type – Indicates whether the content is a Movie or TV Show.

- title – Name of the movie or TV show.

- director – Name(s) of the director(s) of the title.

- cast – List of actors featured in the content.

- country – Country where the title was produced.

- date_added – Date when the title was added to Netflix.

- release_year – Year the movie/TV show was released.

- rating – Content rating (e.g., TV-MA, PG-13, TV-Y7).

- duration – Length of the movie or number of seasons for TV shows.

- listed_in – Categories/genres of the content.

- description – Brief synopsis of the movie or TV show.

## Key Features of the Dashboard

- Movie vs. TV Show Toggle: Users can filter between Movies and TV Shows to analyze content distribution.

- Title-Level Insights: Selecting a specific title reveals its details, including cast, director, genre, and description.

- Country-Based Content Distribution: A heatmap visualizes the number of titles available by country.

- Genre Popularity: Identifies the most common genres on Netflix.

- Ratings Distribution: Displays the breakdown of content ratings (e.g., TV-MA, PG-13, TV-Y7).

- Content Trends Over Time: Shows how Netflix's catalog has evolved, highlighting the growth in content over the years.

## Visualizations Used in the Dashboard

- Filled  Map - Total Movies & TV Shows by Country

Represents the number of titles per country, with darker shades indicating a higher count.

- Bar Chart - Top 10 Genres

Displays the most frequent genres.

Documentaries are the most common genre, followed by Stand-Up Comedy and Dramas.

- Bar Chart - Ratings Distribution

Shows the count of titles by rating (e.g., TV-MA, TV-14, TV-PG, PG-13).

TV-MA (Mature Audience) is the most prevalent rating.

- Bubble Chart - Movies vs. TV Shows Distribution

A proportional chart illustrating the ratio of Movies (68.42%) to TV Shows (31.58%).

- Area Chart - Total Movies & TV Shows by Year

Depicts the increasing trend in Netflix's content library.

Significant growth post-2015, peaking around 2018-2019.

## Insights & Findings

- Movies dominate Netflix's catalog (4,265 movies vs. 1,969 TV shows).

- Documentaries are the most popular genre, followed by Stand-Up Comedy and Dramas.

- TV-MA and TV-14 are the most common content ratings, catering to mature audiences.

- Content additions surged after 2015, with a peak in 2018-2019.

- Global distribution of content, with the United States having the highest number of titles.

- Technical Highlights

- Data Cleaning & Preparation: The dataset was cleaned and structured before importing into Tableau.

- Interactive Features: Used filters, parameters, and dynamic title selection for enhanced interactivity.

- Drill-Through Insights: Clicking on a title reveals additional metadata and descriptions.

- Color Encoding & Visual Hierarchy: Ensures clear differentiation of categories and trends.

TABLEAU SCREENSHOT
  <img width="1426" alt="Picture 2025-03-14 at 1 49 48 PM" src="https://github.com/user-attachments/assets/dda3e4f7-3f05-465c-8088-78437cd661e0" />
