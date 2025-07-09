# 🫀 Coronary Artery Disease Detection using Machine Learning

This project uses supervised machine learning techniques to predict the presence of Coronary Artery Disease (CAD) based on patient clinical data. It leverages various classification algorithms to analyze key health indicators and assist in early diagnosis.

## 📊 Dataset

- **Source:** [UCI Heart Disease Dataset](https://archive.ics.uci.edu/ml/datasets/heart+Disease)
- **Records:** 303 patient entries
- **Features Used:** Age, Sex, Chest Pain Type, Resting BP, Cholesterol, Fasting Blood Sugar, ECG, Heart Rate, Exercise-induced Angina, Oldpeak, Slope, Number of Vessels, Thal

## 🚀 Technologies Used

- **Language:** Python  
- **Libraries:**  
  - `Pandas`, `NumPy` – Data loading and preprocessing  
  - `Scikit-learn` – Model building, evaluation, and tuning (Random Forest, SVM, Logistic Regression, KNN)  
  - `Matplotlib`, `Seaborn` – Visualization  
  - `GridSearchCV` – Hyperparameter tuning

## 🧠 ML Models Applied

| Model                | Accuracy  | ROC-AUC  |
|---------------------|-----------|----------|
| Random Forest        | 92.3%     | 91%      |
| Support Vector Machine | 88.7%  | 89%      |
| Logistic Regression  | 85.4%     | 87%      |
| K-Nearest Neighbors  | 84.1%     | 85%      |

## ⚙️ Steps Performed

1. **Data Cleaning:** Handled missing/null values and checked class distribution  
2. **Feature Engineering:** Selected top clinical features impacting CAD  
3. **Model Training:** Trained models with train-test split (80-20)  
4. **Hyperparameter Tuning:** Applied GridSearchCV to optimize model performance  
5. **Evaluation:** Analyzed confusion matrix, classification report, and ROC curve  
6. **Visualization:** Plotted feature importance, correlations, and model comparisons

## ✅ Results

- Best model: **Random Forest**, with **92.3% accuracy** and **91% ROC-AUC**
- False positives reduced by **17%** after hyperparameter tuning
- Project demonstrates potential use in CAD risk screening for healthcare systems

## 🧩 Future Improvements

- Deploy the model using **Streamlit** or **Flask** as a diagnostic web tool  
- Add deep learning model comparison (e.g., ANN with Keras)  
- Integrate real-time data pipeline for hospital use-cases

## 📎 License

This project is for educational and research purposes only. Dataset © UCI Machine Learning Repository.

---

