# Amazon Prime TV Shows and Movies - EDA

## Project Overview

This project is an Exploratory Data Analysis (EDA) of the Amazon Prime Video content library available in the United States.

The objective of this project is to analyze movies and TV shows available on Amazon Prime and identify useful patterns related to content type, genres, release years, ratings, popularity, production countries, and cast and directors.

The analysis uses Python and popular data analysis and visualization libraries to explore the dataset and generate meaningful business insights.

---

## Business Context

The streaming industry has become highly competitive, with platforms continuously expanding their content libraries to attract and retain viewers.

Amazon Prime Video has a large collection of movies and TV shows from different genres, countries, and time periods. Analyzing this content can help understand how the catalog is structured and identify patterns in ratings, popularity, content categories, and regional representation.

This project uses Exploratory Data Analysis to extract such insights from the available Amazon Prime dataset.

---

## Problem Statement

The dataset contains information about thousands of movies and TV shows available on Amazon Prime Video.

The main questions explored in this project are:

- What type of content dominates the Amazon Prime catalog?
- Which genres are most commonly available?
- How has the content library changed over the years?
- How are IMDb and TMDB ratings distributed?
- Which titles have the highest IMDb votes and TMDB popularity?
- How is content distributed across production countries?
- How do Movies and TV Shows differ in terms of runtime and age certification?
- Which actors and directors appear across the largest number of titles?
- What relationships exist between important numerical variables?

---

## Business Objective

The main objective of this project is to analyze the Amazon Prime content catalog and generate data-driven insights that can help stakeholders understand:

- Content diversity
- Content type distribution
- Genre distribution
- Release trends
- Rating patterns
- Popularity patterns
- Regional content distribution
- Actor and director representation
- Relationships between different content-related variables

---

## Dataset

The project uses two CSV files:

### 1. titles.csv

This dataset contains information about Amazon Prime titles.

Important columns include:

- `id` - Title ID
- `title` - Name of the title
- `type` - Movie or TV Show
- `description` - Description of the title
- `release_year` - Release year
- `age_certification` - Age certification
- `runtime` - Runtime in minutes
- `genres` - Genres associated with the title
- `production_countries` - Countries involved in production
- `seasons` - Number of seasons for TV Shows
- `imdb_id` - IMDb title ID
- `imdb_score` - IMDb rating
- `imdb_votes` - Number of IMDb votes
- `tmdb_popularity` - TMDB popularity score
- `tmdb_score` - TMDB rating

### 2. credits.csv

This dataset contains information about actors and directors associated with the titles.

Important columns include:

- `person_ID` - Person ID
- `id` - Title ID
- `name` - Actor or director name
- `character_name` - Character played by the actor
- `role` - Actor or Director

---

## Technologies Used

### Programming Language

- Python

### Libraries

- Pandas
- NumPy
- Matplotlib
- Seaborn

### Development Environment

- Google Colab
- Jupyter Notebook

---

## Project Workflow

The project follows a complete Exploratory Data Analysis workflow:

1. Import required libraries
2. Load the datasets
3. Understand the dataset structure
4. Check data types
5. Check missing values
6. Check duplicate records
7. Clean and preprocess the data
8. Perform Univariate Analysis
9. Perform Bivariate Analysis
10. Perform Multivariate Analysis
11. Create meaningful visualizations
12. Extract insights from the analysis
13. Connect findings with business objectives
14. Present the final conclusion

---

## Exploratory Data Analysis

The project contains 22 meaningful visualizations covering different types of analysis.

### Univariate Analysis

- Movie vs TV Show distribution
- Content release trends
- Age certification distribution
- Runtime distribution
- IMDb score distribution
- TMDB score distribution
- IMDb vote analysis
- TMDB popularity analysis
- Genre distribution

### Bivariate Analysis

- Movies and TV Shows over the years
- IMDb score by content type
- Top genres by content type
- IMDb score vs TMDB score
- Average runtime by content type
- Production country analysis
- Age certification by content type
- Actor analysis
- Director analysis

### Multivariate Analysis

- Correlation Heatmap
- Pair Plot

---

## Key Findings

Some important observations from the analysis include:

- Movies form the majority of the Amazon Prime titles in the dataset.
- Drama is one of the most frequently represented genres, followed by Comedy and Thriller.
- A large proportion of the catalog consists of content released in recent years.
- Movies have a considerably higher average runtime than TV Show episodes.
- IMDb and TMDB scores show a moderate positive relationship.
- Content popularity and IMDb votes are highly uneven across titles, with a relatively small number of titles receiving very high values.
- The dataset contains titles from multiple production countries, although the distribution is not equal.
- Movies and TV Shows show different patterns in age certification.
- Some actors and directors have appeared across a large number of titles.
- Several columns contain missing values, which should be considered when interpreting the results.

---

## Business Insights

The analysis can help stakeholders understand the overall structure and diversity of the Amazon Prime content catalog.

The findings can be used as a starting point for:

- Understanding content mix
- Studying genre representation
- Comparing Movies and TV Shows
- Exploring regional content distribution
- Understanding rating patterns
- Identifying highly popular titles
- Studying frequently represented actors and directors
- Supporting future content and audience analysis

The analysis does not directly measure revenue, subscriptions, or viewer engagement because those business metrics are not included in the dataset.

---

## Project Structure

```text
Amazon-Prime-EDA-Project/
│
├── Amazon_Prime_EDA_AJAY_KUMAR.ipynb (THIS IS THE MAIN FILE YOU HAVE TO RUN)
│
├── titles.csv
├── credits.csv
│
└── README.md
```

---

## How to Run the Project

### Option 1: Google Colab

Open the notebook in Google Colab and run the cells from top to bottom.

### Option 2: Jupyter Notebook

Clone or download the repository and open:

```text
Amazon_Prime_EDA.ipynb
```

Install the required libraries if necessary:

```bash
pip install pandas numpy matplotlib seaborn
```

Then run the notebook from beginning to end.

---

## Project Type

**Exploratory Data Analysis (EDA)**

---

## Conclusion

This project provides an overall understanding of the Amazon Prime Video content catalog through Exploratory Data Analysis.

By analyzing content types, genres, release years, ratings, popularity, production countries, actors, and directors, the project identifies useful patterns within the available data.

The analysis demonstrates how Python-based data analysis and visualization can transform a large content dataset into meaningful information that can support further business and content strategy analysis.

---

## Author

**Ajay Kumar**

B.Tech - Computer Science and Engineering

Interested in Data Analytics, Data Science, and Artificial Intelligence.

---

## Repository

This repository contains the complete EDA notebook and datasets used for the project.

**GitHub:** https://github.com/ajaykumar81536/Amazon-Prime-EDA-Project

**Google Colab:** https://drive.google.com/file/d/1a_UzntGfpDtZUmlj1EAYWN-hWZEJfRxn/view?usp=sharing
```
