# Cognifyz Restaurant Analysis

## Overview
This project analyzes restaurant data to extract meaningful insights into cuisine popularity, city-wise distributions, pricing trends, and customer ratings. The dataset contains details about restaurants, including their locations, cuisines, pricing, ratings, and availability of online delivery and table bookings.

## Dataset
The dataset consists of **9551** entries and **21** features, including:
- Restaurant Name, City, Address, Cuisines
- Average Cost for Two, Price Range, Currency
- Ratings, Votes, Online Delivery Availability, Table Booking Availability

## Key Insights
### **Cuisine Analysis**
- Top 3 most common cuisines:
  - **North Indian (3960 restaurants)**
  - **Chinese (2735 restaurants)**
  - **Fast Food (1986 restaurants)**
- Percentage of restaurants serving top cuisines:
  - North Indian: **41.46%**
  - Chinese: **28.63%**
  - Fast Food: **20.79%**

### **City-Wise Restaurant Distribution**
- **New Delhi** has the highest number of restaurants (**5473**)
- **Top 5 cities by number of restaurants:**
  - New Delhi, Gurgaon, Noida, Faridabad, Ghaziabad
- **City with the highest average rating:** Inner City (**4.90 rating**)

### **Price Range Distribution**
- Price Range 1 (Lowest) is the most common (**46.5%** of restaurants)
- Price Range 4 (Highest) is the least common (**6.13%** of restaurants)

### **Online Delivery & Table Booking**
- **25.66%** of restaurants offer online delivery
- Restaurants with online delivery have an **average rating of 3.25** compared to **2.47** for those without

### **Restaurant Chains**
- Identified **734** restaurant chains
- **Top 5 chains with most outlets:**
  - **Barbeque Nation (83 outlets)**
  - **Bikaner Misthan Bhandar**
  - **Apni Rasoi**
  - **Patiala Shahi**
  - **Pizza Hut**

### **Correlation Analysis**
- **Votes and Ratings have a weak positive correlation (0.31)**
- Higher-rated restaurants generally have more votes

### **Geographical Insights**
- **Mapped all restaurants** based on latitude and longitude using GeoPandas
- Identified clusters of high-density restaurants in major cities

## Tools & Libraries Used
- **Python (pandas, numpy, seaborn, matplotlib, geopandas)**
- **Jupyter Notebook** for analysis and visualization
- **Geopandas & Geodatasets** for geographical mapping

## Future Improvements
- Sentiment analysis on restaurant reviews
- Predicting restaurant success based on features
- Implementing machine learning models for rating predictions
