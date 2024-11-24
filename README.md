# 📊 Statistical Learning and Data Mining Project

## 🔍 Challenge 1 : Regression problem on a small feature map.

## ⚙️ Key Techniques Used
### 📉 Linear regression & KNN:
Interestingly the linear regression model with fature engineering of polynomial feature enahncement outperfromed the knn which was tending to overfit the small dataset.

## 🔍 Challenge 2 :Russian stock mrket classification: (add, remove or hold)
This project focuses on data preprocessing, feature selection, and model training using various machine learning techniques to predict outcomes from a dataset with missing values.

## ⚙️ Key Techniques Used
### 🧹 Data Preprocessing
- **KNN Imputer**: Used K-Nearest Neighbors to impute missing values by averaging the nearest neighbors' values based on the Euclidean distance.

### 📉 Feature Selection
- **LassoCV**: Applied Lasso Regression with cross-validation to automatically tune the hyperparameter (alpha) and select important features for the model.

### 🔢 Feature Engineering
- **Polynomial Features**: Transformed the data with polynomial terms (degree 2) to capture non-linear relationships in the model.

### 🌲 Model:
Random Forest