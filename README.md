# Housing Price Prediction

This project is a simple implementation of a **Linear Regression** model using **scikit-learn** to predict housing prices based on various input features. It includes data preprocessing such as handling missing values, feature scaling, and model evaluation.

## 📁 Dataset

The dataset used is `housing_price_dataset.csv`. It should be a CSV file with features describing houses and a target column representing the house price.

## 📋 Requirements

Install the required Python libraries before running the code:

```bash
pip install numpy pandas matplotlib scikit-learn

## 🚀 How to Run

1. Place `housing_price_dataset.csv` in the same directory as the script.
2. Run the Python script:

```bash
python housing_price_prediction.py
```

## 🧠 Workflow

1. **Load Data**
   Loads the CSV dataset using pandas.

2. **Check Missing Values**
   Prints the number of missing values in each column.

3. **Train-Test Split**
   Splits the data into training and test sets (80-20 split).

4. **Feature Scaling**
   Standardizes the feature values using `StandardScaler`.

5. **Model Training**
   Trains a **Linear Regression** model on the training data.

6. **Prediction**
   Predicts prices for the test set and prints actual vs predicted values.

---

## 🧪 Output

The output will show a side-by-side comparison of the predicted and actual prices:

