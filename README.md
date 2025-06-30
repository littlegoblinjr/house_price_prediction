# 🏡 House Price Prediction using Linear Regression

This project predicts housing prices using the California Housing dataset with a simple linear regression model. The goal is to estimate the median house value based on various socioeconomic and geographic features.

## 📊 Dataset

- Source: Built-in dataset from `sklearn.datasets.fetch_california_housing`
- Target: Median house value (in $100,000s)
- Key features include:
  - `MedInc`: Median income
  - `HouseAge`: Median age of the houses
  - `AveRooms`: Average number of rooms
  - `Population`, `AveOccup`, `Latitude`, `Longitude`

## 🛠️ Technologies Used

- Python
- Jupyter Notebook
- scikit-learn
- pandas
- matplotlib

## 🚀 Usage

1. Load the dataset using `fetch_california_housing()`
2. Fit a linear regression model using scikit-learn
3. Evaluate using Mean Squared Error (MSE)
4. Visualize predictions against actual prices using line plots

## 📈 Output

The notebook displays a comparison between predicted and actual house prices, helping visualize the performance of the regression model.

---
