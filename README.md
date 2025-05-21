# 🌍 Carbon Risk Intelligence Engine

This project predicts a **Carbon Risk Score** for companies using both structured data (like CO₂ emissions, ESG score, green certifications) and short sustainability text reports.

It demonstrates how AI and data science can help assess which companies pose higher environmental risks — supporting efforts in climate analytics, ESG investment, and corporate profiling.

---

## 🚀 Features

- Clean and process structured environmental data
- Combine numeric features like emissions, ESG score, revenue
- Train a machine learning model to predict risk scores
- Visualize model performance and feature importance
- Export model and predictions for reuse

---


---

## 📊 Technologies Used

- `pandas`, `numpy` – Data wrangling
- `matplotlib`, `seaborn` – Visualization
- `scikit-learn` – Model training (RandomForestRegressor)
- `joblib` – Saving trained model
- *(Optional)* `sentence-transformers` – Text embedding if expanding to NLP

---

## 📦 How to Run the Project

1. 📥 Clone this repository  
2. 🧪 Install dependencies  
3. 📓 Open the notebook and run step-by-step

```bash
pip install -r requirements.txt
jupyter notebook notebooks/carbon_risk_model.ipynb
🧠 Future Work
Integrate BERT-based report analysis

Add Streamlit dashboard for interactive exploration

Apply to real ESG datasets from companies or NGOs

📬 Author
Brijesh Mahant
Postgraduate student – MSc Artificial Intelligence and its Applications
University of Essex
📧 brijeshmahan@gmail.com
🌐 github.com/Om1323

---

## ✅ 📦 `requirements.txt` (create this text file)

pandas
numpy
matplotlib
seaborn
scikit-learn
joblib
sentence-transformers

