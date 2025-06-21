# 📧 Spam Email Detection using Logistic Regression

This project applies Natural Language Processing (NLP) and a Logistic Regression classifier to identify spam messages. It uses TF-IDF vectorization to convert textual data into numerical features suitable for machine learning.

---

## 📁 Dataset

The dataset contains labeled SMS or email messages classified as either 'spam' or 'ham'.  
> **Note:** The dataset (`mail_data.csv`) is not included in this repository.  
> A similar dataset is available at [Kaggle - Email Spam Classification](https://www.kaggle.com/datasets/balaka18/email-spam-classification-dataset-csv/data).  
To run the notebook, download the dataset and upload it manually in the Colab environment.

---

## 🧠 Model Overview

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
2. Upload the dataset file (`mail_data.csv`) when prompted
3. Run all cells to train and evaluate the model

[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/DeshwalX/spam-mail-detection-logreg/blob/main/spam_mail_detect.ipynb)

---

## 🔄 Future Scope

- Evaluate performance using precision, recall, and F1-score
- Compare results with other classifiers (e.g., Naive Bayes, SVM)
- Add support for email metadata and subject classification
- Implement basic spam message visualization or word cloud

---

## 📜 License

This project is licensed under the [MIT License](LICENSE).

## 👤 Author

- **Name:** Abhijeet Deshwal  
- **GitHub:** [@DeshwalX](https://github.com/DeshwalX)
