# Netflix Data Analysis

## Project Overview

This project analyzes Netflix's content dataset to uncover insights about content distribution, ratings, duration, and trends over time.

The goal is to understand how Netflix structures its content and what patterns exist in movies and TV shows.

---

## Dataset

* Dataset: Netflix Titles Dataset
* Contains information about:

  * Type (Movie / TV Show)
  * Release Year
  * Rating
  * Duration
  * Country

---

## Tools & Technologies

* Python
* Pandas
* Matplotlib

---

## Data Cleaning

* Removed missing values from important columns:

  * type
  * release_year
  * rating
  * country
  * duration
* Converted movie duration from string to numerical format

---

## Analysis Performed

* Distribution of Movies vs TV Shows
* Content rating distribution
* Movie duration analysis
* Release year trends
* Top 10 countries by content production

---

## Key Insights

1. Movies dominate Netflix content, accounting for approximately 70% of total content, while TV Shows make up around 30%.

2. TV-MA and TV-14 are the most common ratings, together contributing over 60% of content, indicating a strong focus on mature audiences.

3. Most movies fall within the 80–120 minute range, with a peak around 90–100 minutes, reflecting a standard runtime pattern.

4. Content production increased significantly after 2015, highlighting Netflix’s rapid expansion.

5. The United States is the leading content producer, contributing the highest number of titles.

---

## Visualizations

The project includes the following visualizations:

* Movies vs TV Shows Bar Chart
* Content Rating Pie Chart
* Movie Duration Histogram
* Release Year Scatter Plot
* Top 10 Countries Bar Chart
* Content Trend Line Plot

(All images are saved in the `images/` folder)

---

##  Conclusion

This analysis shows that Netflix focuses heavily on movies and mature audience content, with rapid growth in recent years. The platform's expansion is reflected in increased content production after 2015.

---

## Project Structure

```
Netflix_analysis/
│
├── data/
├── images/
├── notebook.ipynb
├── README.md
```

---

##  Author

Tuba Hasnat
