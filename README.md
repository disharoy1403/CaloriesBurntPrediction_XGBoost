# Calories Burnt Prediction using XGBoost

## 📌 Project Overview
This project predicts the number of calories burned during physical exercise using machine learning.  
An **XGBoost Regressor** model is trained on physiological and exercise-related data such as age, gender, height, weight, exercise duration, heart rate, and body temperature.

The objective is to build an accurate regression model that can estimate calorie expenditure based on user activity and body parameters.

---

## 📊 Dataset Description
The project uses two datasets:

### 1. exercise.csv
Contains user exercise and body-related information:
- User_ID
- Gender
- Age
- Height (cm)
- Weight (kg)
- Duration (minutes)
- Heart_Rate
- Body_Temp (°C)

### 2. calories.csv
Contains:
- User_ID
- Calories (target variable)

Both datasets are merged using `User_ID`.

---

## 🛠️ Technologies Used
- Python
- NumPy
- Pandas
- Matplotlib
- Seaborn
- Scikit-learn
- XGBoost

---

## ⚙️ Data Preprocessing
- Merged exercise and calorie datasets
- Checked for missing values
- Converted categorical feature `Gender` into numerical format
- Performed exploratory data analysis (EDA)
- Visualized distributions and correlations using heatmaps
- Split data into training and testing sets (50% test size)

---

## 📈 Model Used
### XGBoost Regressor
XGBoost is a powerful gradient boosting algorithm known for:
- High accuracy
- Handling non-linear relationships
- Robust performance on structured data

The model was trained using default hyperparameters.

---

## 📉 Model Evaluation
Evaluation Metric Used:
- **Mean Absolute Error (MAE)**

### 🔹 Why MAE Was Chosen
- MAE is easy to interpret and directly represents prediction error in original units.
- It is less sensitive to outliers compared to Mean Squared Error (MSE).
- Suitable for real-world regression tasks where absolute deviation matters.
  
---

## 👩‍💻 Author

Disha Roy
