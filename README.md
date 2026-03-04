# Nigerian-football-Club-data-analysis

# ⚽ Nigeria Premier Football League (NPFL) Data Pipeline Project

## 📌 Project Overview

Access to structured sports data in African football is limited.

So instead of starting with advanced modeling, I started with the real bottleneck:

**Data acquisition.**

This project focuses on scraping, structuring, and cleaning Nigeria Premier Football League (NPFL) data to build a usable foundation for future sports analytics work.

---

## 🧠 What This Project Does

This repository contains two structured scraping workflows:

### 1️⃣ NPFL Standings Scraper
- Scrapes real-time league table data from the official NPFL website
- Handles 403 errors using custom request headers
- Extracts performance metrics (P, W, D, L, F, A, GD, Pts)
- Converts numeric columns properly
- Computes Win Percentage
- Exports a clean CSV dataset

---

### 2️⃣ NPFL Club Information Scraper
- Scrapes club information from Wikipedia
- Extracts team, location, stadium, and capacity data
- Cleans inconsistent capacity formatting
- Converts capacity values to proper numeric types
- Structures data for analysis and export

---

## 🛠 Tools & Technologies

- Python
- Requests
- BeautifulSoup
- Pandas
- Jupyter Notebook

---

## 🎯 Why This Matters

Sports analytics doesn’t start with machine learning.

It starts with:

- Reliable data
- Clean structure
- Reproducible pipelines

For leagues like the NPFL, structured datasets are not readily accessible.

This project builds that foundation.

---

## 🚀 Next Steps

With the dataset now structured, future work can include:

- Performance trend analysis
- Home vs away efficiency comparison
- Stadium capacity vs performance correlation
- Predictive modeling
- Longitudinal league analysis

This repository represents Step 1: building access before building intelligence.

---

## 📂 Repository Structure

- `Sports_Analytics_Project.ipynb` — League standings scraper & performance metric preparation  
- `Sport_Analytics_Nigerian_club_info.ipynb` — Club metadata scraper & cleaning workflow  

---

## 📈 Personal Note

This project reflects my approach to data:

Understand the source.  
Build the pipeline.  
Structure the dataset.  
Then extract insight.

African sports analytics has massive untapped potential — and this is the starting point.


📊 Final Structured Dataset

The cleaned dataset is located in:

`data/processed/npfl_2023_24_structured_data.csv`

It includes:

Team performance metrics

Engineered Win Percentage

Cleaned stadium capacity data

Structured numeric fields ready for analysis

Commercial metadata (kit & shirt sponsors)

This dataset serves as the foundation for downstream analysis and BI development.


📊 Business Intelligence & Visualization Layer

After structuring the dataset, I developed an interactive Power BI dashboard using the processed CSV file located in:

`data/processed/npfl_2023_24_structured_data.csv`

The dashboard explores:

League performance distribution

Goals scored vs goals conceded analysis

Win percentage comparison

Stadium capacity impact analysis

Commercial patterns (kit & shirt sponsors)

This transforms the dataset from structured data into actionable insight.
