This project is an AI-powered chatbot that predicts possible medical conditions based on user-entered symptoms. It uses a machine learning model trained on symptom–disease mappings and offers an interactive web interface via Streamlit.

---

## 🧠 Features
- Accepts comma-separated symptoms as input
- Predicts the most likely medical condition
- Interactive UI with Streamlit
- Uses Random Forest Classifier with symptom vectorization

---

## 🛠️ Tech Stack
| Component      | Technology         |
|----------------|---------------------|
| Language       | Python              |
| Frontend UI    | Streamlit           |
| ML Library     | Scikit-learn        |
| Dataset        | Custom CSV (symptoms + diseases) |
| NLP Utility    | MultiLabelBinarizer |

---

## 🚀 Getting Started

### 1. Clone the Repository
```bash
git clone https://github.com/sandhiya26102004/Disease-Symptom-Prediction-Chatbot-main.git
cd Disease-Symptom-Prediction-Chatbot-main
```

### 2. Install Dependencies
```bash
pip install -r requirements.txt
```

### 3. Run the App
```bash
streamlit run app.py
```

---

## 📁 Dataset Format (CSV)
```
Disease,Symptoms
Flu,"fever, headache, cough"
Diabetes,"weight loss, fatigue, blurred vision"
```

---

## 📸 Screenshot
![screenshot](https://via.placeholder.com/800x400.png?text=AI+Symptom+Checker+Chatbot+Demo)
