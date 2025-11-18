# 📊 Netflix Movies & TV Shows — Exploratory Data Analysis (EDA)

This project explores the Netflix Movies & TV Shows dataset to uncover patterns about content types, genres, countries, release years, and platform trends.  
The goal is to clean the dataset, prepare it for analysis, and create meaningful visualizations that explain how Netflix’s library has evolved over time.

---

## 🚀 Project Objectives

- Perform complete **data cleaning** (handling missing values, fixing formats, standardizing text).
- Conduct extensive **data exploration** using Pandas.
- Generate **visual insights** using Matplotlib and Seaborn.
- Understand trends in:
  - Content types (Movies vs TV Shows)
  - Genre distribution
  - Country additions
  - Ratings
  - Release year patterns
  - Date added trends

---

## 🧹 Data Cleaning Steps

- Filled missing values in `director`, `cast`, `country`.
- Converted `date_added` to proper datetime format.
- Extracted `year_added` and `month_added`.
- Standardized text columns (trim spaces, formatted string values).
- Ensured consistent genre/category labels.

---

## 📈 Key Explorations & Visualizations

- Distribution of movies vs. TV shows  
- Top genres based on listed categories  
- Ratings distribution  
- Content added by year  
- Country-wise presence on Netflix  
- Runtime and season distribution (if applicable)

---

## 🛠️ Technologies Used

- **Python**
- **Pandas**
- **NumPy**
- **Matplotlib**
- **Seaborn**
- **Jupyter Notebook / Kaggle Notebook**

---

```

# 📁 Project Structure

Netflix_shows_EDA
│
├── Netflix_shows.ipynb        # Main analysis notebook
├── README.md                # Documentation
└── dataset/
    └── netflix_shows.csv            # Dataset file

```
