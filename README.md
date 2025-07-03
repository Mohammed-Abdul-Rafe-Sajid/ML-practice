# 🚢 Titanic Dataset - Different ML Models (Beginner Friendly)

Welcome to this repository where I’ve implemented and compared various **Machine Learning models** on the classic **Titanic dataset** from Kaggle.

This project is aimed at **beginners** who want to understand how different ML models work, how to preprocess data, and how to evaluate their models effectively — all on one of the most iconic datasets in the ML world.

---

## 📊 Dataset

- Source: [Kaggle Titanic Competition](https://www.kaggle.com/c/titanic)
- Goal: Predict survival of passengers based on features like age, sex, class, etc.
- Type: **Supervised classification problem**

---

## 🔧 Preprocessing & Feature Engineering

All notebooks use:
- Handling missing values (`Age`, `Embarked`, `Fare`)
- Encoding categorical features (`Sex`, `Embarked`)
- Feature engineering (`FamilySize`, `IsAlone`)
- Scaling where necessary (especially for SVM and KNN)

---

## ✅ Models Implemented

| Model Type            | Notebook Link |
|-----------------------|----------------|
| Logistic Regression   | `logistic regression model (titanic).ipynb` |
| Decision Tree         | `decision-tree-classifier-on-titanic-dataset.ipynb` |
| Random Forest         | `random-forest-titanic-dataset.ipynb` |
| K-Nearest Neighbors   | `knn-titanic-dataset.ipynb` |
| Naive Bayes           | `naive-bayes-on-titanic-dataset.ipynb` |
| SVM                   | `svm-on-titanic-dataset.ipynb` |
| XGBoost               | `xgboost-on-titanic-dataset.ipynb` |
| LightGBM              | `lightgbm-on-titanic-dataset.ipynb` |
| CatBoost              | `catboost-with-basic-featureengineering-on-titanic.ipynb` |
| Stacking Classifier   | `stacking-classifier-titanic-dataset.ipynb` |

Each model includes:
- Preprocessing pipeline
- Model training
- Validation accuracy
- Confusion matrix
- Kaggle submission

---

## 📈 Evaluation

- Most models use **train-validation split**
- Final results are submitted to Kaggle
- Accuracy varies between models — ensemble methods like **Stacking, Random Forest, and XGBoost** typically perform better

---

## 📚 How to Use

1. Clone the repo or open notebooks on [Kaggle](https://www.kaggle.com/code).
2. Follow any notebook end to end.
3. Practice modifying models, tuning hyperparameters, and submitting your own predictions.

---

## 💡 Who is this for?

This project is best for:
- Students learning ML for the first time
- Beginners looking for hands-on practice
- Anyone preparing for interviews or Kaggle competitions

---

## 🌟 Author

**Mohammed Abdul-Rafe Sajid**  
📍 Hyderabad, India  
🔗 [Connect on LinkedIn] https://www.linkedin.com/in/mohammed-abdul-rafe-sajid-49a716291/

---

## 🙌 Feel free to fork, star ⭐, and share this repo if it helped you!

