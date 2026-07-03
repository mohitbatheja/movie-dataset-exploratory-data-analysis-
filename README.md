# Movie Dataset Exploratory Data Analysis (EDA)

## Project Overview
This project focuses on performing Exploratory Data Analysis (EDA) on a movie dataset to understand its structure, data quality, and hidden patterns. The goal is to clean the data and derive meaningful insights using Python.

---

## Objective
- Understand dataset structure
- Identify and remove duplicate records
- Handle data quality issues
- Analyze movie attributes such as revenue and release year
- Prepare clean dataset for analysis

---

##  Dataset Information

### Columns:
- title
- year
- revenue
- imdb_id
- tmdb_id
- trakt_id

### Dataset Size:
- Initial records: ~1000 rows  
- Unique records after cleaning: **10 movies**

Note: Dataset contained high duplication where identical movie records were repeated multiple times.

## Data Cleaning Process
- Removed duplicate rows using `drop_duplicates()`
- Checked uniqueness using `nunique()`
- Verified consistency across all columns
- Reduced dataset to only unique movie entries

## Key Findings
- Dataset had **extreme duplication**
- Only **10 unique movies** were present
- Identifiers (`imdb_id`, `tmdb_id`, `trakt_id`) were also repeated
- Revenue and year values were identical across duplicates

## Insights
- No meaningful variation in movie titles
- Revenue analysis is not reliable due to duplicate structure
- Year-wise trends cannot be analyzed properly
- Dataset is suitable only for learning data cleaning concepts

## Tools & Technologies
- Python 
- Pandas
- Jupyter Notebook

## Conclusion
This project highlights the importance of data quality in analytics. Although the dataset initially contained ~1000 rows, after cleaning only 10 unique records remained due to heavy duplication.

Key learnings:
- Duplicate detection is critical in real-world datasets
- Data cleaning is more important than data size
- Proper validation of dataset uniqueness is required before analysis

