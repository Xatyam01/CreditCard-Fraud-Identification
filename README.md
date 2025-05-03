# 🧠 Fraud Detection Model

This repository contains code for training and evaluating a machine learning model to detect fraudulent transactions.

---

## 📁 Contents

- `main.py` or `.ipynb`: Code to train the model
- `fraud_detection_model.pkl`: Trained model saved using joblib/pickle
- `.gitignore`, `README.md`: Project configs and documentation
-  `creditcard.csv`: Dataset used from offical Kaggle website, (creditcard.csv)

---

## 📊 Dataset

The dataset includes anonymized transaction features (V1 to V28), along with `Amount`, `Time`, and a `Class` label (0 = non-fraud, 1 = fraud).

---

## 🔧 How to Run

1. *Clone the repo*
  ```bash
   git clone https://github.com/yourusername/fraud-detection-model.git
   cd fraud-detection-model

2. *Install the Dependencies*
    pip install -r requirements.txt

3. *Train the model*
    python train_model.py

4. *Load and use the model*
    import joblib
    model = joblib.load('best_model.pkl')
    prediction = model.predict([your_feature_list])
