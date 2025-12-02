# Vestiaire Secondhand Fashion Market Analysis  
MGTA 452 – Final Project  
**Team:** Sophia Salas, Anissa Chan, Jie Geng  

---

## Project Overview

This project analyzes **900,000+ secondhand luxury fashion listings** from Vestiaire Collective to understand the key factors that **drive resale prices** in the growing luxury resale marketplace. Our analysis explores:

- Brand- and category-level pricing patterns  
- The impact of product condition on resale value  
- Country-level pricing insights  
- Popularity metrics such as total likes  
- Predictive modeling to estimate resale price  
- Interactive dashboards for visual analytics  

Through Exploratory Data Analysis (EDA), Tableau dashboards, and machine learning modeling, we aim to uncover how product, seller, and market characteristics influence secondhand fashion pricing.

🔗 **Live Project Website (GitHub Pages):**  
https://rsm-msba-25-26.github.io/vestiaire-mgta452/

---

## Dashboards Overview

We developed several interactive dashboards using Tableau Public to visualize patterns in the Vestiaire dataset.

### **1. Brand & Market Overview**
- Brand-level resale performance  
- Global average price patterns  
- Market-wide pricing distribution  

### **2. Condition, Likes & Category Dashboard**
- How price varies by condition  
- Relationship between likes and resale value  
- Category-level pricing behavior  

### **3. Country-Level Insights**
- Average price by country  
- Average likes by country  
- Geographic patterns in resale behavior  

---

## Predictive Modeling

We build machine learning models to predict **log(price_usd)** based on:

- Product features (brand, category, material, color, season)  
- Condition and popularity indicators (like counts, sold status)  
- Seller reputation metrics (followers, products sold, pass rate)  
- Platform fee and pricing structure variables  

### **Models Implemented**
- **Linear Regression (Baseline)**  
- **Random Forest Regression (Improved Model)**

### **Evaluation Metrics**
- RMSE (log scale and converted price scale)  
- R² (model fit)  
- Cross-validation performance  

The **Random Forest model** achieved the strongest predictive performance and provided interpretable **feature importance** rankings, highlighting key contributors to resale price.


---

