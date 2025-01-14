# Credit Card Fraud Detection 🛡️💳

This project focuses on detecting fraudulent credit card transactions using machine learning. The goal is to build a robust model that can distinguish between genuine and fraudulent transactions based on transaction data.

---

## 📋 **Project Overview**
Credit card fraud detection is a crucial task in the finance industry. This project leverages machine learning algorithms to classify transactions as legitimate or fraudulent. The dataset contains anonymized features and labels indicating whether a transaction is fraudulent.

Key objectives:
- Improve detection accuracy
- Minimize false positives
- Ensure real-time detection capabilities

---

## 🧪 **Dataset**
The dataset used for this project is from [Kaggle's Credit Card Fraud Detection dataset](https://www.kaggle.com/mlg-ulb/creditcardfraud).

### **Dataset Details:**
- **Number of features:** 30 (V1, V2, ..., V28, Amount, and Time)
- **Number of samples:** 284,807 transactions
- **Class distribution:**  
  - 0: Legitimate transactions (99.8%)  
  - 1: Fraudulent transactions (0.2%)  

---

## 🛠️ **Technologies Used**
- **Python** 🐍
- **Pandas** 📊
- **NumPy** 🔢
- **Scikit-learn** 🤖
- **Matplotlib** 📈
- **Seaborn** 📊

---

## 📂 **Project Structure**
```bash
credit-card-fraud-detection/
├── core/
│   └── migrations/
├── datasets/
│   └── creditcard.csv
├── models/
│   └── fraud_detection_model.pkl
├── notebooks/
│   └── exploratory_analysis.ipynb
└── README.md

⚙️ Setup Instructions

To run this project on your local machine, follow the steps below:
1️⃣ Clone the Repository
git clone https://github.com/eKidenge/credit-card-fraud-detection.git
cd credit-card-fraud-detection
2️⃣ Create a Virtual Environment
python3 -m venv myenv
source myenv/bin/activate
3️⃣ Install Dependencies
pip install -r requirements.txt
4️⃣ Run the Project: python3 manage.py runserver 127.0.0.1:40000


📊 Model Performance

The following machine learning models were tested:

    Logistic Regression
    Random Forest
    XGBoost

Model	Accuracy	Precision	Recall
Logistic Regression	98.7%	96.2%	92.4%
Random Forest	99.1%	97.5%	94.3%
XGBoost	99.3%	98.1%	95.7%
📈 Exploratory Data Analysis (EDA)

Key insights from the dataset:

    The dataset is highly imbalanced, with only 0.17% fraudulent transactions.
    Feature scaling was applied to ensure proper model performance.
    PCA (Principal Component Analysis) was used for dimensionality reduction.

💻 Key Features

    Fraud detection using real-time transaction data
    Machine learning models optimized for accuracy
    Exploratory data analysis and feature engineering

🚀 Future Improvements

    Implement deep learning models for better accuracy
    Use a larger dataset for better generalization
    Deploy the model using Flask or FastAPI for real-time detection

🤝 Contributing

Contributions are welcome! Please follow the steps below:

    Fork the repository
    Create a new branch: git checkout -b feature-name
    Commit your changes: git commit -m 'Add feature'
    Push to the branch: git push origin feature-name
    Open a pull request

🛡️ License

This project is licensed under the MIT License. See the LICENSE file for more details.
📧 Contact

    GitHub: eKidenge
    Email: elishakidenge@gmail.com
