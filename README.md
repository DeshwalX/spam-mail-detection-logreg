# 📧 Spam Email Detection using Logistic Regression

This project applies Natural Language Processing (NLP) and a Logistic Regression classifier to identify spam messages. It uses TF-IDF vectorization to convert text data into numerical features suitable for machine learning.

---

## 📁 Dataset

The dataset used contains labeled SMS/email messages categorized as 'spam' or 'ham'.  
> **Note:** The dataset (`mail_data.csv`) is not included in this repository.  
> A similar dataset is publicly available here: [Kaggle - Email Spam Classification](https://www.kaggle.com/datasets/balaka18/email-spam-classification-dataset-csv/data).  
To run the notebook, download the dataset and upload it manually to the Colab environment.

---

## 🧠 Model Details

- **Algorithm:** Logistic Regression
- **Text Vectorization:** TF-IDF (Term Frequency-Inverse Document Frequency)
- **Train/Test Split:** 80/20
- **Libraries Used:** `scikit-learn`, `pandas`, `numpy`

---

## 📈 Performance

- **Training Accuracy:** 96.77%
- **Test Accuracy:** 96.68%

---

## 🚀 How to Run

1. Open the notebook in [Google Colab](https://colab.research.google.com/)
2. Upload `mail_data.csv` manually
3. Run all cells to train and evaluate the model


---

## 🔄 Future Improvements

- Evaluate with additional metrics (F1-score, precision, recall)
- Implement alternative models such as Naive Bayes or SVM
- Extend to multi-class or multilingual text classification

---

## 📜 License

This project is licensed under the [MIT License](LICENSE).
