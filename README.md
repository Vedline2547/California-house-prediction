# 🏠 California House Price Prediction Using Linear Regression

## 📌 Project Overview

This project uses **Machine Learning** to predict California house values using the **California Housing dataset** provided by Scikit-learn.

A **Linear Regression** model is trained to learn the relationship between housing characteristics and median house values. The project demonstrates a complete machine learning workflow, from loading and preparing data to training, evaluating, and making predictions on new data.

## 🎯 Objectives

* Load and explore the California Housing dataset
* Separate features and target variables
* Split the dataset into training and testing sets
* Train a Linear Regression model
* Evaluate model performance
* Analyze model coefficients
* Make predictions for new housing data
* Visualize actual vs predicted house values

## 📊 Dataset

The project uses the **California Housing dataset** available through `sklearn.datasets`.

### Features

| Feature      | Description                 |
| ------------ | --------------------------- |
| `MedInc`     | Median income in the block  |
| `HouseAge`   | Median house age            |
| `AveRooms`   | Average number of rooms     |
| `AveBedrms`  | Average number of bedrooms  |
| `Population` | Block population            |
| `AveOccup`   | Average household occupancy |
| `Latitude`   | Geographic latitude         |
| `Longitude`  | Geographic longitude        |

### Target

`MedHouseVal` — Median house value for the California housing block.

## 🛠️ Technologies Used

* **Python**
* **Pandas**
* **NumPy**
* **Scikit-learn**
* **Matplotlib**

## 🔄 Machine Learning Workflow

The project follows these steps:

1. Load the California Housing dataset
2. Explore the dataset
3. Separate features (`X`) and target (`y`)
4. Split data into training and testing sets
5. Train a Linear Regression model
6. Generate predictions
7. Evaluate the model using:

   * Mean Squared Error (MSE)
   * R² Score
8. Examine model coefficients
9. Predict the value of a new property
10. Visualize actual vs predicted values

## 📈 Model Performance

The Linear Regression model achieved:

* **Mean Squared Error (MSE):** 0.5559
* **R² Score:** 0.5758

The R² score indicates that the model explains approximately **57.6% of the variation** in the target house values.

## 📊 Visualization

An **Actual vs Predicted House Values** scatter plot is included to visually compare the model's predictions with the actual values.

A model performing well would generally have predictions concentrated around the diagonal relationship between actual and predicted values.

## 🏡 New House Prediction

The trained model is also tested with new housing characteristics, including:

* Median income
* House age
* Average rooms
* Average bedrooms
* Population
* Average occupancy
* Latitude
* Longitude

The model uses these characteristics to generate a predicted house value.

## 📂 Project Structure

```text
California-House-Price-Prediction/
│
├── main.py
├── README.md
├── requirements.txt
```

## ▶️ How to Run

### 1. Clone the repository

```bash
git clone https://github.com/Vedline2547/California-House-Price-Prediction.git
```

### 2. Navigate to the project directory

```bash
cd California-House-Price-Prediction
```

### 3. Install the required libraries

```bash
pip install pandas numpy scikit-learn matplotlib
```

### 4. Run the Python script

```bash
python main.py
```

## 💡 Key Skills Demonstrated

* Data Loading
* Data Exploration
* Data Preprocessing
* Feature and Target Separation
* Train-Test Splitting
* Linear Regression
* Model Evaluation
* Model Interpretation
* Data Visualization
* Making Predictions with Machine Learning

## 🚀 Future Improvements

Possible improvements include:

* Comparing Linear Regression with Random Forest and Gradient Boosting
* Feature scaling and engineering
* Hyperparameter tuning
* Cross-validation
* Additional exploratory data analysis
* Comparing multiple regression models
* Improving prediction performance

## 👨‍💻 Author

**Vedline Ochieng**

Civil Engineering Student • Machine Learning Enthusiast • Python Developer • Future AI Engineer

---

⭐ If you found this project useful, consider giving the repository a star!
