# Customer Churn Prediction App

This project is a machine learning-based web application that predicts customer churn. It provides both **Flask** and **FastAPI** interfaces for making predictions based on customer data.

## 🧠 Features

- Trained ML model for predicting customer churn
- Web interface built with **Flask**
- REST API built with **FastAPI**
- Data preprocessing with saved encoders and scalers
- Example dataset: `customer-churn.csv`
- Jupyter notebook for model training: `customer_churn.ipynb`

---

---

## 🚀 Getting Started

### 1. Clone the Repository

```bash
git clone https://github.com/yourusername/customer-churn-predictor.git
cd customer-churn-predictor
```
2. Create a Virtual Environment
```bash
python -m venv venv
source venv/bin/activate  # or venv\Scripts\activate on Windows
```
3. Install Requirements
```bash
pip install -r requirements.txt
```
🧪 Running the Applications

Flask App (Frontend + Prediction)
```bash
python app.py
```
FastAPI App (API Interface)
```bash
uvicorn fastapi_app:app --reload
```
📦 Model Training
The model is trained in customer_churn.ipynb using the dataset customer-churn.csv. It includes: 

	•	Data cleaning 
	•	Feature encoding 
	•	Scaling 
	•	Model training (e.g., RandomForest, XGBoost, etc.) 
	•	Exporting artifacts (best_model.pkl, encoder.pkl, scaler.pkl, etc.) 
