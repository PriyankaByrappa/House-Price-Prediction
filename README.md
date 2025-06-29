# 🏠 House Price Prediction using Linear Regression

## 📌 Project Overview

This machine learning project predicts house prices based on various features such as the number of rooms, percentage of lower-income population, and student-teacher ratio. It uses **Linear Regression**, a fundamental supervised learning algorithm, to estimate housing prices.

The project is implemented using **Python in Google Colab**, featuring data visualization, model training, evaluation, and performance metrics.

---

## 📁 Dataset

- **File Name**: `housing.csv`  
- **Source**: Provided by internship / UCI ML Repository / Kaggle  
- **Target Variable**: `MEDV` – Median value of owner-occupied homes (in $1000s)  
- **Features** (examples):
  - `RM`: Average number of rooms per dwelling
  - `LSTAT`: Percentage of lower-income population
  - `PTRATIO`: Pupil-teacher ratio by town
  - *(More depending on dataset)*

---

## 🔧 Technologies Used

- Python 3
- Google Colab
- Libraries:
  - `pandas`
  - `numpy`
  - `scikit-learn`
  - `matplotlib`
  - `seaborn`

---

## 📈 ML Model Used

### Linear Regression
- A basic regression technique used to model the relationship between features and the target price.
- Evaluated using:
  - Mean Squared Error (MSE)
  - R² Score (coefficient of determination)

---

## 🚀 Project Workflow

1. Load and explore the dataset
2. Clean and preprocess data (handle missing values if any)
3. Visualize feature relationships using scatter plots, heatmaps
4. Select relevant features for prediction
5. Split data into training and testing sets
6. Train the model using Linear Regression
7. Evaluate model performance using:
   - Mean Squared Error (MSE)
   - R² Score
8. Visualize predictions using actual vs. predicted plot

---

## 📊 Results

| Metric | Value |
|--------|-------|
| Mean Squared Error (MSE) | ~24.29 |
| R² Score (Accuracy)       | ~0.73  |

> *Note: These results may vary depending on the dataset and feature selection.*

---

## 📌 How to Run

> You can open this project in [Google Colab](https://colab.research.google.com) and run all cells interactively.

### 🔗 Notebook Link:
[👉 Click here to view in Colab](#) <!-- (Replace # with actual Colab link) -->

---

## 📷 Sample Outputs

> ![{E6F80E29-624B-4A30-990C-20F9FB7CAB30}](https://github.com/user-attachments/assets/7e92e822-76ea-4867-aeb0-a8ae1b813dcd)


---

## 🧾 License

This project was created as part of a Python + Machine Learning internship. Educational use only.

---

## 🙋‍♀️ Author

**Priyanka Byrappa B**  
*Intern - Python & Machine Learning*

---

## ⭐ Optional Sections to Add

- `requirements.txt` (for local Python environments)
- `GUI version` using Tkinter
- `Flask or Streamlit web app` for deployment

---
