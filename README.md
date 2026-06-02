# Netflix Content Analysis 📺

## Project Overview

This project performs an in-depth Exploratory Data Analysis (EDA) on Netflix's content catalog to uncover trends, patterns, and insights related to movies and TV shows available on the platform.

The analysis focuses on understanding content distribution, growth trends, ratings, countries of origin, genres, and overall characteristics of Netflix's library using Python-based data analysis tools.

---

## Objectives

The primary goals of this project are:

- Understand the distribution of Movies and TV Shows
- Analyze content growth over time
- Identify top content-producing countries
- Examine content ratings and audience categories
- Explore genre distribution
- Perform data cleaning and preprocessing
- Generate meaningful business insights from the dataset

---

## Dataset Information

The dataset contains information about Netflix titles, including:

| Feature | Description |
|----------|-------------|
| show_id | Unique identifier |
| type | Movie or TV Show |
| title | Name of the title |
| director | Director information |
| cast | Cast information |
| country | Country of origin |
| date_added | Date added to Netflix |
| release_year | Original release year |
| rating | Content rating |
| duration | Duration or number of seasons |
| listed_in | Genre classification |
| description | Brief description |

---

## Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Jupyter Notebook

---

## Project Workflow

### 1. Data Collection
- Loaded Netflix dataset into Pandas DataFrame.

### 2. Data Understanding
- Examined dataset dimensions.
- Reviewed column information and data types.

### 3. Data Cleaning
- Handled missing values.
- Removed inconsistencies.
- Converted date columns into proper datetime format.

### 4. Feature Engineering
- Extracted year and month information from dates.
- Created additional features for temporal analysis.

### 5. Exploratory Data Analysis
Performed analysis on:

- Movies vs TV Shows
- Content ratings
- Top countries
- Genre distribution
- Release year trends
- Netflix content growth

### 6. Data Visualization
Created visualizations using:

- Bar Charts
- Count Plots
- Histograms
- Heatmaps
- Distribution Plots

---

## Key Insights

- Movies dominate Netflix's content library.
- The United States contributes the highest number of titles.
- TV-MA is the most common content rating.
- Netflix experienced rapid content growth between 2016 and 2019.
- Drama and International content are among the most popular categories.
- TV Shows have shown steady growth in recent years.

---

## Project Structure

Netflix-Content-Analysis-EDA/

├── data/
│ └── netflix_titles.csv
│
├── notebooks/
│ └── Netflix_EDA.ipynb
│
├── images/
│ └── visualizations
│
├── README.md
│
├── requirements.txt
│
└── .gitignore

---

## Installation

Clone the repository:

```bash
git clone https://github.com/yourusername/Netflix-Content-Analysis-EDA.git
```

Move into the project directory:

```bash
cd Netflix-Content-Analysis-EDA
```

Install dependencies:

```bash
pip install -r requirements.txt
```

Launch Jupyter Notebook:

```bash
jupyter notebook
```

---

## Future Improvements

- Interactive dashboard using Streamlit
- Genre recommendation analysis
- Content forecasting
- Netflix content clustering using Machine Learning
- Sentiment analysis on descriptions

---

## Author

Sakshi Patil

GitHub: https://github.com/SakshiPatil249
