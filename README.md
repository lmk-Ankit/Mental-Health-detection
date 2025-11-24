# 🧠 Mental Health & Emotion Detection (Machine Learning + Explainability)

A machine-learning system that predicts **human emotions** (e.g., frustration, loneliness, hopelessness) and **mental health conditions** (e.g., depression, anxiety) from raw text.

Built using **TF-IDF + Logistic Regression / RandomForest**, with **SHAP & LIME** for explainability.

---
## Dataset
-RMHD(reddit Mental Health dataset) or any dataset u can feed just check the names with the code

##  Features

###  Dual Prediction System
- Emotion Detection (GoEmotions dataset)
- Mental Health Classification (Reddit MH dataset)
- Multi-label output (one text → multiple emotions/conditions)

###  Machine Learning Models
- TF-IDF Vectorizer
- Logistic Regression
- Random Forest
- MultiOutputClassifier wrapper

###  Explainability (XAI)
- SHAP — Global & local feature importance
- LIME — Explain individual text predictions
- Transparent & interpretable ML decisions

---

---

## 🔧 Installation

### 1️⃣ Clone the repository
```bash
git clone https://github.com/<your-username>/<your-repo>.git
cd <your-repo>
python -m venv venv
```
For Windows
```bash
venv\Scripts\activate
```
##  Requirements
- numpy
- pandas
- scikit-learn
- joblib
- matplotlib
- seaborn
- shap
- lime
- tqdm
- jupyter
- notebook
## Resultant Output

![WhatsApp Image 2025-11-24 at 15 16 45_20600720](https://github.com/user-attachments/assets/fc738fb2-0c52-4e67-afaf-6277c089814e)
![WhatsApp Image 2025-11-24 at 15 17 23_ce29fb17](https://github.com/user-attachments/assets/ec7ed6e4-34d6-462a-9e40-5f8d8b5aa5ab)
![WhatsApp Image 2025-11-24 at 15 17 48_c5f2f375](https://github.com/user-attachments/assets/da1222dc-33cc-40c7-ac97-faae653a82ec)
![WhatsApp Image 2025-11-24 at 15 18 05_b390b2ed](https://github.com/user-attachments/assets/dbfba6a9-fc77-4b8e-89f8-5170880b5701)

---
📈 Future Improvements

- Add BERT-lite model for comparison

- Flask/FastAPI API

- Flutter mobile UI

- Deploy on Render / HF Spaces

🤝 Contributing

- PRs are welcome — open an issue for major changes.

📜 License

- MIT License
---





