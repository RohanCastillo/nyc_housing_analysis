# NYC Housing Affordability Analysis (2014–2024)

This project explores **NYC residential sale prices** across boroughs from 2014 to 2024. The goal is to identify **neighborhoods and boroughs** with the most affordable housing and understand long-term affordability trends.

---

## Project Objectives

- Analyze NYC residential sale records (2014–2024)
- Clean and standardize large Excel datasets from NYC open data
- Compare affordability across NYC boroughs
- Visualize long-term trends in sale prices
- Identify potentially undervalued areas

---

## Project Structure

nyc-housing-affordability/
│
├── data/ # Raw and cleaned datasets
├── notebooks/ # Analysis notebooks and data cleaning scripts
├── visuals/ # Charts, plots, and generated visuals
├── README.md # You are here
└── .gitignore
---


## Data Cleaning
This project includes:

- Standardizing column names
- Converting borough codes → borough names
- Filtering valid sale prices
- Handling missing values
- Parsing property types
- Removing outliers
- Fixing categorical formatting issues

Data cleaning is done using:

- **Pandas**
- **Regex**
- **Custom utility functions**

---

## Visuals

Below are some of the visuals generated in this project (kept in the `visuals/` folder):
- Borough Median Sale Price Percent Change (2014-2024)
- Median Sale Price by Borough (2014-2024)
- Median Sale Price by year (NYC 2014-2024)
- NYC Median Sale Price by Zipcode heatmap
