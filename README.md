# 🏏 IPL Cricket Score Predictor

This project predicts the final score of an IPL (Indian Premier League) cricket match using machine learning. By selecting options like venue, batting team, bowling team, striker, and bowler, you can get a predicted final score — just like a virtual commentator!

---

## 🌟 What This Project Does

Imagine you're watching an IPL match and wondering:

> "How many runs will this team score based on who's batting, bowling, and where they're playing?"

This notebook uses historical IPL match data to answer that! It combines machine learning with interactive widgets to predict scores in real-time.

---

## 📂 Project Files

- **`IPL Cricket Score Predictor.ipynb`** – The main notebook with code, model, visualizations, and an interactive prediction UI
- **`ipl_data.csv`** – Historical IPL data used to train the model

---

## 🎯 Features

✅ Clean, interactive dropdowns to select teams, players, and venue  
✅ Predicts the final score dynamically using a trained ML model  
✅ Visualizations: box plots, violin plots, and score distribution analysis  
✅ Fully built in Python using `pandas`, `scikit-learn`, `seaborn`, and `ipywidgets`

---

## 🛠 How to Use

1. Clone or download the repository  
2. Open the Jupyter Notebook (`IPL Cricket Score Predictor.ipynb`)  
3. Run all the cells (make sure you have Python 3.9 and dependencies installed)  
4. Use the dropdowns to choose your match conditions  
5. Click "Predict Score" to see the result!

---

## 🧠 Machine Learning Approach

- **Model**: Linear Regression  
- **Encoding**: LabelEncoder for categorical variables  
- **Scaling**: StandardScaler for input features  
- **Prediction**: Based on venue, batting/bowling teams, and key players

---

## 📊 Insights with Visuals

- **Box plots** showing score variations across venues and teams  
- **Violin plots** highlighting distribution trends  
- **Distribution plot** showing common and outlier scores

---

## 🙌 Credits

Built as a college machine learning project to explore real-world sports analytics using Python.

---

## 💬 Suggestions or Feedback?

If you have ideas to improve this project — like adding player stats or match conditions — feel free to fork it or drop a suggestion!
