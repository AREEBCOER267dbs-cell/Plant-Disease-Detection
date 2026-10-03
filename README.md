# 🌱 Plant Disease Detection

## 📌 Project Overview

This project is a simple **Machine Learning-based Plant Disease Detection System** that predicts a plant disease based on common leaf symptoms.

The project uses a **Random Forest Classifier** to classify plants into three categories:

* 🦠 Bacterial Spot
* 🌿 Healthy
* 🍂 Powdery Mildew

The model takes four symptoms as input and predicts the most likely disease.

## 🔍 Input Symptoms

The system uses the following four features:

1. Leaf spots
2. Yellow leaves
3. Plant wilting
4. Leaf damage

Each symptom is represented as:

* `1` → Symptom is present
* `0` → Symptom is absent

## 🤖 Machine Learning Model

**Algorithm:** Random Forest Classifier

The dataset contains **20 samples** and is divided into:

* Training samples: 16
* Testing samples: 4

The model uses 100 decision trees with a fixed random state for reproducibility.

## 📊 Model Performance

The model achieved:

**Test Accuracy: 75.0%**

The project also includes:

* Classification Report
* Confusion Matrix
* Actual vs Predicted Disease Comparison

## 🧪 Example Prediction

For the following symptoms:

```text
Leaf spots = 1
Yellow leaves = 1
Wilting = 0
Leaf damage = 1
```

The model predicts:

```text
Predicted Disease: Bacterial Spot
```

## 🛠️ Technologies Used

* Python
* NumPy
* Pandas
* Matplotlib
* Scikit-learn
* Jupyter Notebook

## 📂 Project Structure

```text
Plant-Disease-Detection/
│
├── Plant-Disease-Detection.ipynb
└── README.md
```

## ▶️ How to Run

1. Open `Plant-Disease-Detection.ipynb`.
2. Run the notebook cells in order.
3. The model will create the dataset and train the Random Forest classifier.
4. The notebook will display model evaluation results.
5. Use the interactive predictor to enter symptoms using `1` or `0`.
6. The system will display the predicted disease.

## ⚠️ Note

This is an **educational machine learning project** using a small, manually created dataset of 20 samples. The 75% accuracy is based only on the project's four test samples and should not be treated as a real-world plant disease diagnosis system.

## 👨‍💻 Project

**Plant Disease Detection using Machine Learning**

Built as a student machine learning project.
