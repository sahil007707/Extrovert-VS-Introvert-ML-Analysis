# Extrovert-VS-Introvert-ML-Analysis# 🧠 Personality Prediction Using Machine Learning

![License](https://img.shields.io/badge/license-MIT-blue.svg)
![Python](https://img.shields.io/badge/python-3.7+-blue.svg)
![Model Accuracy](https://img.shields.io/badge/accuracy-92.6%25-brightgreen.svg)
![Status](https://img.shields.io/badge/project-active-success.svg)

---

## 🌟 Overview

This machine learning project predicts whether an individual is an **Introvert** or an **Extrovert** based on their social behavior patterns, such as time spent alone, stage fear, post frequency, and social engagement.

Leveraging survey data and robust preprocessing, this model achieves a **92.6% accuracy** using a Random Forest Classifier. It's an insightful exploration of personality traits and how data can reflect psychological patterns.

---

## 📊 Dataset Features

| Feature                    | Description                                                                 |
|----------------------------|-----------------------------------------------------------------------------|
| `Time_spent_Alone`         | Hours per week spent alone                                                  |
| `Stage_fear`               | Fear of public speaking (`Yes`/`No`)                                        |
| `Social_event_attendance` | Frequency of attending social events                                        |
| `Going_outside`            | Frequency of outdoor activity                                               |
| `Drained_after_socializing`| Energy level after socializing (`Yes`/`No`)                                 |
| `Friends_circle_size`      | Number of close friends                                                     |
| `Post_frequency`           | Number of social media posts per week                                      |
| `Personality`              | Target label - `Introvert` or `Extrovert`                                  |

---

## 🛠️ Tools & Technologies

- Python 🐍
- Pandas, NumPy
- Scikit-learn
- Matplotlib / Seaborn
- Jupyter Notebook
- VS Code

---

## 📌 Problem Statement

> Can we predict whether someone is an **introvert** or **extrovert** purely based on survey-based behavioral data?

---

## 🔄 Workflow

1. 📥 Data Import & Exploration  
2. 🧹 Data Cleaning & Preprocessing  
   - Label Encoding of categorical features
   - Conversion of object columns to numeric types
   - Handling missing values
3. 📊 Exploratory Data Analysis (EDA)
4. ⚙️ Model Building
   - Random Forest Classifier
   - Logistic Regression (optional comparison)
5. 📈 Evaluation
   - Accuracy, Precision, Recall, F1-Score
   - Confusion Matrix
6. 📡 Prediction on New Data

---

## 🎯 Model Performance

> ✅ **Accuracy Score:** `92.6%`
> Precision, Recall, F1-score (both classes):

Precision: 93%

Recall: 92–93%

 F1-score: 93%


---

## 🧑‍💼 Real-World Scenario Prediction

We tested the model on a new data point:

| Trait                         | Description                              |
|------------------------------|------------------------------------------|
| Time Alone                   | Always alone                             |
| Stage Fear                   | Yes                                      |
| Social Events                | Occasionally attends                     |
| Going Outside                | Never                                    |
| Drained After Socializing    | Yes                                      |
| Friends Circle               | None                                     |
| Post Frequency               | Almost zero                              |

> 🔍 **Prediction:** The model classified the person as an **Introvert** — a strong confirmation of its alignment with psychological traits.

---


---

## 📌 Future Enhancements

- Add interactive Streamlit web app
- Try deep learning (e.g., MLP classifier)
- Personality spectrum instead of binary classification
- More granular psychological features

---

## 📃 License

This project is licensed under the **MIT License**.

---

## 🙋‍♂️ Author

**[Md Sahil Islam]** – _Data Science Enthusiast_  
Feel free to connect on [LinkedIn](https://www.linkedin.com/in/md-sahil-islam-335789357?utm_source=share&utm_campaign=share_via&utm_content=profile&utm_medium=android_app) or explore more of my [GitHub projects](https://github.com/sahil007707?tab=repositories).

---

## 🌐 Let's Predict Personality With Data!

> “Personality is not what you say about yourself, but what your data quietly whispers.”  
> – Inspired by Behavioral ML 🧠




