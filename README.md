# 🧠 FocusScoreML  
### Predicting & Improving Daily Productivity using Machine Learning

FocusScoreML is a machine learning–powered web application that predicts a person’s daily **focus/productivity score (0–100)** based on lifestyle habits such as sleep, screen time, work hours, exercise, mood, and distractions.

The project goes beyond prediction by providing **actionable recommendations**, turning an ML model into a practical, user-focused product.

---

## 🚀 Features
- Manual user input through a clean Streamlit web interface  
- Machine Learning–based focus score prediction  
- Explainable lifestyle-driven insights  
- Personalized habit improvement recommendations  
- End-to-end ML pipeline: data → model → web app  

---

## 🧠 Problem Statement
Productivity is influenced by multiple behavioral and lifestyle factors. However, people often struggle to quantify how their daily habits impact focus.

This project answers:
> *“Given my daily habits, how productive am I likely to be — and what can I improve?”*

---

## 📊 Dataset
- Synthetic but realistic dataset simulating human behavior
- Features include:
  - Sleep hours  
  - Screen time  
  - Work hours  
  - Breaks taken  
  - Exercise minutes  
  - Caffeine intake  
  - Distractions  
  - Mood score  

Target:
- **Focus Score (0–100)**

---

## 🤖 Machine Learning Approach
- Problem Type: **Regression**
- Models used:
  - Linear Regression (baseline)
  - **Random Forest Regressor (final model)**
- Evaluation Metrics:
  - R² Score
  - Mean Absolute Error (MAE)

Random Forest performed best due to its ability to model non-linear relationships between lifestyle factors.

---

## 🌐 Web Application
- Built using **Streamlit**
- Users manually enter daily habit data
- The app predicts focus score in real time
- Provides personalized, rule-based recommendations

---

## 🛠 Tech Stack
- Python  
- Pandas, NumPy  
- Scikit-learn  
- Streamlit  
- Matplotlib / Seaborn  

---

## 📈 Key Learnings
- ML is most impactful when combined with explainability
- Product thinking is as important as model accuracy
- Deploying models highlights real-world engineering challenges

---

## 🔮 Future Improvements
- Visual focus score gauge
- Feature contribution breakdown for each prediction
- User history tracking
- Cloud deployment with persistent storage

---

## ▶️ How to Run Locally
```bash
pip install -r requirements.txt
streamlit run app.py
