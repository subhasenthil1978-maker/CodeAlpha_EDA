# CodeAlpha_EDA
````markdown
# 🎵 CodeAlpha Internship – Data Analytics

## 📊 Task 2: Exploratory Data Analysis (EDA)

### 📌 Project Overview

This project performs a comprehensive **Exploratory Data Analysis (EDA)** on a Spotify audio features dataset containing **32,833 tracks** and **23 attributes**. The primary objective is to understand the dataset's structure, analyze audio feature distributions, identify genre-wise trends, validate statistical relationships, and detect data quality issues such as missing values and duplicate records.

---

## 🎯 Objectives

The analysis focuses on answering the following questions:

- What is the overall structure of the dataset?
- How are the numerical and categorical features distributed?
- Is there a relationship between **energy** and **loudness**?
- Are there any missing values or duplicate records?

---

## 🛠️ Technology Stack

- **Language:** Python 3.12+
- **Environment:** Google Colab / Visual Studio Code
- **Libraries:**
  - Pandas
  - NumPy

---

## 📂 Dataset Summary

| Property | Value |
|----------|-------|
| Total Records | 32,833 |
| Total Features | 23 |
| File Format | CSV |

---

## 📈 Key Findings

### Dataset Structure

- Dataset contains **32,833 tracks**.
- A total of **23 features** describe each track.
- Features include:
  - **Categorical:** `track_id`, `track_name`, `playlist_genre`, etc.
  - **Numerical:** `danceability`, `energy`, `loudness`, `tempo`, `valence`, and more.

### Statistical Insights

- Electronic (EDM) and Rock genres have the highest average **energy** levels.
- Pop and Rap tracks generally have higher average **popularity**.
- Popularity scores are unevenly distributed across genres.

### Feature Relationships

- A strong positive correlation exists between **loudness** and **energy**.
- Tracks with higher loudness generally exhibit higher energy.

### Data Quality Analysis

#### Missing Values

- No missing or null values were found in the dataset.

#### Duplicate Records

- **4,477 duplicate track IDs** were identified.
- These duplicates occur because the same track appears in multiple playlists rather than due to data corruption.

---

## 🚀 How to Run

### 1. Clone the Repository

```bash
git clone https://github.com/your-username/your-repository.git
cd your-repository
````

### 2. Install Dependencies

```bash
pip install pandas numpy
```

### 3. Run the Python Script

```bash
python eda.py
```

---

## 📁 Project Structure

```
.
├── dataset/
│   └── spotify_songs.csv
├── eda.py
├── README.md
└── requirements.txt
```

---

## 📚 Learning Outcomes

This project strengthened my understanding of:

* Exploratory Data Analysis (EDA)
* Data cleaning and validation
* Descriptive statistics
* Data integrity checks
* Feature relationship analysis
* Working with large datasets using Pandas and NumPy

---

## 📌 Conclusion

This Exploratory Data Analysis provides meaningful insights into Spotify's audio features dataset by examining its structure, identifying genre-specific trends, analyzing relationships between musical attributes, and evaluating data quality. The findings serve as a solid foundation for future machine learning models and music recommendation systems.

---

## 👨‍💻 Author

**Subha S**

Artificial Intelligence & Data Science Student

CodeAlpha Data Analytics Internship

```
```
