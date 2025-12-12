# 🍽️ Zomato Restaurant Analytics (EDA & Statistics Project)

## 📌 Project Overview
Understanding customer preferences and restaurant performance is critical for food delivery platforms.  
This project performs **Exploratory Data Analysis (EDA)** on a Zomato restaurant dataset to uncover insights related to **pricing, ratings, restaurant types, and online ordering behavior**, supported by **statistical validation**.

---

## 🎯 Objectives
- Analyze customer preferences across restaurant types  
- Study pricing trends and preferred cost ranges  
- Compare ratings for online vs offline ordering  
- Validate insights using statistical hypothesis testing  
- Generate actionable business insights for food delivery platforms  

---

## 🗂️ Dataset
- Source: Zomato restaurant dataset  
- Size: ~150 restaurant records  
- Key Features:
  - `name`
  - `rate`
  - `votes`
  - `online_order`
  - `listed_in(type)`
  - `approx_cost(for two people)`

---

## 🛠️ Tech Stack
- **Programming Language:** Python  
- **Libraries:** Pandas, NumPy, Matplotlib, Seaborn  
- **Statistics:** SciPy (Hypothesis Testing)  
- **Environment:** Jupyter Notebook / Google Colab  

---

## 🔍 Key Analysis Steps

### 1️⃣ Data Cleaning & Preprocessing
- Handled inconsistent rating formats (`NEW`, `-`, `3.8/5`)
- Converted ratings into numerical values
- Checked and treated missing values
- Processed categorical variables for analysis

---

### 2️⃣ Exploratory Data Analysis (EDA)
- Restaurant type distribution analysis
- Online vs offline order availability
- Rating distribution and popularity trends
- Cost preference analysis for couples

---

### 3️⃣ Feature Engineering
- Created cost-based and rating-based features
- Categorized restaurants by expense level
- Identified high-rated vs low-rated restaurants

---

### 4️⃣ Statistical Hypothesis Testing
- **Test Used:** Two-sample t-test  
- **Objective:** Compare ratings of online-order vs offline restaurants  

**Results:**
- T-statistic = 6.11  
- P-value = 8.39 × 10⁻⁹  

**Conclusion:**  
Restaurants offering online ordering have **statistically significantly higher ratings** (p < 0.001).

---

## 📊 Visualizations
- Count plots for restaurant types and order modes  
- Boxplots for rating comparison  
- Histograms for rating distribution  
- Heatmaps showing order preference by restaurant type  

---

## 📈 Key Insights
- Online-order restaurants receive significantly higher ratings  
- Dining restaurants are preferred for offline visits  
- Cafes show higher online-order adoption  
- Most couples prefer restaurants priced around ₹300–₹400  
- Higher votes generally correlate with better ratings  

---

## 💡 Business Impact
- Helps food delivery platforms identify high-potential restaurants  
- Supports online-order adoption strategies  
- Assists restaurants in pricing and service optimization  
- Demonstrates data-driven decision-making using EDA and statistics  

---

## 🚀 Future Enhancements
- Build machine learning models for rating prediction  
- Develop a restaurant recommendation system  
- Create an interactive dashboard using Streamlit or Power BI  
- Expand analysis with larger multi-city datasets  

---
