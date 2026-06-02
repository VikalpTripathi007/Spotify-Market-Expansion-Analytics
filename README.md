# Spotify-Market-Expansion-Analytics
# 🎵 Spotify Data Analysis Dashboard

A comprehensive Power BI dashboard designed to analyze and visualize Spotify music trends, streaming history, and audio features. This project transforms raw Spotify data into actionable insights regarding listening habits, track popularity, and artist performance.

---

## 🚀 Project Overview

This repository contains the `.pbix` file for a fully interactive Power BI dashboard. The analysis focuses on deep-diving into streaming metrics, identifying patterns in user engagement, and breaking down the sonic attributes (like danceability, energy, and valence) of top tracks.

### Key Insights Tracked:
* **Listening Trends:** Hourly, daily, and seasonal streaming activity patterns.
* **Top Performers:** Most-streamed artists, albums, and tracks over time.
* **Audio Features Analysis:** Distribution of track metrics such as acousticness, energy, tempo, and liveness.
* **Genre Breakdown:** Popularity and dominance of various music genres across the dataset.

---

## 🛠️ Built With

* **Power BI Desktop:** For data modeling, DAX calculations, and report visualization.
* **Power Query:** For ETL (Extract, Transform, Load) processes, data cleaning, and schema normalization.
* **Data Source:** Spotify Web API / Extended Streaming History JSON exports.

---

## 📊 Dashboard Architecture & Features

### 1. Data Model
The project utilizes a optimized Star Schema design consisting of:
* `Fact_Streams` (Fact table capturing play counts, duration, and timestamps)
* `Dim_Tracks` (Dimension table with audio features)
* `Dim_Artists` (Dimension table for artist metadata)
* `Dim_Calendar` (Custom DAX date table for time-intelligence analysis)

### 2. Key DAX Measures Included
* **Total Play Time:** Summing total milliseconds streamed converted to hours.
* **Skip Rate %:** Percentage of tracks skipped before completing 30 seconds.
* **Active Days:** Unique count of days with streaming activity.

---

## 📸 Screenshots

*(Tip: Place your dashboard screenshots in an `images/` folder in your repo and link them here)*

| Main Overview Dashboard | Audio Features Deep Dive |
| :---: | :---: |
| <img src="images/overview_dashboard.png" width="400"> | <img src="images/features_dashboard.png" width="400"> |

---

## 🏃‍♂️ How to Run This Project Locally

To explore the interactive dashboard yourself, follow these steps:

### Prerequisites
* Windows OS (Power BI Desktop is currently Windows-only).
* [Power BI Desktop](https://powerbi.microsoft.com/desktop/) installed.

### Setup
1. **Clone the Repository:**
   ```bash
   git clone [https://github.com/YOUR_USERNAME/YOUR_REPOSITORY_NAME.git](https://github.com/YOUR_USERNAME/YOUR_REPOSITORY_NAME.git)
