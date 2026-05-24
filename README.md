# Fraud Detection Project

## 🎯 Goal
Detect fraudulent transactions using machine learning techniques on the **[Kaggle Credit Card Fraud Detection dataset](https://www.kaggle.com/datasets/mlg-ulb/creditcardfraud)**.

## 📂 Project Structure
```
fraud-detection-project/
│
├── data/
│   ├── raw/                # Placeholder for raw CSV files (git‑ignored)
│   └── processed/          # Placeholder for processed data (git‑ignored)
│
├── notebooks/
│   └── fraud_detection_project.ipynb   # Exploratory analysis & model training
│
├── models/
│   └── xgb_fraud_model.pkl   # Trained XGBoost model (git‑ignored)
│
├── reports/
│   └── figures/               # Generated plots (git‑ignored)
│
├── README.md                  # 📖 This file
├── requirements.txt           # 📦 Python dependencies
├── .gitignore                 # 🚫 Untracked files
└── LICENSE                    # 📄 MIT license
```

## 🛠️ Installation
```bash
# Clone the repo (once it exists on GitHub)
git clone https://github.com/DivyanshuHeroo/fraud-detection-project.git
cd fraud-detection-project

# Install dependencies in a virtual environment
python -m venv venv
source venv/bin/activate   # macOS/Linux
# or
venv\Scripts\activate      # Windows
pip install -r requirements.txt
```

## 📊 Usage
Open the notebook:
```bash
jupyter notebook notebooks/fraud_detection_project.ipynb
```
The notebook walks through:
1. Data loading & exploratory analysis
2. Feature engineering
3. Model training with **XGBoost**, hyper‑parameter tuning via **Optuna**, and interpretability with **SHAP**
4. Evaluation on an imbalanced dataset using **imbalanced‑learn** utilities

## 📈 Expected Results
- **Precision**, **Recall**, and **F1‑score** for the minority (fraud) class.
- SHAP plots highlighting the most important features driving fraud predictions.

## 📜 License
This project is licensed under the **MIT License** – see the `LICENSE` file for details.

---
*Created with 💡 Antigravity – your AI‑powered coding companion.*
