# Flight Delay Prediction Using Machine Learning

## Project Overview
This project predicts whether a flight will be **delayed or on time** using Machine Learning techniques.  
It uses historical flight data to help improve decision-making for passengers and airlines.

---

## Research Objective
To evaluate how accurately **gradient-boosted models (XGBoost)** can predict flight delays and improve performance using model tuning techniques.

---

## Dataset
- Source: U.S. Bureau of Transportation Statistics (BTS)
- Alternative: Kaggle Flight Delay Dataset  
- Type: Tabular Data
- Dataset link:([[url](https://www.transtats.bts.gov/ONTIME/)](https://www.transtats.bts.gov/ONTIME/))

### Features include:
- Airline
- Departure & Arrival Time
- Distance
- Airport information
- Delay-related variables

---

## Model Used
- XGBoost Classifier (Gradient Boosted Model)
- Compared before and after tuning

---

## Methodology

1. Data preprocessing and cleaning  
2. Feature selection and encoding  
3. Model training using XGBoost  
4. Model evaluation using confusion matrix  
5. Threshold tuning to improve predictions  

---

## How Prediction Works
- The model outputs a **probability of delay**
- A threshold is applied:
  - If probability > 0.7 → Delayed
  - Else → On Time

---

##  Results

### Before Tuning:
- Very good at predicting on-time flights  
- Poor at detecting delayed flights (many missed delays)

### After Tuning:
- Significant improvement in detecting delays  
- Reduced missed delays  
- Slight increase in false delay warnings (trade-off)

---

##  Evaluation Metrics
- Confusion Matrix  
- Precision, Recall, F1-score  

---

##  Key Insight
The model shows a trade-off:
- Lower threshold → more delay predictions (more false alarms)
- Higher threshold → fewer false alarms but may miss delays  

Optimal threshold chosen: **0.7**

---

## Project Files
- `Flight_Delay_Prediction_using_GB_Ensemble_models.ipynb` → Main notebook  
- `README.md` → Documentation  

---

## Conclusion
The model successfully improves flight delay prediction using XGBoost and threshold tuning.  
It achieves a better balance between detecting delays and reducing false warnings.

---

## 👨‍💻 Author
**Dharanidhar Beere**  
MSc Data Science (Advanced Research)
