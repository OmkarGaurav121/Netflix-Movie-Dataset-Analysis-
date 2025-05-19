# 🎬 Netflix Movie Dataset Analysis

This repository contains a data analysis project on Netflix movies using Python. The analysis includes data cleaning, feature engineering, and exploratory data visualization.

---

## 📦 Technologies Used

- Python
- Pandas
- Matplotlib
- Seaborn
- Jupyter Notebook / Google Colab

---

## 📊 Dataset Summary

- **File:** `mymoviedb.csv`
- **Rows:** 9827 movies
- **Columns:** Title, Release Date, Popularity, Vote Count, Vote Average, Genre, etc.

---

## 🧹 Data Cleaning Steps

- Converted `Release_Date` to year format
- Dropped unnecessary columns: `Overview`, `Original_Language`, `Poster_Url`
- Removed duplicates and nulls
- Exploded `Genre` column to handle multiple genres per movie
- Categorized `Vote_Average` into 4 levels:
  - Not_Popular
  - Below_Average
  - Average
  - Popular

---

## 🔍 Analysis & Visualizations

- 📌 **Most Frequent Genre**: Drama
- 🏆 **Most Popular Movie**: Spider-Man: No Way Home
- 🔻 **Least Popular Movie**: The United States vs. Billie Holiday
- 📅 **Year with Most Releases**: Visualized via histogram
- 📊 **Rating Distribution**: Categorized and visualized

---

## 📈 Key Charts

- Genre Distribution (bar chart)
- Vote Average Category Distribution (bar chart)
- Movie Releases by Year (histogram)

---

## 🚀 How to Run

1. Clone this repo or download the files
2. Place `mymoviedb.csv` in the same directory
3. Open `Netflix_Movie_Analysis.ipynb` or `.py` file in Jupyter or Colab
4. Run all cells to explore the dataset and visuals

---

## 🙌 Credits

Data Source: TMDB (via a scraped Netflix dataset)

Made with ❤️ using Python.
