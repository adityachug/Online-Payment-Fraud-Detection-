<<<<<<< HEAD
# Online-Payment-Fraud-Detection-
This project applies machine learning to detect fraudulent online payments. It includes preprocessing, feature engineering, and XGBoost training to classify transactions as legit or fraud. The pipeline handles class imbalance and evaluates with precision, recall, F1-score, and ROC-AUC for reliable fraud detection.
=======
# Online Payment Fraud Detection

This project applies **machine learning** techniques to detect fraudulent online payments.  
It explores **data preprocessing, feature engineering, and model training (XGBoost, Random Forest, Logistic Regression)** to classify transactions as **legit or fraud**.  
The pipeline addresses **class imbalance** and evaluates models with **precision, recall, F1-score, and ROC-AUC** to ensure reliable fraud detection.

---

## 📂 Project Structure
```
fraud-detection/
│── data/            # (Optional) Sample/public datasets (no sensitive data)
│── notebooks/       # Jupyter notebooks for EDA & experimentation
│── src/             # Source code (preprocessing, training, evaluation)
│── models/          # Trained model files (.pkl/.joblib)
│── requirements.txt # Project dependencies
│── README.md        # Documentation
```

---

## ⚙️ Installation

Clone this repository and install dependencies:

```bash
git clone https://github.com/your-username/fraud-detection.git
cd fraud-detection
pip install -r requirements.txt
```

---

## 🚀 Usage

1. Open the **notebooks/** folder in Jupyter/Colab.  
2. Run preprocessing, training, and evaluation steps.  
3. Trained models are saved under **models/** folder (`fraud_model.joblib`).  
4. Future deployment options include **Flask/FastAPI API** or **Streamlit dashboard**.

---

## 📊 Models Used
- Logistic Regression  
- Random Forest Classifier  
- XGBoost Classifier  
- Decision Tree / Extra Trees  
- Support Vector Machine (SVC)

---

## 📈 Evaluation Metrics
- Accuracy  
- Precision & Recall  
- F1-Score  
- Confusion Matrix  
- ROC-AUC Curve  
- Precision-Recall Curve  

---

## 🤝 Contributing
Pull requests are welcome. For major changes, please open an issue first to discuss what you would like to change.

---

## 📜 License
This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
>>>>>>> c9e5352 (Removed large Fraud.csv and cleaned up files)
