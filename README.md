# Data-Wrangling-Project
A data wrangling project focused on analyzing U.S. police killings and racial demographics by city. This project includes data gathering, cleaning, merging, and exploratory data analysis to uncover patterns and insights from real-world datasets.


# US Police Killings & Racial Demographics - Data Wrangling Project

## 📌 Project Overview
This project focuses on cleaning, merging, and exploring two related real-world datasets:
- One detailing police killings across the United States.
- Another providing racial demographic shares by U.S. cities.

The goal is to perform the complete data wrangling process using Python, including gathering, assessing, cleaning, storing, and analyzing data using a Jupyter Notebook. The final output includes visual insights that help answer a key research question.

## 📁 Project Structure
├── Data_Wrangling_Project_Starter.ipynb

├── DataSets.txt

├── PoliceKillingsUS.csv

├── ShareRaceByCity.csv

└── README.md


## 🧩 Datasets Used
### 1. Police Killings in the US
- **Source:** [https://www.kaggle.com/datasets/kwullum/fatal-police-shootings-in-the-us?resource=download&select=PoliceKillingsUS.csv]
- Contains information about individuals killed by police, including race, city, cause of death, and other details.

### 2. Racial Demographics by City
- **Source:** [https://www.kaggle.com/datasets/kwullum/fatal-police-shootings-in-the-us?resource=download&select=ShareRaceByCity.csv]
- Provides the share of different racial groups in various cities across the United States.

These datasets are linked by a **common key: city name**, allowing for effective merging and comparative analysis.

## ⚠️ Data Issues Resolved
The datasets had several data quality and tidiness issues:
- Missing values (e.g., `NaN` in racial categories or unknown causes of death).
- Inconsistent capitalization and formatting.
- Tidiness issue: a single observation spread across two tables (merged during cleaning).
- Incorrect data types (e.g., strings instead of numeric values).

## ✅ Steps Completed
- **Data Gathering:** Manual download of both datasets from reliable sources.
- **Assessment:** Visual + programmatic inspection using Pandas functions.
- **Cleaning:** Addressed missing values, reformatted columns, standardized city names, merged datasets.
- **Exploration:** Performed statistical summaries and created visualizations to analyze trends.

## 📊 Tools & Libraries
- Python 3.x
- Jupyter Notebook
- Pandas
- NumPy
- Matplotlib
- Seaborn

## 📈 Key Insights
- Cities with higher Black populations showed disproportionately higher rates of police killings involving Black victims.
- The number of police killings did not strongly correlate with total city population but showed a pattern across racial demographics.

## 🔧 How to Run
1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/us-police-killings-data-wrangling.git
   cd us-police-killings-data-wrangling
