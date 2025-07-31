# Fake-Job-Posting-Data-Cleaning-Project---Python

# Project Overview

This project focuses on cleaning a fake job posting dataset to prepare it for further analysis and fraud detection. The goal was to remove irrelevant and low-quality entries, clean up text data, and ensure the dataset was robust enough for use in NLP or machine learning tasks.

# Key Techniques & Tasks
- Text Cleaning: Removed records with short or duplicate job descriptions to improve text data quality.

- Feature Dropping: Dropped the location column due to inconsistency and lack of value.

- Data Validation: Ensured that job titles and descriptions were meaningful and not duplicates.

# Tools & Libraries
pandas, numpy, BeautifulSoup, requests
- BeautifulSoup & requests were used to clean and standardize text content.

# Steps Taken
- Dropped location column.

- Filtered out rows with job descriptions under 50 characters.

- Removed rows where the job title was the same as the description.

- Exported the cleaned dataset to CSV for further modeling or analysis.

# Dataset Features
Cleaned data includes columns like:

title, company_profile, description, requirements, benefits, employment_type, industry, function, fraudulent, etc.

# Outcome: A well-structured, high-quality dataset ready for exploratory data analysis or fake job classification using NLP or ML models.
