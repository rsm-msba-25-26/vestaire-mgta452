# Vestaire Second Hand Fashion Market Analysis
MGTA 452 Final Project
Team: Sophia Salas, Anissa Chan, Jie Geng

---

## Project Overview

This project analyzes **900,000+ secondhand luxury fashion listings** from Vestiaire Collective to understand **what drives resale price**. We explore:

- Brand- and category-level pricing patterns  
- The impact of item condition on resale value  
- Predictive modeling of resale price 
- Interactive dashboards for visual analytics

By combining Exploratory Data Analysis (EDA), visualization, and predictive modeling, our goal is to uncover key drivers of price in the secondhand luxury market.

**Live GitHub Pages site:**  
https://rsm-msba-25-26.github.io/vestaire-mgta452/

---

## Dashboards Overview

We built three interactive dashboards using Tableau:

1. **Brand & Market Overview**  
   - Top brands  
   - Global price map  
   - Brand-level listing volume  
   - Price distribution by region

2. **Condition & Category Dashboard**  
   - Condition insights  
   - Price heatmaps for category × condition  
   - Category-level comparisons

3. **Seller & Popularity Patterns**  
   - Average price by country
   - Total likes by country
   - Total like count effect on average price

View all dashboards here:  
https://rsm-msba-25-26.github.io/vestaire-mgta452/dashboards.md

---

## Predictive Modeling

We model **log(price_usd)** using:

- Product features  
- Seller reputation metrics  
- Popularity indicators (like count, sold status)  
- Fees and platform economics  
- Category and brand dummy variables  

### Models implemented:
- **Linear Regression (baseline)**
- **Random Forest Regression (improved model)**

We evaluate models using:

- RMSE (log scale and price scale)
- R²
- Cross-validation

The Random Forest achieved the strongest performance and was used to extract **feature importances**.

Full modeling results:  
https://rsm-msba-25-26.github.io/vestaire-mgta452/model.md

---
