# 🔒 Sensitive Information Detection using Logistic Regression

## 📌 Overview

This project uses **Natural Language Processing (NLP)** and **Machine Learning** to automatically detect whether a given text contains **Sensitive** or **Non-Sensitive** information.

The text data is converted into numerical feature vectors using **TF-IDF Vectorization**, and a **Logistic Regression** classifier is trained to perform binary text classification.

---

## 🚀 Features

- Text preprocessing
- TF-IDF feature extraction
- Logistic Regression classifier
- Binary text classification
- Model evaluation using multiple performance metrics

---

## 🛠️ Technologies Used

- Python
- Pandas
- NumPy
- Scikit-learn
- Google Colab

---

## 📂 Dataset

The dataset consists of text samples paired with binary class labels.

| Label | Description |
|-------:|-------------|
| **0** | Non-Sensitive Text |
| **1** | Sensitive Text |

The dataset is used to train a machine learning model capable of identifying whether a text contains sensitive information.

---

## ⚙️ Project Workflow

```
Dataset
      │
      ▼
Data Preprocessing
      │
      ▼
Train-Test Split
      │
      ▼
TF-IDF Vectorization
      │
      ▼
Logistic Regression
      │
      ▼
Prediction
      │
      ▼
Performance Evaluation
```

---

## 📊 Results

| Metric | Score |
|---------|------:|
| Training Accuracy | **99.89%** |
| Test Accuracy | **99.91%** |
| Precision | **99.9%** |
| Recall | **99.9%** |
| F1-Score | **99.9%** |

### Confusion Matrix

```
                Predicted

                0       1
Actual 0      591       0
Actual 1        1      559
```

The model correctly classified **1150 out of 1151** test samples, demonstrating excellent performance on the evaluation dataset.

---

## ▶️ How to Run

1. Clone this repository

```bash
git clone https://github.com/Uu5816/sensitive-Information-Detection.git
```

2. Install the required libraries

```bash
pip install pandas numpy scikit-learn
```

3. Open the notebook

```text
SensitiveInfoDetection.ipynb
```

4. Run all cells to train and evaluate the model.

---

## 📁 Repository Structure

```
Sensitive-Information-Detection/
│
├── SensitiveInfoDetection.ipynb
├── dataset.csv
└── README.md
```

---

## 🔮 Future Improvements

- Implement BERT for contextual text understanding
- Experiment with DistilBERT and RoBERTa
- Perform hyperparameter tuning
- Deploy the model as a Streamlit web application
- Integrate the model into a REST API

---

## 👨‍💻 Author

**Vishwesh Ittam**

GitHub: https://github.com/Uu5816
