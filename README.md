# 🎬 Movie Data Analysis with Python

This repository contains a full analysis of IMDB movie data using Python, including data preprocessing, exploratory data analysis (EDA), visualization, and revenue prediction using machine learning models.

## 📊 Project Overview

The dataset contains details of 1,000 movies including:
- Title, Genre, Description
- Director & Actors
- Year of Release
- Runtime (Minutes)
- IMDB Rating
- Number of Votes
- Revenue (Millions)
- Metascore

## 🧰 Tools & Libraries Used

- Python 3
- Pandas
- NumPy
- Seaborn
- Matplotlib
- Scikit-learn

## 📌 Key Features

- ✅ Data Cleaning (handling nulls and duplicates)
- 📈 Data Visualization (heatmaps, bar plots, line graphs, scatter plots)
- 🧠 Machine Learning Models:
  - Linear Regression
  - Random Forest Regressor
- 📉 Model Evaluation Metrics:
  - R² Score
  - Mean Absolute Error
  - Root Mean Squared Error

## 🔍 Highlights from Analysis

- Top 10 movies by:
  - Rating
  - Votes
  - Revenue
- Trends in movie duration, votes, and revenue by release year
- Runtime analysis for movies over 3 hours
- Revenue prediction based on votes

## 🚀 How to Run

1. Clone this repository
2. Ensure you have Python 3 and required libraries installed (`pip install -r requirements.txt`)
3. Open the notebook `Movie_Analysis.ipynb` in Jupyter
4. Run all cells to view the full analysis and results

## 📁 Dataset

Dataset used: `IMDB-Movie-Data.csv`  
Contains 1,000 entries of movies released between 2006 and 2016.

## 📈 Sample Visualizations

- Heatmap of missing values
- Runtime vs Year scatter plot
- Revenue trends by year
- Votes per movie by year

## 🤖 Model Results

- **Linear Regression R²:** ~0.41
- **Random Forest R²:** ~0.86

## 📬 Contact

For queries or feedback, please reach out via GitHub Issues or pull requests.

---

📌 *This project was created for academic and learning purposes.*
