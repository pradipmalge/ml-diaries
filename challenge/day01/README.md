# 🏡 California Housing Price Prediction using Linear Regression

This project demonstrates how to apply **Linear Regression** to predict **California housing prices** using the **California Housing Dataset** from Scikit-Learn. It’s a great starting point to understand regression modeling in machine learning.

---

## 📂 Dataset Overview

The dataset is based on data from the 1990 California census and includes housing information for various districts in California.

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

## 🎯 Problem Statement

> Predict the **Median House Value** (`MedHouseVal`) using other available features.

This is a **supervised regression problem**, and we’ll use **Linear Regression** as the baseline model.

---

## 🧠 Linear Regression Intuition

Linear Regression models the relationship between the target (`MedHouseVal`) and features as a straight line (or hyperplane in higher dimensions):

MedHouseVal = b0 + b1 * MedInc + b2 * HouseAge + ... + error

Where:
- `b0` is the intercept
- `b1`, `b2`, ... are the coefficients (slopes)
- The goal is to minimize the prediction error