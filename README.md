
# 🔐 Cybersecurity Attack Detection System 🚀  

A **machine learning-powered** web application for detecting and classifying different types of cyber attacks.  
Built using **Streamlit, Scikit-Learn, XGBoost, TensorFlow**, and more! 🛡️  

Here is the link to the web application - [Cyber Security Attack Prediction](https://cyber-security-attack-prediction-nk3gtz97kb36k2ry5oumfx.streamlit.app/)

## Project & Contribution — Saibou Keita

**Academic group project — DSTI — 2025**

Originally developed as a team project:
[Original repository](https://github.com/ashish18oct/Cyber-Security-Attack-Prediction).

**Saibou Keita** — Machine Learning, model training/evaluation & Streamlit UI  
Former GitHub account: [@KEITA-Sai](https://github.com/KEITA-Sai) · Current account: [@skeita](https://github.com/skeita)

My contribution focused on:

- Data preparation and preprocessing.
- Model training and evaluation, including comparison of Random Forest and XGBoost.
- Integration of the trained model into a Streamlit application with interactive visualisations.

### Team

- Yani Lala
- Saibou Keita
- Ashish Singh
- Aicha El Gueddari
- Ravichandan Kodijuttu
- Durga Bhavani Kowrada

This is a **group project**. This fork preserves the original team attribution and Git history.

### GitHub Identity Continuity

`@KEITA-Sai` was my GitHub account during the 2025 project.
`@skeita` is my current account, used for the 2026 portfolio documentation.

Both accounts refer to **Saibou Keita**. Historical commits retain their original authorship.

---

## ✅ Prerequisites  

💻 **System Requirements:**  
- Python **3.8+** 🐍  
- `pip` (**Python package manager**)  🛠️ *(Pre-installed with Python but can be updated if needed)*  
- **Git** 🌍 *(Required for cloning the repository and version control)*   

---

## 📁 Project Structure

```
├── App.py                              # Streamlit web app
├── CyberSecurity_Attack_Prediction.ipynb  # Model training & exploration
├── cybersecurity_attacks.csv          # Dataset used for training
├── xgboosttrained.pkl                 # Trained XGBoost model
├── requirements.txt                   # Python dependencies
├── CyberSecAttacksProjectReport.pdf   # Project documentation/report
└── README.md                          # You're here!
```

---

## ⚙️ Installation Steps 🛠️  

### 1️⃣ Clone the repository  

```bash
git clone https://github.com/skeita/Cyber-Security-Attack-Prediction.git
cd Cyber-Security-Attack-Prediction
```

### 2️⃣ Set up a virtual environment  

#### For Windows 🏁  
```bash
python -m venv venv
venv\Scripts\activate
```

#### For macOS/Linux 🐧  
```bash
python3 -m venv venv
source venv/bin/activate
```

### 3️⃣ Install required dependencies  
```bash
pip install -r requirements.txt
```

---

## 🖥️ How to Use

1. Start the application:
```bash
streamlit run App.py
```
2. Enter the required network traffic feature values in the sidebar.
3. Click **Make Prediction**.
4. View the predicted attack type and model confidence.

---

🔥 **Stay Secure, Stay Ahead!** 🛡️🚀  

---
