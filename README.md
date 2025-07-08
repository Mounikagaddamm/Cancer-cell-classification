# 🧬 Cancer Cell Classification using Scikit-learn

> Predict whether a tumor is **malignant** or **benign** using the **Breast Cancer Wisconsin dataset** and a **Gaussian Naive Bayes classifier**.

## 📌 Project Overview

This project applies **supervised machine learning** techniques to classify cancerous cells using **Scikit-learn**. The model is trained on real medical diagnostic data and achieves **94.15% accuracy**, making it a potential candidate for **early detection tools** in healthcare.

## 🎯 Objectives

- Classify tumors as **malignant** (cancerous) or **benign** (non-cancerous)
- Use a simple yet effective model (Naive Bayes) for fast and interpretable predictions
- Visualize dataset and class distribution
- Evaluate model performance with accuracy metrics

## 🧠 Dataset

- **Name:** Breast Cancer Wisconsin (Diagnostic) Dataset
- **Source:** sklearn.datasets.load_breast_cancer()
- **Features:** 30 numeric features (e.g., mean radius, texture, smoothness)
- **Target:** 0 = malignant, 1 = benign


## 📊 Tools & Libraries

- Python  
- Pandas  
- Matplotlib  
- Scikit-learn  
- GaussianNB (Naive Bayes classifier)

## 🚀 How It Works

1. **Data Loading**  
   Loads the breast cancer dataset from `sklearn.datasets`.

2. **Exploration & Visualization**  
   - Displays feature info and summary statistics  
   - Visualizes target class distribution using pie chart

3. **Data Preprocessing**  
   - Splits data into training (67%) and testing (33%) sets

4. **Model Training**  
   - Trains a **Gaussian Naive Bayes classifier**

5. **Evaluation**  
   - Predicts on test set  
   - Evaluates with accuracy_score 
   - **Result:** 94.15% accuracy

## ✅ Results

- **Accuracy:** 94.15%  
- The model effectively distinguishes between benign and malignant tumors based on input features.



## 📌 Future Improvements

- Use more complex models (Random Forest, SVM) for comparison  
- Add ROC curves, confusion matrix, and F1-score  
- Build a front-end interface for doctors or lab techs

## 🤝 Contributing

Feel free to fork the repo, raise issues, or submit pull requests for improvements.

## 📬 Contact

**Gaddam Mounika**  
📧 gaddamm334@gmail.com  
🔗 [LinkedIn](https://www.linkedin.com/in/mounika-gaddam) | [GitHub](https://github.com/Mounikagaddamm)





