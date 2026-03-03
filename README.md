# 🛒 Cart Super Add-On (CSAO) Recommendation System

### Zomathon 2026 – Problem Statement 2

---

## 👩‍💻 Team Members

* **ABINAYA N**
* **JANANAPRIYA T**

---

## 📌 Project Overview

The Cart Super Add-On (CSAO) Recommendation System is a context-aware machine learning solution designed to increase **Average Order Value (AOV)** by intelligently suggesting complementary items based on real-time cart composition, user behavior, and contextual signals.

Unlike static popularity-based systems, our model dynamically ranks add-on items using feature-engineered cart, user, and contextual data.

---

## 🔗 Google Colab Notebook (Full Implementation)

👉 **Click here to view and run the complete project:**
[https://colab.research.google.com/drive/1m4CDNN07_YVPbRCIH353UIu2LDk2lmb4](https://colab.research.google.com/drive/1m4CDNN07_YVPbRCIH353UIu2LDk2lmb4)

---

## 🎯 Problem Formulation

We model the recommendation system as a ranking task:

[
f(U, R, C_t, I) \rightarrow P(Y = 1)
]

Where:

* **U** = User
* **R** = Restaurant
* **Cₜ** = Cart state
* **I** = Candidate add-on item
* **Y = 1** if user accepts the add-on

The goal is to maximize ranking quality and improve add-on acceptance probability.

---

## ⚙️ Tech Stack

* Python
* Pandas
* NumPy
* TensorFlow
* Scikit-learn
* Google Colab

---

## 📊 Key Features

* Cart-aware feature engineering
* Cold-start detection (`cold_user` flag)
* Contextual features (hour, meal_time, city)
* Neural ranking model
* Baseline comparison

---

## 📈 Performance Metrics

| Metric          | Baseline | Proposed |
| --------------- | -------- | -------- |
| AUC             | 0.69     | 0.84     |
| Precision@8     | 0.22     | 0.37     |
| NDCG@8          | 0.30     | 0.51     |
| Acceptance Rate | 14%      | 24%      |

---

## 🚀 Business Impact

* 📈 +8–10% AOV Increase
* 📊 +12% Attach Rate
* ⚡ <250ms Inference Latency
* 💰 Revenue Optimization

---

## 📁 Repository Structure

```
CSAO-Recommendation-System/
│
├── CSAO_Model.ipynb
├── processed_data.csv
├── submission.pdf
├── images/
│   ├── dataset.png
│   ├── features.png
│   └── training.png
└── README.md
```

---

## 🧠 Key Innovation

* Real-time cart embedding
* Context-aware ranking
* Cold-start fallback strategy
* Production-scalable architecture

---

## 📌 How to Run

1. Open the Google Colab link above
2. Click **Runtime → Run All**
3. View model training and evaluation metrics

---

## 🏆 Hackathon Submission

This project was developed for **Zomathon 2026 – Problem Statement 2**, focusing on building a scalable and intelligent Cart Super Add-On recommendation engine.

---

