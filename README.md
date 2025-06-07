# 🍽️ Restaurant_Customer_Ratings

Welcome to the **Restaurant Customer Ratings** project!  
This project explores what makes restaurants popular and how different factors affect their ratings.

---

## 🔍 Project Purpose

Customer reviews are crucial in the food industry. This project aims to:
- Understand how service options (like online delivery or table booking), location, and food types affect customer ratings.
- Find patterns in restaurant data that predict high or low ratings.
- Use machine learning to build a model that can estimate a restaurant’s customer rating.

---

## 📊 What's Inside the Dataset?

The dataset includes **9551 restaurants** from different cities and countries.  
Each entry includes:

- 🍱 **Cuisines** offered  
- 🏙️ **City and location coordinates**  
- 💵 **Average cost for two**  
- 📦 **Online delivery / Table booking availability**  
- ⭐ **Aggregate rating** (our target for prediction)  
- 🎯 **Customer votes and reviews**

---

## 🧹 What Did (Step-by-Step)

### 1. **Data Cleaning**
- Removed missing and duplicate values.
- Dropped unnecessary columns (like long addresses or IDs).

### 2. **Exploratory Data Analysis (EDA)**
- Found top cuisines and cities.
- Checked how price range and services affect customer ratings.
- Visualized insights using bar plots, pie charts, and heatmaps.

### 3. **Feature Engineering**
- Created new features like address length.
- Converted categorical columns using one-hot encoding.

### 4. **Model Building**
We tried 3 machine learning models to predict the customer rating:
- Linear Regression ✅ (Best: R² = 0.95)
- Decision Tree Regressor
- Random Forest Regressor

### 5. **Model Saving**
- The best model was saved using `joblib` for future use.

---

## 💡 Key Insights

- **New Delhi** has the most restaurants.
- **North Indian cuisine** is the most common but not the highest rated.
- **Online delivery** and **table booking** positively impact ratings.
- **Higher prices often mean higher ratings**.
- Top-rated cuisines include **Modern Indian**, **Seafood**, and **Thai**.

## 🛠️ Tools & Technologies Used

* Python 3
* Google Colab
* pandas, numpy
* matplotlib, seaborn
* plotly.express
* scikit-learn (for regression model)

## 📁 Files Included

* restaurant_analysis.ipynb – Main notebook with code and visuals
* dataset.csv – Dataset file (uploaded manually in Colab)
* README.md – Project overview

## 👩‍💻 Author
Zahadana Haneef Thundhakkachi
Data Analyst


