# Titanic - Machine Learning from Disaster 🛳️

This repository contains three progressively improved models submitted to Kaggle's Titanic survival prediction competition:

## 🔧 Models Included
1. **Baseline Random Forest** – default sklearn settings
2. **Tuned Random Forest** – GridSearchCV optimized
3. **Tuned XGBoost** – grid search + feature engineering

## 📁 Structure
- `notebooks/` – All model development notebooks
- `submissions/` – CSVs ready for Kaggle submission
- `requirements.txt` – Python packages used

## 📊 Results
| Model              | CV Accuracy | Kaggle Rank |
|-------------------|-------------|-------------|
| Baseline RF        | ~82.1%     | #14,329     |
| Tuned RF           | ~83.7%     | #10,729     |
| Tuned XGBoost      | ~84.9%     | **#9,686**  |

## 🚀 Features Used
- Title & Deck extracted from Name/Cabin
- FamilySize, IsAlone
- Pclass, Age, Sex, Fare, Embarked

## 📌 Future Work
- Ensemble Voting Classifier
- LightGBM trials
- Additional feature engineering

---
