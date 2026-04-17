# 📍 PokéStops & Restaurant Traffic: A Statistical Analysis

![Python](https://img.shields.io/badge/Python-Used-blue)
![Data Analysis](https://img.shields.io/badge/Type-Statistical%20Analysis-orange)
![Visualization](https://img.shields.io/badge/Visualization-Heatmaps%20%26%20EDA-green)
![Status](https://img.shields.io/badge/Status-Completed-brightgreen)

---

## 📌 Overview
This project investigates the **impact of PokéStop locations on nearby restaurant activity**, using Yelp check-ins as a proxy for customer foot traffic.

The release of *Pokémon GO* in 2016 introduced location-based gameplay elements such as **PokéStops** and **Gyms**, which encouraged players to move through real-world environments. This raised an important question:  

👉 *Do PokéStops influence consumer behavior and increase traffic to nearby businesses?*

To answer this, we analyze Yelp check-in data over time, comparing restaurants located near PokéStops to those farther away.

## 🎥 Presentation
View the full project presentation here:  
https://canva.link/5ek0qy6puzpox4m

---

## 👥 Authors
- Yasushi Oh  
- Nancy Shen  
- Taggert Smith  
- Katelyn Villamin  

---

## 🎯 Objectives
- Evaluate whether PokéStops increase **restaurant foot traffic**  
- Compare check-in trends between **nearby vs. distant restaurants**  
- Apply statistical methods to assess **causal impact**  
- Visualize spatial and temporal patterns in the data  

---

## 📊 Results at a Glance

- 📈 **Positive Trend:** Restaurants near PokéStops show a slight increase in Yelp check-ins  
- ⚖️ **Not Statistically Significant:** The observed effect is not strong enough to confirm causality  
- 🗺️ **Spatial Patterns:** Heatmaps suggest localized increases in activity near PokéStops  
- 📊 **Potential Relationship:** Results indicate a possible link between game locations and real-world behavior  

👉 Overall, PokéStops may influence foot traffic, but **larger datasets and deeper analysis are needed to confirm the effect**.

---

## 🔍 Methodology

### 1. Data Collection
- Yelp check-in data for restaurants  
- PokéStop location data  

### 2. Exploratory Data Analysis (EDA)
- Visualized check-in trends over time  
- Compared distributions of nearby vs. distant restaurants  

### 3. Heatmap Visualization
- Mapped geographic concentration of check-ins  
- Identified spatial relationships between PokéStops and restaurants  

### 4. Difference-in-Difference Analysis
- Compared changes in check-ins before and after Pokémon GO release  
- Evaluated relative differences between treatment (near PokéStops) and control groups  

---

## 🗂️ Project Structure

```
pokestops-analysis/
├── data/                     # Yelp and PokéStop datasets
├── notebooks/               # Analysis notebooks (EDA, modeling)
├── scripts/                 # Data processing and analysis code
├── visualizations/          # Heatmaps and plots
└── README.md                # Project documentation
```
 
 ---

## 🔍 Key Insights
- PokéStops may contribute to **increased local foot traffic**, but the effect is modest  
- The lack of statistical significance suggests **high variability or insufficient sample size**  
- Location-based games can influence **real-world movement patterns**, but effects are complex  
- External factors (e.g., urban density, restaurant popularity) likely play a significant role  
---

## 🔮 Future Work
- Expand dataset to include **more cities and longer timeframes**  
- Control for confounding variables such as **population density and business popularity**  
- Apply more advanced causal inference techniques  
- Analyze other business types (e.g., retail, cafes)  
- Investigate long-term vs. short-term effects of location-based games  


