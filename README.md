![Netflix Logo](logo.png)


# Netflix_SQL_Project
SQL project analyzing Netflix dataset — 15 business queries

# Netflix Movies and TV Shows Data Analysis using SQL

## Overview
This project analyzes Netflix's movies and TV shows data using SQL to extract actionable insights. The focus is on understanding content distribution, ratings, genres, release trends, and patterns in Indian content. This project demonstrates practical SQL skills applied to real-world data.

---

## Objectives
- Compare the number of Movies vs TV Shows  
- Identify the most common ratings for content types  
- Analyze content by release year, country, and duration  
- Explore genre distribution and categorize content based on keywords  
- Identify top actors and directors in Indian content  

---

## Dataset
The dataset is sourced from Kaggle:  
[Netflix Movies Dataset](https://www.kaggle.com/datasets/shivamb/netflix-shows)  

---

## Schema
```sql
CREATE TABLE netflix
(
    show_id      VARCHAR(5),
    type         VARCHAR(10),
    title        VARCHAR(250),
    director     VARCHAR(550),
    casts        VARCHAR(1050),
    country      VARCHAR(550),
    date_added   VARCHAR(55),
    release_year INT,
    rating       VARCHAR(15),
    duration     VARCHAR(15),
    listed_in    VARCHAR(250),
    description  VARCHAR(550)
);

----
## Key Analyses

- **Movies vs TV Shows:** Count distribution of content types.  
- **Most Common Ratings:** Identify the top rating for movies and TV shows.  
- **Content by Year:** List movies released in a specific year (e.g., 2020).  
- **Top Countries:** Identify top 5 countries with the most content.  
- **Longest Movie:** Find the movie with the highest duration.  
- **Recent Additions:** Content added in the last 5 years.  
- **Director Analysis:** List all content by a specific director (e.g., Rajiv Chilaka).  
- **TV Shows with >5 Seasons:** Identify long-running shows.  
- **Genre Distribution:** Count content items in each genre.  
- **India Content Trends:** Average content releases by year in India.  
- **Documentaries:** List all movies classified as documentaries.  
- **Content Without Directors:** Identify items missing director information.  
- **Actor Analysis:** Movies featuring 'Salman Khan' in the last 10 years.  
- **Top Actors in India:** Actors with the most appearances in Indian content.  
- **Content Categorization:** Label content as 'Good' or 'Bad' based on keywords like 'kill' or 'violence'.  

---

## Findings

- **Content Diversity:** Netflix offers a wide variety of movies and TV shows with varying ratings and genres.  
- **Regional Insights:** India produces significant content, with trends in release years and popular actors.  
- **Content Categorization:** Helps understand the nature of content, identifying items that may be violent or intense.  

---

## Author

**Prasad Nikam – Aspiring Data Scientist**  
This project demonstrates SQL and data analysis skills as part of my portfolio for aspiring data science roles.

---

## Connect

-## Connect

- **LinkedIn:** [Prasad Nikam](https://www.linkedin.com/in/prasad-nikam-a968a3290/)  
- **Instagram:** [Prasad Nikam](https://www.instagram.com/prasad_nikam__96k/)


