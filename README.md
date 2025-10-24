# 🎬 NETFLIX DATA ANALYSIS - EDA USING MATPLOTLIB

![Python](https://img.shields.io/badge/Python-3.10%2B-blue?logo=python)
![Matplotlib](https://img.shields.io/badge/Visualization-Matplotlib-orange?logo=plotly)
![Pandas](https://img.shields.io/badge/Data%20Analysis-Pandas-yellow?logo=pandas)
![License](https://img.shields.io/badge/License-MIT-green)
![Status](https://img.shields.io/badge/Project%20Stage-EDA%20%7C%20Data%20Cleaning-blueviolet)

---

### 🔍 **Project Overview**
This project performs **Exploratory Data Analysis (EDA)** on the Netflix Titles dataset using **Matplotlib** and **Pandas**.

It marks the **first step in the AIML workflow** — where raw data is **preprocessed, cleaned, visualized, and understood** before training any Machine Learning models.

By analyzing Netflix’s catalog, this notebook provides insights into **content distribution, release trends, genres, ratings, and durations**.

---

### 🧠 **Objectives**
- 🧹 Clean and preprocess raw Netflix data  
- 📊 Visualize key patterns using Matplotlib  
- 🎞️ Compare Movies vs TV Shows content  
- 📈 Explore content growth trends over years  
- 🎬 Analyze duration, ratings, and genres  
- ⚙️ Prepare the data for future ML applications  

---

### 📂 **Dataset Information**
**Source:** Netflix Titles Dataset  
This dataset includes details about Netflix’s Movies and TV Shows.

| Feature | Description |
|----------|--------------|
| `show_id` | Unique identifier for each title |
| `type` | Movie or TV Show |
| `title` | Name of the content |
| `director` | Director(s) of the title |
| `cast` | Actors involved |
| `country` | Country of origin |
| `release_year` | Year the title was released |
| `rating` | Content rating (PG, R, etc.) |
| `duration` | Length of movie or number of seasons |
| `listed_in` | Genre/category |
| `description` | Brief summary of the content |

---

### 🧹 **Data Preprocessing Steps**
✔️ Removed duplicates  
✔️ Handled missing values  
✔️ Cleaned text and numeric columns  
✔️ Extracted integer durations (`90 min → 90`)  
✔️ Converted categorical data to uniform format  
✔️ Prepared the dataset for visualization and modeling  

---

### 📊 **Exploratory Data Analysis**
Key visualizations created using **Matplotlib**:

- 🎥 Distribution of **Movies vs TV Shows**
- 📅 **Content released per year**
- 🌍 **Top 10 countries** producing Netflix titles
- 🧾 **Ratings breakdown**
- ⏱️ **Distribution of movie durations**

> These plots help understand Netflix’s global expansion, content focus, and audience rating distribution.

---

### 🧰 **Tech Stack & Libraries**
| Library | Purpose |
|----------|----------|
| 🐍 **Python** | Programming language |
| 🧮 **NumPy** | Numerical computation |
| 🧾 **Pandas** | Data cleaning & manipulation |
| 📊 **Matplotlib** | Visualization library |
