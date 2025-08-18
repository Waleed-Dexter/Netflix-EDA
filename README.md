# 📊 Exploratory Data Analysis (EDA) on Netflix Dataset

## 📌 Project Overview
This project performs an **Exploratory Data Analysis (EDA)** on the Netflix dataset to understand:
- Distribution of movies and TV shows
- Trends across years, genres, and countries
- Ratings and durations
- Correlations among features

The goal is to practice **data cleaning, visualization, and feature engineering** using Python libraries like `pandas`, `numpy`, `matplotlib`, and `seaborn`.

---

## 📂 Dataset
The dataset used is: **Netflix Titles 2021**  
File: `netflix_titles_2021.csv`  
- Rows: ~8800 titles  
- Columns: `show_id`, `type`, `title`, `director`, `cast`, `country`, `date_added`, `release_year`, `rating`, `duration`, `listed_in`, `description`

---

## ⚙️ Steps in the Project

1. **Data Import & Cleaning**
   - Load dataset using Pandas
   - Handle missing values (`director`, `cast`, `country`)
   - Convert date fields to datetime

2. **Exploratory Data Analysis**
   - Distribution of Movies vs TV Shows
   - Count of releases per year
   - Most common genres/categories
   - Top contributing countries

3. **Data Visualization**
   - Histograms, Barplots, Boxplots
   - Heatmaps (correlation)
   - Interactive plots with Plotly

4. **Feature Engineering**
   - Extract year, month from `date_added`
   - Create binary features (e.g., is_movie, is_tv_show)
   - Grouping and aggregations

---

## 📊 Visualizations
- Movie vs TV Show distribution  
- Content added over the years  
- Top 10 countries with most content  
- Genre popularity  

(📌 Example plots will be shown here once generated)

---

## 🛠️ Tech Stack
- **Python**
- **Pandas** → Data cleaning & manipulation  
- **NumPy** → Numerical operations  
- **Matplotlib / Seaborn** → Visualization  
- **Plotly** → Interactive plots  

---

## 🚀 How to Run
1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/netflix-eda.git
