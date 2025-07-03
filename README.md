
# Netflix Titles EDA

This repository contains an Exploratory Data Analysis (EDA) report on Netflix's global catalog of Movies and TV Shows. The goal is to uncover meaningful patterns in content type, genre distribution, release trends, viewer ratings, and geographic availability.

---

## 📁 Dataset Overview

- **Source**: Netflix data scraped from JustWatch.
- **Original Records**: 21,917
- **Final Records after Cleaning**: 21,507
- **Key Columns**:
  - `title`: Name of the show/movie
  - `type`: Type of content (Movie or Show)
  - `genres`: Comma-separated genre list
  - `releaseYear`: Year of release
  - `imdbAverageRating`: IMDb average user rating
  - `imdbNumVotes`: Number of votes on IMDb
  - `availableCountries`: Countries where the title is available

---

## 🧹 Data Cleaning Summary

- Filled missing genres with `'Unknown'`
- Dropped records with missing `releaseYear`
- Converted year and rating columns to proper formats
- Removed duplicates
- Final dataset is well-structured with minimal missing data (excluding `availableCountries`)

---

## 📊 Analysis Sections

### 1. Univariate Analysis
- Distribution of content types (Movies vs Shows)
- Frequency of top genres
- Content release trends over the years
- IMDb rating distribution

### 2. Bivariate & Multivariate Analysis
- Release year vs IMDb rating
- IMDb votes vs rating (log scale)
- Top genres by average IMDb rating
- Content type vs IMDb rating (boxplot)

### 3. Country Availability Analysis
- Top 10 countries by number of available titles
- Note: Over 99% missing data in `availableCountries`, so insights are directional only

---

## 📈 Key Insights

- **Movies** dominate the platform, comprising ~80% of titles
- **Drama** and **Comedy** are the most frequent genres
- Content production peaked between **2017 and 2020**
- **War**, **History**, and **Biography** genres receive the highest ratings
- **IMDb votes** positively correlate with rating stability
- Country data is too sparse to be used for confident geographic strategy

---

## 📎 Artifacts

- `Netflix_EDA_Executive_Report.pptx`: Stakeholder-ready slide deck
- Code scripts for data cleaning and visualization

---

## 🚀 Getting Started

To reproduce this analysis:

```bash
pip install pandas matplotlib
```

Run the notebook or scripts starting from data loading through chart generation.

---

## 📄 License

This project is for educational and analytical purposes only.

##Author 
-Sivakumar Devaraj
- Email : www.sivakumardevaraj@gmail.com
 
-#MLwithZUKO 

