# 🎬 Netflix Data Exploration Dashboard

This project explores Netflix’s extensive library of movies and TV shows using a data-driven approach. It offers insights across multiple dimensions including country, director, actor, release timelines, and content addition dates. The dashboard aims to provide a global perspective on digital entertainment trends.

## 📌 Project Motivation

With Netflix reshaping how global audiences consume content, this project was inspired by the desire to better understand:
- The volume and distribution of content added to Netflix over time
- Patterns in direction, casting, and content production
- Global content contributions across countries

## 📊 Data Overview

- **Source**: [Netflix Movies and TV Shows – Kaggle](https://www.kaggle.com/datasets/shivamb/netflix-shows)
- **Format**: CSV
- **Records**: 8,807 Netflix titles (as of mid-2021)
- **Key Fields**: 
  - `show_id`, `type`, `title`, `director`, `cast`, `country`, `date_added`, `release_year`, `rating`, `duration`

## 🧹 Data Preparation

- **Unpivoted**: Country, director, and cast columns were unpivoted in Excel to facilitate accurate aggregation and visualization.
- **Cleaned**: Blank and redundant rows were removed, and whitespace was trimmed to ensure consistent analysis.
- **Tool Used**: Microsoft Excel for preprocessing, Tableau for dashboard creation

## ❓ Research Questions Explored

- 📅 How many movies/shows are added monthly to Netflix?
- 🌍 Which country produces the most Netflix content?
- 🎬 Which director has the most Netflix titles?
- ⏱️ What’s the average runtime of a Netflix movie?
- 🕒 How long after release does a title appear on Netflix?
- 👤 Which actor has the most titles on the platform?

## 📈 Dashboard Visuals

The Tableau dashboard includes:
- Map charts for country-level insights
- Tree maps for actor/director frequency
- Bar and line charts for time-based trends
- Pie charts for categorical distributions

## 🧠 Lessons Learned

- Data cleaning and reshaping were critical for accurate visualizations
- Creating modular tables improved Tableau usability and interactivity
- Effective chart selection enhanced clarity and storytelling
- Sorting values in visuals increased intuitive data interpretation


