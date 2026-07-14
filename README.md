# 🚢 Titanic Survival Prediction

A Machine Learning project that predicts whether a passenger survived the Titanic disaster based on passenger information. The project focuses on data preprocessing, training multiple classification models, comparing their performance, and selecting the best-performing model.

---

## 📌 Project Overview

The objective of this project is to build a machine learning model capable of predicting passenger survival using the Titanic dataset. Multiple classification algorithms were implemented and evaluated based on their performance metrics.

---

## 🔄 Project Workflow

### 1. Data Preprocessing

The dataset was preprocessed before training the models by performing the following steps:

- Removed unnecessary and missing values.
- Cleaned the dataset.
- Encoded categorical features into numerical values.
- Applied feature scaling using **MinMaxScaler**.
- Split the dataset into training and testing sets.

---

### 2. Machine Learning Models

The following classification algorithms were implemented and evaluated:

- Logistic Regression
- K-Nearest Neighbors (KNN)
- Decision Tree Classifier
- Support Vector Machine (SVM)

Each model was evaluated using:

- Accuracy Score
- Classification Report
- Confusion Matrix

The model with the best performance was selected as the final prediction model.

---

## 📊 Model Performance

| Model | Accuracy Score |
|--------|---------------:|
| Logistic Regression | 0.80% |
| K-Nearest Neighbors (KNN) | 0.79% |
| Decision Tree Classifier | 0.75% |
| Support Vector Machine (SVM) | 0.74% |

> **Note:** Replace the accuracy values with the results obtained from your notebook.

---

## 📈 Evaluation Metrics

Each model was evaluated using:

- Accuracy Score
- Precision
- Recall
- F1-Score
- Classification Report
- Confusion Matrix

These metrics were used to compare the overall performance of the classification algorithms.

---

## 🛠️ Technologies Used

- Python
- Pandas
- NumPy
- Scikit-learn
- Matplotlib
- Seaborn
- Jupyter Notebook

---

## 📚 Libraries Used

- pandas
- numpy
- scikit-learn
- matplotlib
- seaborn

---

## 📁 Project Structure

```
Titanic-Survival-Prediction/
│
├── titanic.ipynb
├── requirements.txt
├── README.md
└── .gitignore
```

---

## ▶️ How to Run

Clone the repository:

```bash
git clone https://github.com/your-username/Titanic-Survival-Prediction.git
```

Move into the project directory:

```bash
cd Titanic-Survival-Prediction
```

Install the required libraries:

```bash
pip install -r requirements.txt
```

Open the notebook:

```bash
jupyter notebook titanic.ipynb
```

---

## 🎯 Results

After comparing multiple classification algorithms, the model with the highest accuracy and best evaluation metrics was selected for the final prediction.

---

## 🚀 Future Improvements

- Hyperparameter tuning using GridSearchCV.
- Feature engineering for improved prediction accuracy.
- Deploy the model using Streamlit or Flask.
- Perform cross-validation for better model evaluation.

