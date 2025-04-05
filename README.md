

# Credit Card Fraud Detection 🛡️💳

This project uses machine learning to detect fraudulent credit card transactions. It applies various classification algorithms to a real-world, imbalanced dataset and evaluates their performance.

## 🔍 Problem Statement

Credit card fraud is a significant issue in today's digital economy. The objective of this project is to build a model that accurately identifies fraudulent transactions from a large set of real, anonymized data.

## 📁 Dataset

- **Source**: [Kaggle Credit Card Fraud Detection Dataset](https://www.kaggle.com/datasets/mlg-ulb/creditcardfraud)
- **Description**: The dataset contains transactions made by European cardholders in September 2013. It includes 284,807 transactions, of which 492 are fraudulent.

## 📊 Features

- 30 features (V1 to V28 are PCA-transformed)
- `Time`: Seconds elapsed between transactions
- `Amount`: Transaction amount
- `Class`: Target variable (0 = legit, 1 = fraud)

## ⚙️ Technologies Used

- Python 🐍
- NumPy, Pandas
- Scikit-learn
- Matplotlib, Seaborn
- Jupyter Notebook

## 🧠 ML Models Applied

- Logistic Regression
- Decision Tree
- Random Forest
- XGBoost
- LightGBM
- SMOTE (for handling class imbalance)

## 📈 Performance Metrics

- Accuracy
- Precision
- Recall
- F1 Score
- Confusion Matrix
- ROC-AUC Score

## 📌 Highlights

- Handled data imbalance using **SMOTE**.
- Performed **data visualization** to explore fraud trends.
- Compared multiple algorithms to find the best-performing one.
- Saved the final model using **pickle** for deployment.

## 🚀 How to Run

1. Clone the repo:
   ```bash
   git clone https://github.com/yourusername/credit_card_fraud_detection.git
   cd credit_card_fraud_detection
   ```

2. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```

3. Run the notebook:
   ```bash
   jupyter notebook
   ```

## 📂 Output

- `credit_card_model.pkl` – Trained model file.
- Visualizations and metrics inside the notebook.

## 🤝 Contribution

Contributions are welcome! Feel free to fork the repo and submit pull requests.

## 📄 License

This project is licensed under the MIT License.

---

