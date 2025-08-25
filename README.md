# Geospatial Analysis of Housing Prices Using Machine Learning

## Overview  
This project predicts **housing prices** by combining **property-specific features** (rooms, land size, building area) with **geospatial features** such as distances to schools, hospitals, train stations, and CBD, derived using **OSMnx**.  
It demonstrates how property attributes and location together influence real estate values.

---

## Key Highlights  
- Processed and analyzed **10,000+ property records**  
- Built regression models (RandomForest, XGBoost, LightGBM, etc.)  
- Added **geospatial proximity features** using OSMnx & GeoPandas  
- Achieved an **R² score of 0.89** on log-price predictions  
- Applied **SHAP (Explainable AI)** for feature importance and interpretability  

---

## Tech Stack  
- **Python**, **Pandas**, **GeoPandas**, **NumPy**  
- **Scikit-learn**, **XGBoost**, **LightGBM**, **CatBoost**  
- **Matplotlib**, **Seaborn** for visualization  
- **OSMnx**, **Shapely** for geospatial analysis  
- **SHAP** for explainability  
- **Jupyter Notebook**, **GitHub**

---

## Results & Insights  
- Property attributes (Rooms, Landsize, BuildingArea) are the **strongest predictors** of price  
- Location features (distance to CBD, hospitals, schools) show **localized impact** on individual predictions  
- SHAP plots provide **global + local interpretability** of the model’s reasoning  
- Example: A property close to CBD but with fewer rooms had higher price due to location advantage  

---
