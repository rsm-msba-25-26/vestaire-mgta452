<link rel="stylesheet" href="style.css">


# Vestaire Secondhand Fashion Project

Welcome to our MGTA 452 Project Site! Use the links below to navigate through our dashboards and predictive model!

- [Dashboards](dashboards.html)
- [Predictive Model](model.md)
- [EDA](eda.md) 

--- 

## Project Overview

This project explores the secondhand luxury fashion market using ~900,000 listings from Vestiaire Collective. We analyze:

- Brand-level resale value  
- Condition and category effects  
- Seller reputation and popularity signals  
- Predictive modeling of resale price

Our goal was to understand and explore what drives price in the secondhand luxury market through interactive dashboards and predictive modeling. 


## Dataset Overview
The dataset contains approximately 900,000 listings from Vestiaire Collective, each representing a secondhand fashion item offered for resale. Each row corresponds to one product listing along with its associated seller and marketplace attributes.

The data includes detailed information about the item (brand, category, condition, materials), its pricing structure, its popularity among users, and descriptive statistics about the seller. The dataset provides enough depth to examine relationships between product characteristics and resale prices, as well as to build models that predict pricing outcomes.

It was scraped using Python and the Hrequests Library. The CSV file contains approximately 900k rows and 36 columns.


### Key Variables
Below is a breakdown of the most important variable groups included in the dataset that we utilize for our analysis and visualizations.

**A. Product Characteristics**

These describe intrinsic attributes of the fashion item:

* brand_name – Luxury brand (e.g., Chanel, Gucci, Dior).

* product_type – High-level category (e.g., handbags, shoes, accessories).

* product_category – Detailed category (e.g., shoulder bags, sneakers, boots).

* product_gender_target – Intended gender target (men, women, unisex).

* product_material – Material composition (leather, denim, wool, etc.).

* product_color – Dominant color of the item.

* product_condition – Qualitative condition rating (e.g., “Very Good”, “Good”).

* product_season – Collection season for seasonal products.

These features are central for resale pricing analysis because they represent core product attributes visible to buyers.

**B. Pricing & Financial Structure**

Vestiaire uses a combination of seller input, platform fees, and shipping rules to determine how much a buyer pays and how much a seller receives.

The dataset includes:

* price_usd – Listing price converted to USD.

* seller_price – Price set by the seller before platform fees.

* seller_earning – Amount the seller receives after fees.

* buyers_fees – Platform fees added to the buyer’s price.

* has_cross_border_fees – Whether international costs apply.

These fields help us study the economics of resale and how platform costs influence item prices.

**C. Popularity & Buyer Interest**

These variables capture marketplace demand signals:

* product_like_count – Number of likes the listing has received.

* product_has_pictures – Indicates whether the listing includes photos.

* reserved, sold, available, in_stock – Listing status indicators.

Engagement metrics such as likes can help explain trends in popularity and demand.

**D. Seller Information**

Understanding seller behavior and reputation is key in resale markets. Seller-level variables include:

* seller_country – Country where the seller is located.

* seller_products_sold – Total historical sales by the seller.

* seller_num_products_listed – Number of items currently listed.

* seller_num_followers – Seller’s follower count.

* seller_pass_rate – Percentage of listings approved by moderators.

* seller_community_rank – Vestiaire’s rating of seller trust or activity.

These features allow us to analyze whether seller credibility affects resale prices.

## Limitations

While the dataset is rich, several constraints must be noted:

Listing prices are not actual sale prices — some items may not have sold at the listed amount.

The platform focuses on luxury fashion, which may not generalize to lower-priced secondhand markets.

Some fields are inconsistently filled (e.g., descriptions, materials), requiring cleaning or imputation.

Temporal data is limited, reducing the ability to analyze time-based trends.

Despite these limitations, the dataset is sufficiently large and diverse to support robust modeling and market analysis.

## Purpose of This Project

Using this dataset, the project aims to:

1. Visualize key trends in resale value by brand, category, and condition.

2. Analyze how item characteristics and seller attributes influence price and popularity.

3. Build a predictive model for estimating resale prices.

4. Create a final dashboard that communicates these insights in a clear and compelling way.


## Key Findings
- Luxury brands like Chanel, Gucci, and Louis Vuitton retain the highest resale value.  
- Condition strongly influences price, especially for handbags and shoes.  
- Our Random Forest model predicts resale price with solid accuracy and highlights brand/condition as the top predictors.


Explore our dashboards and model details using the links above!
