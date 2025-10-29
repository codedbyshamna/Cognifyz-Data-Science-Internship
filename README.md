# 🧠 Data Science Internship Project – Cognifyz Technologies

## 📌 Overview
This repository contains the **Data Science Internship Project** completed at **Cognifyz Technologies**.  
The project focuses on performing **data analysis, visualization, and predictive modeling** on a restaurant dataset to extract meaningful business insights.

Through this internship, I explored various stages of the data science workflow, including **data preprocessing, feature engineering, exploratory data analysis (EDA), and simple machine learning modeling**.

---

## 🎯 Objectives
- To clean, preprocess, and analyze a real-world dataset.
- To visualize customer behavior and restaurant trends using Python.
- To identify relationships between features like price range, ratings, and delivery options.
- To build a simple predictive model for restaurant ratings.
- To present insights and conclusions through visualizations.

---

## 📂 Dataset Description
**Dataset Name:** `Dataset.csv`

| Column Name | Description |
|--------------|-------------|
| Restaurant Name | Name of the restaurant |
| City | City where the restaurant is located |
| Country Code | Numeric code representing the country |
| Cuisines | Type(s) of cuisine served |
| Aggregate rating | Overall customer rating |
| Votes | Number of customer votes |
| Price range | Price category (1=Low, 4=High) |
| Has Table booking | Indicates if table booking is available |
| Has Online delivery | Indicates if online delivery is available |
| Is delivering now | Shows if the restaurant is delivering currently |
| Latitude / Longitude | Geographical location |
| Address | Full address of the restaurant |

---

## 🧰 Tools & Technologies Used
- **Python**  
  Libraries: `pandas`, `numpy`, `matplotlib`, `seaborn`, `folium`, `sklearn`
- **Google Colab** for coding and visualization
- **GitHub** for project documentation and version control

---

## 📊 Key Modules & Analysis Performed

### 🔹 1. Data Exploration and Cleaning
- Loaded and inspected data
- Handled missing values
- Converted data types for consistency

### 🔹 2. Descriptive & Statistical Analysis
- Calculated mean, median, standard deviation
- Identified top cuisines and most popular cities

### 🔹 3. Geospatial Analysis
- Used **Folium** maps to visualize restaurant distribution by latitude and longitude
- Analyzed top cities and countries by restaurant count

### 🔹 4. Booking & Delivery Insights
- Compared ratings of restaurants with/without online delivery and table booking
- Found that restaurants with these services often had higher ratings

### 🔹 5. Price Range Analysis
- Analyzed how pricing affects restaurant ratings
- Found that higher price ranges generally correspond to better-rated restaurants

### 🔹 6. Predictive Modeling
- Built a **Linear Regression Model** using:
  - Table booking availability
  - Online delivery option
  - Cuisines and city
  - Name and address length
- Evaluated model performance using MSE and R² score

### 🔹 7. Customer Preference Analysis
- Identified top cuisines by average rating and vote count
- Visualized relationships between cuisine popularity and customer satisfaction

---

## 📈 Key Insights
- Restaurants offering **online delivery** and **table booking** have higher customer ratings.  
- **Social and popular cuisines** (like North Indian, Italian, Chinese) are top-rated.  
- **Price Range 4 (Expensive)** restaurants tend to receive better average ratings.  
- Top-rated cities show higher customer engagement and satisfaction.  
