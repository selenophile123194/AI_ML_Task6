# Task: House Price Prediction Analysis

## 📌 Objective
The objective of this task is to develop a machine learning model that predicts house prices based on various property features such as size, number of bedrooms, bathrooms, and location.  
The analysis also aims to explore relationships between property characteristics and price trends.

---

## 📂 Dataset
- **Source:** Kaggle – House Price Prediction Dataset  
  🔗 [https://www.kaggle.com/datasets/shree1992/housedata](https://www.kaggle.com/datasets/shree1992/housedata)
- **Format:** CSV
- **Key Features:**
  - `sqft_living` – Living space area in square feet
  - `bedrooms` – Number of bedrooms
  - `bathrooms` – Number of bathrooms
  - `floors` – Number of floors
  - `waterfront` – Whether the house has a waterfront view
  - `view` – House view rating
  - `condition` – Condition rating
  - `grade` – Overall grade
  - `price` – Target variable (House Price)

---

## 🛠 Steps Performed
1. **Data Loading & Preprocessing**
   - Loaded dataset using Pandas
   - Handled missing values (if any)
   - Converted categorical features to numerical format
   - Applied feature scaling for better model performance

2. **Exploratory Data Analysis (EDA)**
   - Visualized feature distributions
   - Examined correlations using heatmaps
   - Analyzed price trends for different features (e.g., bedrooms, location)

3. **Model Training**
   - Implemented **Linear Regression** and **Gradient Boosting** models
   - Split dataset into training and test sets (80/20)
   - Tuned hyperparameters for optimal performance

4. **Evaluation**
   - Evaluated models using:
     - **Mean Absolute Error (MAE)**
     - **Root Mean Squared Error (RMSE)**
   - Compared predicted prices with actual prices using scatter plots

---

## 📊 Key Results
- **Best Performing Model:** Gradient Boosting Regressor
- **Performance Metrics:**
  - MAE: *~X,XXX* (to be updated with your actual value)
  - RMSE: *~X,XXX* (to be updated with your actual value)
- **Insights:**
  - Waterfront properties have significantly higher prices
  - Larger living area correlates strongly with higher prices
  - Location and condition ratings are strong predictors

---

## 📷 Sample Visualization
```plaintext
Price vs. Square Footage → Positive correlation
Heatmap of feature correlations → Waterfront, sqft_living, and grade have the highest correlation with price
Predicted vs. Actual Price → Most points align closely with the diagonal line, showing good predictions
