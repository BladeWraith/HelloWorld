# 🏏 IPL Win Probability Predictor

A Machine Learning project that predicts the probability of the chasing team winning an IPL match based on the current match situation. The model uses historical IPL ball-by-ball data and match statistics to estimate win probabilities in real time.

---

## 📌 Project Overview

This project applies Machine Learning techniques to IPL match data to predict the likelihood of the batting team winning during the second innings.

The prediction is based on important match parameters such as:

* Batting Team
* Bowling Team
* Host City
* Target Score
* Current Score
* Overs Completed
* Wickets Remaining
* Current Run Rate (CRR)
* Required Run Rate (RRR)

---

## 🚀 Features

* Data preprocessing and cleaning
* Feature engineering from ball-by-ball IPL data
* Team name standardization
* Removal of discontinued teams and D/L affected matches
* Machine Learning classification model
* Real-time win probability prediction
* Model evaluation using standard classification metrics

---

## 🛠️ Tech Stack

* Python
* Pandas
* NumPy
* Scikit-learn
* Matplotlib
* Google Colab

---

## 📂 Dataset

The project uses two IPL datasets:

* `matches.csv`
* `deliveries.csv`

These datasets contain historical IPL match information and ball-by-ball delivery records.

---

## ⚙️ Machine Learning Workflow

1. Data Collection
2. Data Cleaning
3. Feature Engineering
4. Exploratory Data Analysis (EDA)
5. Model Training
6. Model Evaluation
7. Win Probability Prediction

---

## 📊 Model Evaluation

The model was evaluated using standard Machine Learning metrics including:

* Accuracy
* Confusion Matrix
* ROC Curve
* Classification Report

---

## 📈 Sample Prediction

**Input**

| Feature         | Value               |
| --------------- | ------------------- |
| Batting Team    | Chennai Super Kings |
| Bowling Team    | Mumbai Indians      |
| City            | Chennai             |
| Target          | 181                 |
| Current Score   | 120                 |
| Overs Completed | 15.2                |
| Wickets Lost    | 4                   |

**Output**

```
Winning Probability : 68%
Losing Probability  : 32%
```

---

## 📁 Repository Structure

```
IPL-Win-Predictor/
│
├── IPL_Win_Predictor.ipynb
├── README.md
├── requirements.txt
├── matches.csv
├── deliveries.csv
└── images/
```

---

## 🎯 Future Improvements

* Deploy using Streamlit
* Improve model accuracy using advanced ensemble methods
* Add interactive dashboard
* Live match probability visualization
* Hyperparameter tuning

---

## 📚 Learning Outcomes

This project helped me gain practical experience in:

* Data preprocessing
* Feature engineering
* Classification algorithms
* Model evaluation
* Sports analytics using Machine Learning

---

## 🙏 Acknowledgements

A huge thanks to the **InternPe** team for providing this hands-on learning opportunity and helping me strengthen my Machine Learning skills through practical projects.

---

## 📬 Connect With Me

If you have any suggestions, feedback, or would like to collaborate, feel free to connect with me on LinkedIn.

⭐ If you found this project helpful, consider giving this repository a star!
