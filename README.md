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

### 1. Rating vs Price Category
This boxplot shows the relationship between restaurant pricing and ratings. Interestingly, expensive restaurants (>₹500 for two) tend to have slightly higher median ratings.

![Rating vs Price Category](rating_vs_price.png)

### 2. High vs Low Rated Restaurants
Distribution of restaurants based on rating threshold (≥4.0). The majority of restaurants in the dataset have ratings above 4.0, indicating overall good quality.

![High vs Low Rated Restaurants](high_vs_low_rating.png)

### 3. Restaurant Types Distribution
Count of different restaurant types in the dataset. **Dining** restaurants dominate the dataset, followed by **Cafes** and **Buffet** establishments.

![Restaurant Types](restaurant_types.png)

### 4. Votes by Restaurant Type
This line graph shows the total votes received by each restaurant type. **Dining** restaurants receive significantly more votes, indicating higher customer engagement.

![Votes by Restaurant Type](votes_by_type.png)

### 5. Online vs Offline Order Availability
Pie chart showing the distribution of restaurants offering online ordering versus those that don't.

![Online vs Offline Orders](online_vs_offline.png)

### 6. Rating Distribution
Histogram showing the distribution of ratings across all restaurants. Most ratings cluster around 3.5-4.0 range.

![Rating Distribution](rating_distribution.png)

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
