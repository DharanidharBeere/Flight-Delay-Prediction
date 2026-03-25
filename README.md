# ✈️ Flight Delay Prediction

## 📌 Project Overview
This project predicts whether a flight will be **delayed or on time** using Machine Learning.  
The goal is to help passengers and airlines make better decisions by identifying possible delays in advance.

---

## 🎯 Objective
- Predict flight delays (Yes/No)
- Reduce missed delays
- Balance between correct predictions and false warnings

---

## 🧠 Model Used
- XGBoost Classifier (Optimized)
- Threshold tuning applied to improve performance

---

## ⚙️ How It Works
1. Input flight data (airline, time, distance, etc.)
2. Model calculates probability of delay
3. Apply threshold (0.7) to classify:
   - Above 0.7 → Delayed
   - Below 0.7 → On Time

---

## 📊 Results
- Improved detection of delayed flights
- Reduced missed delays significantly
- Some increase in false delay warnings (trade-off)

---

## 📈 Evaluation
- Confusion Matrix used for performance analysis
- Compared results before and after tuning

---

## 📂 Files in Repository
- `Final_Running_Modal_{FD}.ipynb` → Main project notebook  
- `README.md` → Project documentation  

---

## 🚀 Conclusion
The model successfully improves delay prediction using threshold tuning.  
It provides a better balance between detecting delays and avoiding false alerts.

---

## 👨‍💻 Author
Dharanidhar Beere
