## 🧠 Linear Regression Intuition

Linear Regression models the relationship between the target variable and features as a straight line (or hyperplane in higher dimensions)--

in more sophisticated way...

Linear Regression is a fundamental supervised learning algorithm used for modeling the relationship between a dependent variable and one or more independent variables. It assumes that this relationship is linear, meaning it can be represented as a straight line in a multidimensional space.

```
target = b0 + b1 * feature1 + b2 * feature2 + ... + error
```

Where:
- `b0` is the intercept
- `b1`, `b2`, ... are the coefficients (slopes)
- The goal is to minimize the prediction error

---

## 🚀 Steps Covered in the Notebooks

1. **Load and Explore the Dataset**
2. **Preprocess the Data**
3. **Split into Training and Test Sets**
4. **Train a Linear Regression Model**
5. **Evaluate Model Performance**
6. **Visualize Predictions**

Each notebook is well-commented and walks you through the process from data loading to model evaluation.

---


# 🏡 California Housing & Diabetes Regression with Linear Regression

This project demonstrates how to apply **Linear Regression** to two classic regression problems using Scikit-Learn datasets:

- **California Housing Price Prediction**
- **Diabetes Progression Prediction**

Both examples are great starting points to understand regression modeling in machine learning.

---

## 📂 Datasets Overview

### 1. California Housing Dataset

- **Source:** 1990 California census data.
- **Goal:** Predict the **Median House Value** (`MedHouseVal`) for California districts based on features like income, house age, rooms, and location.

| Feature       | Description                                |
|---------------|--------------------------------------------|
| `MedInc`      | Median income in a block                   |
| `HouseAge`    | Median house age                           |
| `AveRooms`    | Average number of rooms per household      |
| `AveOccup`    | Average household occupancy                |
| `Latitude`    | Geographical latitude                      |
| `Longitude`   | Geographical longitude                     |
| `MedHouseVal` | Median house value (Target Variable)       |

---

### 2. Diabetes Dataset

- **Source:** Diabetes patient data from a medical study.
- **Goal:** Predict a quantitative measure of disease progression one year after baseline, based on physiological variables.

| Feature      | Description                                 |
|--------------|---------------------------------------------|
| `age`        | Age in years                                |
| `sex`        | Sex                                         |
| `bmi`        | Body mass index                             |
| `bp`         | Average blood pressure                      |
| `s1`-`s6`    | Various blood serum measurements            |
| `target`     | Disease progression after one year (Target) |

---

## 🎯 Problem Statements

### California Housing

> **Predict the Median House Value (`MedHouseVal`) for a district using features such as income, house age, rooms, and location.**

This is a **supervised regression problem** where the goal is to estimate house prices based on district-level features.

### Diabetes

> **Predict the progression of diabetes disease (`target`) one year after baseline using physiological variables.**

This is also a **supervised regression problem** focused on medical data.

---

## 📈 Results

- **California Housing:** Predicts median house values with reasonable accuracy using linear regression.
- **Diabetes:** Estimates disease progression scores based on patient data.

---

## 📝 Try It Yourself!

Clone the repository and run the notebooks in the `challenge/day01` folder to get hands-on experience with regression modeling.

---