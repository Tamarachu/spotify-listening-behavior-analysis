# Spotify Listening Behavior Analysis

Behavioral analysis of long-term Spotify listening history using Python, session analytics, and clustering techniques.

---

# Project Overview

This project explores long-term Spotify listening behavior using exploratory data analysis, feature engineering, behavioral analytics, and unsupervised machine learning.

The analysis focuses on identifying:

- Listening activity patterns over time
- Behavioral engagement trends
- Session-level listening behavior
- Skip behavior
- Artist dominance trends
- Behavioral listening archetypes through clustering

The project was designed to simulate real-world product and behavioral analytics workflows commonly used in digital streaming platforms.

---

# Dataset

The dataset was obtained through Spotify Extended Streaming History exports.

The original raw dataset included:

- Timestamped listening activity
- Track and artist metadata
- Playback duration
- Skip behavior
- Platform information
- Shuffle and offline activity indicators

Raw/private user data was excluded from the public repository.

---

# Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- Jupyter Notebook

---

# Analytical Workflow

## 1. Data Cleaning & Feature Engineering

The raw Spotify export data was cleaned and transformed into an analysis-ready dataset.

Additional behavioral features were engineered, including:

- Listening duration in minutes
- Hour of day
- Day of week
- Year and month
- Session identifiers
- Session duration
- Skip rate metrics

---

## 2. Exploratory Behavioral Analysis

Behavioral listening patterns were explored through:

- Listening activity heatmaps
- Hourly engagement analysis
- Artist listening trends
- Artist dominance over time
- Listening diversity trends

---

## 3. Session Analytics

Listening sessions were reconstructed using inactivity-gap sessionization logic.

Session-level analysis included:

- Session duration distribution
- Session engagement depth
- Tracks played per session
- Session skip behavior
- Time-of-day engagement patterns

---

## 4. Behavioral Segmentation

KMeans clustering was applied to identify distinct listening behavior archetypes.

Features used for clustering:

- Session duration
- Tracks played
- Skip rate

The analysis identified multiple behavioral listening patterns, including:

- Deep immersion sessions
- Focused low-skip sessions
- Exploratory high-skip sessions
- Standard engagement sessions

---

# Key Findings

- Listening activity demonstrated highly consistent time-based behavioral patterns.
- Long-duration immersive listening sessions occurred frequently.
- Artist concentration did not eliminate broader listening diversity.
- Listening behavior could be segmented into distinct behavioral archetypes using unsupervised learning techniques.
- Session duration and skip behavior showed meaningful behavioral relationships.

---

# Repository Structure

```text
spotify-listening-behavior-analysis/
│
├── notebooks/
│   ├── 01_data_loading.ipynb
│   └── spotify_behavioral_analysis.ipynb
│
├── visuals/
│   └── exported project visualizations
│
├── requirements.txt
├── .gitignore
└── README.md
```

---

# Example Visualizations

## Listening Activity Heatmap

Behavioral visualization of listening intensity by weekday and hour.

## Behavioral Session Clusters

Visualization of clustered listening session archetypes based on engagement metrics.

## Artist Listening Trends

Long-term artist listening evolution across multiple years of streaming history.

---

# Future Improvements

Potential future extensions for the project include:

- Dashboard deployment using Streamlit or Tableau
- Predictive behavioral modeling
- Genre enrichment analysis
- Recommendation-system experimentation
- Advanced temporal trend forecasting

---

# Author

Tamara Panda  
B.Sc. in Digital Sciences & Biology  
Focused on behavioral analytics, data analysis, and machine learning applications.
