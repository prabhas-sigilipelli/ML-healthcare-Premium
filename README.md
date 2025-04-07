
# 🏥 Health Insurance Cost Predictor

This project is a **Machine Learning-based Web App** built with **Streamlit** that predicts health insurance costs based on user inputs like age, gender, income, BMI, medical history, and more.

---

## 🚀 Features

- Interactive web interface with multiple input fields  
- Predicts personalized health insurance costs  
- Pre-trained ML models used for prediction  
- Easy-to-deploy and lightweight frontend using Streamlit

---

## 🧠 How It Works

The application uses machine learning models (trained and stored in the `artifacts/` folder) to predict the health insurance premium based on:

- Age  
- Income  
- Gender  
- BMI  
- Region  
- Smoking status  
- Marital and employment status  
- Medical history, and more

---

## 🗂 Project Structure

```
ML-healthcare-Premium/
│
├── artifacts/
│   ├── model_rest.joblib
│   ├── model_young.joblib
│   ├── scaler_rest.joblib
│   └── scaler_young.joblib
│
├── main.py                # Main Streamlit app
├── prediction_helper.py   # Prediction logic
├── requirements.txt       # Dependencies
├── README.md              # Project documentation
├── LICENSE
└── .gitignore
```

---

## 📦 Installation

1. **Clone the repository**  
```bash
git clone https://github.com/prabhas-sigilipelli/ML-healthcare-Premium.git
cd ML-healthcare-Premium
```

2. **Create and activate a virtual environment**  
```bash
python -m venv venv
venv\Scripts\activate        # On Windows
source venv/bin/activate     # On Mac/Linux
```

3. **Install the dependencies**  
```bash
pip install -r requirements.txt
```

4. **Run the Streamlit app**  
```bash
streamlit run main.py
```

---

## 🌐 Deployment (Streamlit Cloud)

To deploy this on **[Streamlit Cloud](https://streamlit.io/cloud)**:
- Push the repo to GitHub
- Set the path to `main.py`
- Ensure the `artifacts/` folder is present and accessible
- Python version used: **3.10**
- All dependencies must be listed in `requirements.txt`

---

## ✅ Requirements

```
joblib==1.3.2  
pandas==2.0.2  
streamlit==1.22.0  
numpy==1.25.0  
scikit-learn==1.3.0  
xgboost==2.0.3  
```

---

## 👤 Author

**Sigilipelli Prabhas**  
[LinkedIn Profile](www.linkedin.com/in/prabhas-sigilipelli)  
Project deployed at: [Streamlit App](https://sigilipelli-prabhas-ml-healthcare-premium.streamlit.app/) 
