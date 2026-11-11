# 🎬 Netflix Data Analysis Project

## 📌 Project Overview

This project focuses on analyzing Netflix Movies and TV Shows data using Python. The objective is to explore Netflix's content library, identify trends, understand content distribution, and generate meaningful insights through data visualization.

## 🎯 Project Objectives

- Analyze Netflix Movies and TV Shows.
- Perform data cleaning and preprocessing.
- Identify missing values and duplicate records.
- Explore content distribution by type.
- Analyze top countries and popular genres.
- Understand yearly content trends.
- Visualize findings using charts.

## 🛠️ Technologies Used

| Technology | Purpose |
|---|---|
| Python | Programming |
| Pandas | Data cleaning and manipulation |
| Matplotlib | Data visualization |
| Google Colab | Cloud-based development environment |

## 📂 Project Structure

```text
PROJECT 3/
│
├── netflix_titles.csv
├── netflix_cleaned.csv
├── Netflix_Data_Analysis.ipynb
├── netflix_data_analysis.py
├── README.md
│
└── charts/
    ├── 01_content_distribution.png
    ├── 02_top_countries.png
    ├── 03_yearly_content_trend.png
    ├── 04_movies_vs_tv_yearly.png
    ├── 05_top_genres.png
    └── 06_release_period_distribution.png
```

## 📊 Dataset Information

- Dataset: Netflix Movies and TV Shows
- Total Records: 8,807
- Total Columns: 12
- Source: Kaggle – Netflix Movies and TV Shows Dataset

### Important Columns

- show_id
- type
- title
- director
- cast
- country
- date_added
- release_year
- rating
- duration
- listed_in
- description

## 🧹 Data Cleaning & Preprocessing

The following operations were performed:

1. Loaded the dataset using Pandas.
2. Inspected dataset structure and data types.
3. Identified missing values.
4. Checked duplicate records.
5. Handled missing values in selected columns.
6. Converted `date_added` into datetime format.
7. Created a cleaned dataset.
8. Verified the cleaned dataset.

## 📈 Data Analysis & Visualizations

Six visualizations were created:

| No. | Analysis | Chart Type |
|---|---|---|
| 01 | Movies vs TV Shows | Bar Chart |
| 02 | Top 10 Countries | Horizontal Bar Chart |
| 03 | Yearly Content Trend | Line Chart |
| 04 | Movies vs TV Shows by Year | Grouped Bar Chart |
| 05 | Top 10 Genres | Horizontal Bar Chart |
| 06 | Release Period Distribution | Donut Chart |

## 🔍 Key Findings

- Total Netflix titles analyzed: 8,807.
- Movies: 6,131 (69.6%).
- TV Shows: 2,676 (30.4%).
- Movies represent the larger share of Netflix's content library.
- The 2010–2019 release period contains the highest number of titles in the dataset.

## 🚀 How to Run the Project

1. Clone or download this repository.
2. Install the required libraries:

```bash
pip install pandas matplotlib
```

3. Open `Netflix_Data_Analysis.ipynb` using Google Colab.
4. Upload or load the original CSV dataset.
5. Run the notebook cells sequentially.
6. Explore the analysis and visualizations.

## 📌 Project Outcome

This project demonstrates practical skills in Python, Pandas, data cleaning, Exploratory Data Analysis (EDA), and data visualization.

It provides insights into Netflix's content distribution, release patterns, countries, and genres.

## 👨‍💻 Author

**Krishna Prasath**

Data Analytics | Python | SQL | Pandas | Matplotlib 