#  Shanghai Real Estate & POI – PCA Analysis

This project explores the relationship between housing prices and the presence of various types of Points of Interest (POIs) in Shanghai. It was conducted as part of a data and urban planning course at **UTSEUS – Shanghai University**.

The analysis includes spatial filtering, distance calculations using KDTree, and dimensionality reduction using **Principal Component Analysis (PCA)** to uncover the main POI categories influencing housing prices.

---

## 📌 Project Summary

- 🏡 **Dataset**: Real estate listings from Anjuke (2017), cleaned and geo-referenced  
- 📍 **POI Data**: 2017 dataset from Gaode, with 300+ types of urban features  
- 📏 **Distance analysis**: Calculated distance from each housing point to all POI categories  
- 📉 **PCA**: Reduced dimensionality of hundreds of POI distances to find the strongest factors  
- 📊 **Visuals**: PCA scatter plots, feature contributions, explained variance

---

## 🛠️ Tools & Libraries

- Python, Pandas, GeoPandas  
- Scikit-learn (PCA, KDTree), Matplotlib, Seaborn  
- Spatial filtering using bounding boxes  
- Data transformation and feature engineering

---

## 📄 Full Report

📥 [Click here to read the full project report (PDF)](./report/PCA-Ghali_ Thalia.pdf)

---

## ✨ Key Takeaways

- Housing prices in Shanghai correlate strongly with proximity to specific POIs (e.g., consulates, commercial zones, transportation hubs).
- PCA helped reduce the complexity of hundreds of POI features into meaningful components.
- Urban spatial data can provide valuable insights into market dynamics and infrastructure planning.

---

## 📁 Repo Structure


