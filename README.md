# Movie Analytics Report & Dashboard

This project analyzes movie data from [The Movie Database (TMDB)
API](https://developer.themoviedb.org/docs/getting-started), combining
**data mining**, **machine learning**, and **visual storytelling**.\
It was developed as part of INFO-6150: Data Mining & Analysis (August
2025) course at Fanshawe College.

## Project Structure

-   `Movie Analytics Report.pdf` → Full report of methods, analysis, and
    findings\
-   `Movies Dashboard.pbix` → Interactive Power BI dashboard for data
    exploration\

## Features

-   **Data Extraction**: Python script pulls movie data (titles, genres,
    votes, popularity, language, release date).\
-   **Data Cleaning & Transformation**: One-hot encoding of genres,
    filtering, numeric transformations.\
-   **Power BI Dashboard**:
    -   Popularity & ratings over time\
    -   Movie releases by language & year\
    -   Genre-specific insights\
-   **Clustering**: Applied k-means to group movies into 3 clusters
    (Blockbusters, Moderate Performers, Underperformers).\
-   **Recommender System**: Content-based filtering with cosine
    similarity to recommend similar movies.\
-   **Data Art**: Genre evolution visualized over 25 years.

## Key Insights

-   **Seasonal Popularity**: Movies released May--July peak in
    popularity.\
-   **Industry Growth**: Annual movie releases are steadily increasing,
    except 2020 (COVID impact).\
-   **Genre Trends**: Action, Drama, and Comedy dominate; Animation popularity is
    rising; Comedy is steady.\
-   **Language Trends**: English dominates, but Japanese
    films also show growth patterns.\
-   **Clusters**:
    -   Cluster 2 → Blockbusters (Action, Animation, Adventure-heavy)\
    -   Cluster 1 → Underperformers (Drama, Romance-heavy)\
    -   Cluster 0 → Moderate Performers (balanced genres).
    

## References

-   [TMDb API
    Docs](https://developer.themoviedb.org/docs/getting-started)\
-   [TMDb Popularity
    Metric](https://developer.themoviedb.org/docs/popularity-and-trending)\
-   [r/DataIsBeautiful -- Movie Genres
    (1894--2025)](https://www.reddit.com/r/dataisbeautiful/comments/8dyqfk/oc_the_prevalence_of_movie_genres_between_1894/)
