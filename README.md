# 🎵 Spotify Music Intelligence Dashboard
### Exploratory Data Analysis on 114,000+ Spotify Tracks

![Python](https://img.shields.io/badge/Python-3.14-blue)
![Pandas](https://img.shields.io/badge/Pandas-Data%20Analysis-green)
![Matplotlib](https://img.shields.io/badge/Matplotlib-Visualization-orange)
![Seaborn](https://img.shields.io/badge/Seaborn-Statistical%20Plots-red)
![Status](https://img.shields.io/badge/Project-Completed-brightgreen)

---

# 📌 Project Overview

Spotify hosts millions of songs across thousands of genres and artists. Understanding what makes a song popular can provide valuable insights into listener behavior, music trends, and audio characteristics.

This project performs an in-depth **Exploratory Data Analysis (EDA)** on a Spotify dataset containing **114,000+ tracks** and **20 audio-related features**.

The objective is to uncover patterns, relationships, and trends between song popularity and musical attributes such as:

- 🎤 Artists
- 🎶 Genres
- 💃 Danceability
- ⚡ Energy
- 🔊 Loudness
- 🎵 Tempo
- ❤️ Valence
- 🎧 Acousticness
- 🎸 Instrumentalness

The analysis transforms raw Spotify data into meaningful insights using data cleaning, statistical summaries, visualizations, and correlation analysis.

---

# 🎯 Project Objectives

✅ Clean and prepare Spotify track data

✅ Perform statistical exploration

✅ Analyze popularity distribution

✅ Investigate genre trends

✅ Study artist representation

✅ Explore relationships between popularity and audio features

✅ Generate business and music-industry insights

✅ Build a professional EDA portfolio project

---

# 📂 Dataset Information

### Dataset Size

| Metric | Value |
|----------|----------|
| Total Tracks | 114,000+ |
| Features | 20 |
| Missing Values | Removed |
| Final Records | 113,999 |

### Important Features

| Feature | Description |
|----------|-------------|
| popularity | Spotify popularity score (0–100) |
| duration_ms | Track duration |
| danceability | Suitability for dancing |
| energy | Intensity and activity level |
| loudness | Overall volume |
| speechiness | Presence of spoken words |
| acousticness | Acoustic confidence score |
| instrumentalness | Instrumental probability |
| liveness | Presence of audience |
| valence | Musical positivity |
| tempo | Beats per minute |
| track_genre | Genre classification |

---

# 🛠️ Technologies Used

### Programming

- 🐍 Python

### Libraries

- 📊 Pandas
- 🔢 NumPy
- 📈 Matplotlib
- 🎨 Seaborn

### Environment

- 📓 Jupyter Notebook
- 💻 VS Code
- 🌐 GitHub

---

# 📁 Project Structure

```text
Spotify_Music_Intelligence/
│
├── data/
│   └── spotify_tracks.csv
│
├── images/
│   ├── popularity_distribution.png
│   ├── top_genres.png
│   ├── top_artists.png
│   ├── explicit_content.png
│   ├── correlation_heatmap.png
│   ├── popularity_vs_danceability.png
│   ├── popularity_vs_energy.png
│   ├── danceability_distribution.png
│   └── energy_distribution.png
│
├── notebooks/
│   └── spotify_eda.ipynb
│
├── reports/
│
├── src/
│   ├── analysis.py
│   ├── data_cleaning.py
│   └── visualization.py
│
├── README.md
├── requirements.txt
└── .gitignore
```

---

# 🧹 Data Cleaning Process

The following preprocessing steps were performed:

### Step 1

Removed unnecessary index column:

```python
df.drop(columns=['Unnamed: 0'])
```

### Step 2

Handled missing values:

```python
df.dropna()
```

### Step 3

Reset dataframe index:

```python
df.reset_index(drop=True)
```

### Result

✅ Dataset completely cleaned

✅ No missing values remaining

✅ Ready for analysis

---

# 📊 Exploratory Data Analysis

The project includes multiple analytical sections:

## 📈 Popularity Distribution

Analyzed how song popularity scores are distributed across Spotify tracks.

### Insight

Most songs fall within low-to-medium popularity ranges, while highly popular songs represent a small percentage of tracks.

---

## 🎵 Top Genres Analysis

Identified the most represented genres within the dataset.

### Insight

Spotify contains significant genre diversity, reflecting broad listener preferences.

---

## 🎤 Top Artists Analysis

Examined artists with the highest track representation.

### Insight

Certain artists contribute a substantial number of tracks compared to others.

---

## 🚫 Explicit Content Analysis

Compared explicit and non-explicit songs.

### Insight

Non-explicit tracks dominate the dataset, although explicit content still represents a meaningful share.

---

## 🔥 Danceability Distribution

Studied the distribution of danceability scores.

### Insight

Most songs cluster around moderate-to-high danceability levels.

---

## ⚡ Energy Distribution

Explored how energetic Spotify songs tend to be.

### Insight

The majority of tracks possess medium-to-high energy characteristics.

---

## 🎯 Popularity vs Danceability

Analyzed whether danceability affects popularity.

### Insight

More danceable songs show a slight tendency toward higher popularity.

---

## 🎯 Popularity vs Energy

Analyzed whether energy levels impact popularity.

### Insight

Energy alone does not strongly determine track popularity.

---

## 🔗 Correlation Heatmap

Generated a correlation matrix among numerical variables.

### Insight

Several audio features show meaningful relationships, but popularity depends on multiple factors.

---

# 💡 Key Business Insights

### 🎯 Insight 1

Highly popular songs are relatively rare.

---

### 🎯 Insight 2

Genre diversity plays an important role in audience engagement.

---

### 🎯 Insight 3

Danceability shows moderate influence on popularity.

---

### 🎯 Insight 4

Energy levels alone are not enough to predict success.

---

### 🎯 Insight 5

Most songs follow similar duration patterns.

---

# 📸 Visualizations Generated

The project automatically saves all generated charts inside the `images/` folder:

- 📊 Popularity Distribution
- 🎵 Top Genres
- 🎤 Top Artists
- 🚫 Explicit Content Analysis
- 💃 Danceability Distribution
- ⚡ Energy Distribution
- 🔥 Popularity vs Danceability
- 🔥 Popularity vs Energy
- 🔗 Correlation Heatmap

---

# 🚀 Future Improvements

Possible extensions of this project:

- 🎯 Machine Learning Popularity Prediction
- 🎵 Music Recommendation System
- 📈 Interactive Power BI Dashboard
- 🌐 Streamlit Web Application
- 🤖 Genre Classification Model

---

# 🏆 Project Outcome

This project demonstrates:

✔ Data Cleaning

✔ Exploratory Data Analysis

✔ Statistical Interpretation

✔ Data Visualization

✔ Insight Generation

✔ GitHub Project Management

✔ Real-World Dataset Handling

These skills are fundamental for Data Analyst, Data Science, and Machine Learning roles.

---

# 👨‍💻 Author

### Anish Das

First-Year Computer Science Engineering Student

Passionate about:
- 📊 Data Science
- 🤖 Machine Learning
- 💻 Software Development
- 🚀 AI & Analytics

---

⭐ If you found this project useful, consider giving it a star on GitHub!