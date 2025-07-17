# 🎬 Movie Profitability Analysis – EDA Project

This project analyzes a dataset of movies to explore key profitability drivers such as production budget, revenues, distributor impact, genre-wise trends, and audience ratings.

> 📁 Dataset: Contains columns like `movie_title`, `genre`, `production_budget`, `domestic_gross`, `worldwide_gross`, `release_date`, `distributor`, `mpaa_rating`, and `runtime`.

---

## 🚀 Objective

To explore and visualize the relationship between movie features (like budget, rating, distributor) and their profitability using Python (Pandas, Matplotlib, Seaborn).

---

## 🧼 Data Cleaning & Initial Exploration

### ✅ Top 5 Rows  
![Top Rows](images/df_head.png)

### ✅ Dataset Info (dtypes, nulls)  
![Info](images/df_info.png)

### ✅ Summary Statistics  
![Describe](images/df_describe.png)

### ✅ Null Count Before & After Cleaning  
![Null Check](images/df_isnull.png)

---

## 📊 Exploratory Data Analysis (EDA)

### 🎭 Genre Distribution  
`df['genre'].value_counts()`  
![Genre Count](https://github.com/Dheeru0133/Eda/blob/main/images/genre_counts.png?raw=true)

### 🎞️ MPAA Rating Distribution  
`df['mpaa_rating'].value_counts()`  
![Rating Count](https://github.com/Dheeru0133/Eda/blob/main/images/mpaa_counts.png?raw=true)

### 💰 Histogram of Worldwide Gross  
`df['worldwide_gross'].plot(kind='hist')`  
![Histogram](https://github.com/Dheeru0133/Eda/blob/main/images/worldwide_gross_hist.png?raw=true)

### 🎨 Bar Chart: Total Budget by Genre  
Grouped bar chart of total production budget per genre  
![Budget by Genre](https://github.com/Dheeru0133/Eda/blob/main/images/budget_by_genre.png?raw=true)

### 🍿 Pie Chart: Domestic Gross by Rating  
Shows how much each MPAA rating contributed to domestic gross  
![Domestic by Rating](https://github.com/Dheeru0133/Eda/blob/main/images/domestic_by_rating_pie.png?raw=true)

### 📈 Line Chart: Mean Worldwide Gross per Year  
Tracks average worldwide gross of movies over the years  
![Mean Gross Line](https://github.com/Dheeru0133/Eda/blob/main/images/mean_gross_by_year.png?raw=true)

### 🔁 Line Chart: Mean Gross by New Year Column  
Line plot based on extracted `release_year` column  
![Release Year Line](images/release_year_line.png)

### 📉 Scatter Plot: Budget vs Worldwide Gross  
Relationship between production budget and worldwide gross  
![Scatter](images/scatter_budget_vs_gross.png)

### 🏢 Top 5 Distributors by Revenue  
Horizontal bar chart of top-grossing distributors  
![Top Distributors](images/top5_distributors.png)

### 🔍 Correlation Heatmap  
`df.corr(numeric_only=True)`  
![Heatmap](images/heatmap.png)

---

## 🛠️ Tools Used

- Python  
- Jupyter Notebook  
- Pandas  
- NumPy  
- Seaborn  
- Matplotlib  

---

## 📂 Folder Structure

```
Movie-Profitability-EDA/
│
├── movie_profit_EDA.ipynb
├── README.md
└── images/
    ├── df_head.png
    ├── df_info.png
    ├── df_describe.png
    ├── df_isnull.png
    ├── genre_value_counts.png
    ├── rating_value_counts.png
    ├── worldwide_gross_hist.png
    ├── budget_by_genre.png
    ├── domestic_by_rating_pie.png
    ├── mean_gross_by_year.png
    ├── release_year_line.png
    ├── scatter_budget_vs_gross.png
    ├── top5_distributors.png
    └── heatmap.png
```

---

## 📌 Summary

This EDA project gives a clear understanding of the movie industry trends by analyzing revenue, budgets, and factors impacting a movie's success.

> Ideal for portfolio demonstration, beginner-friendly EDA walkthroughs, or analytical storytelling with visual support.
