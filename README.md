# 🩺 AI-Driven Personalized Medical Recommendation System

This project is an AI-based web application that predicts diseases from user-provided symptoms and recommends suitable medicines. It leverages machine learning techniques to assist in early-stage medical guidance and demonstrates the practical application of AI in healthcare.

---

## 📌 Features

- Symptom-based disease prediction using machine learning  
- Personalized medicine recommendation using content-based filtering  
- Support for multiple symptoms input  
- Optional speech-based symptom input  
- Interactive web interface built with Flask  
- Real-time prediction and recommendations  

---

## 🧠 Machine Learning Models Used

- Decision Tree Classifier  
- Random Forest Classifier  
- Support Vector Machine (SVM)  

The Random Forest model was selected as the final model due to its superior performance across evaluation metrics.

---

## 📊 Model Performance

The trained model was evaluated using standard classification metrics:
- Accuracy  
- Precision  
- Recall  
- F1-Score  

The system achieved approximately **88–90% accuracy** on the test dataset, with balanced precision and recall values.

---

## 🗂️ Dataset

The dataset consists of:
- Symptom-to-disease mappings  
- Disease labels  
- Associated medicine information  

### Preprocessing Steps:
- Data cleaning and normalization  
- One-hot encoding of symptoms  
- Handling class imbalance using SMOTE  
- Feature selection for optimal model performance  

---

## 🏗️ System Architecture

1. User inputs symptoms (text or speech)  
2. Input is preprocessed and converted into a feature vector  
3. Machine learning model predicts the disease  
4. Content-based filtering recommends suitable medicines  
5. Results are displayed on the web interface  

---

## 🌐 Web Technologies Used

- **Backend:** Flask (Python)  
- **Frontend:** HTML, CSS  
- **Templating Engine:** Jinja2  
- **Model Serialization:** Pickle (.pkl)  

Jinja2 is used to dynamically render predictions and recommendations on the HTML pages.

---

## ▶️ How to Run the Project

1. Clone the repository:
   ```bash
   git clone https://github.com/mansi0406/medical-recommendation-system.git
