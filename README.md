# 🌍 World Risk Index Prediction using Machine Learning

## 📌 Project Overview
This project focuses on predicting the **World Risk Index (WRI) Category** of countries using Machine Learning techniques.  
The WRI measures disaster risk by considering **Exposure, Vulnerability, Susceptibility, Coping Capacity, and Adaptive Capacity**.  

By applying a **Random Forest Classifier**, this project automates the classification of countries into **risk categories (Low, Medium, High, Very High)**, supporting policymakers and researchers in disaster preparedness and management.

---

## 🎯 Objectives
- To clean and preprocess the World Risk Index dataset.  
- To train and evaluate a Machine Learning model for predicting disaster risk categories.  
- To deploy the trained model for future predictions.  
- To demonstrate how ML can help in **real-world disaster risk management**.  

---

## 🗂️ Dataset
- **File:** `world_risk_index.csv`  
- **Features Used:**  
  - Exposure  
  - Vulnerability  
  - Susceptibility  
  - Lack of Coping Capacity  
  - Lack of Adaptive Capacities  
  - Year  
- **Target Variable:** WRI Category (Low, Medium, High, Very High)  

---

## 🛠️ Tools & Technologies
- **Programming Language:** Python  
- **Libraries:** Pandas, NumPy, Scikit-learn, Pickle  
- **Platform:** Google Colab / Jupyter Notebook  
- **Deployment:** Saved ML Model (`rf_model.pkl`) and Label Encoder (`label_encoder.pkl`)  

---

## 🔑 Methodology
1. **Data Collection** – Imported *world_risk_index.csv*.  
2. **Data Preprocessing** – Handled missing values (mean/mode imputation), encoded categorical data.  
3. **Feature Selection** – Selected important WRI indicators.  
4. **Model Training** – Applied Random Forest Classifier.  
5. **Model Evaluation** – Measured accuracy, classification report, and confusion matrix.  
6. **Deployment** – Saved model and label encoder using Pickle for reusability.  

---

## 📊 Results
- **Model Used:** Random Forest Classifier  
- **Performance:** Achieved reliable accuracy on test data.  


  
- **Evaluation Metrics:**  
- Accuracy Score  
- Classification Report  
- Confusion Matrix  

---

## 🚀 Deployment
The model and encoder are saved for future predictions:  
- `rf_mode.pkl` → Trained Random Forest model  
- `label_encoder.pkl` → Label encoder for WRI categories  

You can load these files and predict risk categories without retraining the model.

---

## 📌 Improvisations Done
- Handled missing values using **mean/mode imputation**.  
- Used **Label Encoding** for categorical targets.  
- Chose **Random Forest** for its robustness and high accuracy.  
- Saved **trained model and encoder** for reusability using Pickle.  
- Generated a **clean dataset** for future model improvements.  

---

## 🖼️ Screenshots of Output

<img width="1075" height="814" alt="Image" src="https://github.com/user-attachments/assets/3b07847c-fea9-4053-af80-cb3ca919ef32" />

<img width="1212" height="799" alt="Image" src="https://github.com/user-attachments/assets/4f029fa6-934d-44e7-8d37-abc64226052e" />



---

## ✅ Conclusion
This project successfully demonstrates how Machine Learning can be applied to predict disaster risk categories using the World Risk Index dataset. The Random Forest Classifier provided reliable results, and the deployment ensures scalability and efficiency. This system can serve as a valuable tool for researchers and policymakers to improve disaster preparedness and mitigation strategies.  

