# 🏦 Bank Authentication ML Project

## 📌 Project Overview

This project uses **Machine Learning** to classify banknotes as **Authentic** or **Fake** based on statistical features extracted from banknote images.

A **Random Forest Classifier** is trained on the Banknote Authentication dataset and the trained model is integrated with an interactive **Streamlit web application**.

## 🎯 Objective

The objective of this project is to build a machine learning classification model that can predict whether a banknote is authentic or counterfeit using four statistical features.

## 📊 Dataset

The dataset contains the following input features:

- **Variance**
- **Skewness**
- **Curtosis**
- **Entropy**

### Target Variable

- **Class** — used to classify the banknote.

## 🤖 Machine Learning Model

The project uses:

**Random Forest Classifier**

### Workflow

1. Load the dataset using Pandas
2. Separate features (`X`) and target (`y`)
3. Split the dataset into training and testing sets
4. Train a Random Forest Classifier
5. Make predictions on the test data
6. Evaluate the model using Accuracy Score
7. Save the trained model using Joblib

The trained model is saved as:

```text
classifier.pkl
```

## 📈 Model Evaluation

The model is evaluated using:

- Accuracy Score
- Classification Report

The train-test split uses:

```text
Test Size: 25%
Random State: 42
```

## 🛠️ Technologies Used

- Python
- Pandas
- NumPy
- Scikit-learn
- Random Forest
- Joblib
- Streamlit

## 📁 Project Structure

```text
Bank-Authentication/
│
├── Data/
│   └── BankNote_Authentication.csv
│
├── app.py
├── train.py
├── classifier.pkl
├── requirements.txt
├── README.md
└── .gitignore
```

## 🌐 Streamlit Application

The project includes an interactive Streamlit application.

Users can enter:

- Variance
- Skewness
- Curtosis
- Entropy

The trained Random Forest model then generates a prediction.

## ▶️ How to Run Locally

### 1. Clone the repository

```bash
git clone https://github.com/chandanidevare/Bank-Authentication.git
```

### 2. Navigate to the project

```bash
cd Bank-Authentication
```

### 3. Install dependencies

```bash
pip install -r requirements.txt
```

### 4. Run the Streamlit application

```bash
streamlit run app.py
```

The application will open in your browser.

## 🚀 Future Improvements

- Improve the Streamlit user interface
- Display model performance metrics
- Add data visualizations
- Compare multiple classification algorithms
- Improve input validation
- Deploy the application using Streamlit Community Cloud

## 👩‍💻 Author

**Chandani Devare**

BCA Graduate | Aspiring Data Analyst / Data Scientist

## ⭐ Project

If you find this project useful, consider giving the repository a ⭐ on GitHub.
