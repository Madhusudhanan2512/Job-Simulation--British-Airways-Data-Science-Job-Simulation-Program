#  British Airways Customer Insights: NLP + ML

This repository contains two key data science tasks based on British Airways data:

1. **Task 1: Sentiment Analysis of Customer Reviews**
2. **Task 2: Predicting Customer Booking Probability**

Each task showcases end-to-end analysis using real-world data — from cleaning to modeling — offering actionable insights that can help improve customer satisfaction and operational efficiency.

---

##  Task 1: Sentiment Analysis

###  Objective:
Analyze customer reviews of British Airways and classify them as **Positive**, **Negative**, or **Neutral**.

###  Methods Used:
- Text Preprocessing (stopword removal, stemming)
- Feature Extraction using TF-IDF
- Model Training using Logistic Regression / Naive Bayes
- Evaluation using Confusion Matrix & Accuracy Score

###  Findings:
- Positive Reviews: **981**
- Negative Reviews: **781**
- Neutral Reviews: **238**

 Nearly **39%** of the reviews were negative. Major concerns include:
- Seat availability
- Flight timings
- Food & services

---

##  Task 2: Customer Booking Prediction

###  Objective:
Predict the **probability of a customer making a booking** using features like origin, route, and stay duration.

###  Methods Used:
- Feature Engineering
- Encoding Categorical Variables
- Model Building with Random Forest / Logistic Regression
- Evaluation using Accuracy and Feature Importance

###  Findings:
- **Model Accuracy:** 85%
- Top predictive features:
  - Booking origin
  - Route
  - Length of stay

---

##  Key Results

| Task | Technique | Accuracy |
|------|-----------|----------|
| Sentiment Analysis | Logistic Regression | ~81% |
| Booking Prediction | Random Forest | **85%** |

---

##  Learnings & Recommendations

- **Sentiment Analysis** revealed clear customer pain points that should be addressed to improve satisfaction.
- **Booking Prediction** can be integrated into BA’s CRM system for lead scoring and dynamic marketing.

---

##  Tech Stack

- Python
- Scikit-learn
- Pandas, NumPy
- NLTK / spaCy
- Matplotlib / Seaborn
- Jupyter Notebooks

