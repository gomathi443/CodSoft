## 📌 Project Overview

This project builds a **machine learning model** to predict IMDb movie ratings based on features such as **genre, director, actors, duration, votes, and year of release**.

The goal is to analyze historical IMDb movie data and develop a regression model that accurately estimates the rating given to a movie by users or critics.

---

## 🚀 Features

* Data cleaning and preprocessing (handling missing values, text to numeric conversions).
* Feature engineering (genre simplification, one-hot encoding, categorical handling).
* Regression model training (Linear Regression).
* Evaluation using **Mean Squared Error (MSE)** and **R² Score**.
* Visualization of **Actual vs Predicted ratings**.

---

## 🛠️ Tech Stack

* **Python 3**
* **Pandas, NumPy** → Data manipulation
* **Matplotlib, Seaborn** → Data visualization
* **Scikit-learn** → Machine learning

---

## 📂 Dataset

The dataset used is **IMDb Movies India**, containing details like:

* Movie Name
* Year of Release
* Duration
* Genre
* Rating (target variable)
* Votes
* Director
* Actor 1, Actor 2, Actor 3

---

## 📊 Workflow

1. Load and explore dataset
2. Clean data (Year, Duration, Votes, Genres, etc.)
3. Handle missing values
4. Encode categorical features (Genre, Director, Actor)
5. Train-test split
6. Train regression model (Linear Regression)
7. Evaluate model performance
8. Visualize results

---

## 📈 Results

* The model provides predicted ratings close to actual IMDb ratings.
* Performance measured with:

  * **Mean Squared Error (MSE)**
  * **R² Score**

---
