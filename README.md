# 🏏 IPL Score Prediction using Machine Learning

A web-based machine learning application built with Flask that predicts the **first innings score** in IPL cricket matches based on real-time input like batting team, bowling team, current score, overs, wickets, and previous performance.

---

## 🚀 Overview

This project uses a trained **Linear Regression model** (stored as a `.pkl` file) to predict the final score of a team batting first in an IPL match. The application takes match details from the user and returns an estimated **score range**.

---

## 🧠 Machine Learning Model

- ✅ Model Type: Linear Regression (or Random Forest, based on your `.pkl`)
- 🎯 Target: First innings final score
- 🧾 Features Used:
  - Batting team
  - Bowling team
  - Overs completed
  - Current runs
  - Wickets fallen
  - Runs scored in last 5 overs
  - Wickets fallen in last 5 overs

---

## 💻 Tech Stack

| Component   | Technology     |
|-------------|----------------|
| Backend     | Python, Flask  |
| ML Model    | Scikit-learn   |
| Frontend    | HTML, CSS (via Flask templates) |
| Deployment  | Localhost / Render |

---
