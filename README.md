# KAIBURR_TASK_5
# 📂 Task 5: Consumer Complaint Text Classification

This project classifies consumer complaints into categories like Credit Reporting, Debt Collection, Loans, and Mortgages using classical ML models.

---

## 🔍 1. Exploratory Data Analysis (EDA)

We start by loading the dataset and visualizing the class distribution.

📸 Screenshot:
![EDA Screenshot](screenshot_1.jpg)

---

## ✂️ 2. Text Preprocessing

Each complaint is:
- Converted to lowercase
- Stripped of URLs and special characters
- Tokenized and cleaned of stopwords

📸 Screenshot:
![Preprocessing Screenshot](screenshot_1.jpg)

---

## 🔤 3. TF-IDF Vectorization

We convert clean text into numerical features using TF-IDF with a vocabulary size of 5000.

📸 Screenshot:
![TF-IDF Screenshot](screenshot_2.jpg)

---

## ⚙️ 4. Model Training and Accuracy Comparison

We train three models:
- Logistic Regression
- Naive Bayes
- Linear SVM

📸 Screenshot:
![Model Accuracy Screenshot](screenshot_4.jpg)

---

## 🧪 5. Evaluation (Confusion Matrix & Report)

We evaluate the best model (Linear SVM) using:
- Classification report
- Confusion matrix

📸 Screenshot:
![Confusion Matrix Screenshot](screenshot_5.jpg)

---

## 🧾 6. Predict on a Custom Complaint

We predict a sample complaint:
> "There is a hard inquiry I didn’t authorize."

📸 Screenshot:
![Prediction Screenshot](screenshot_6.jpg)

---

## 🧠 Conclusion

TF-IDF + Linear SVM gives excellent accuracy for text classification problems. Simplicity + Clean data = Great results.

---

## 📂 Folder Structure

