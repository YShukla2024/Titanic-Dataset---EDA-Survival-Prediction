# Titanic-Dataset---EDA-Survival-Prediction
"Titanic EDA &amp; Survival Prediction: Data cleaning, feature engineering (Age, Cabin, Title), and ML modeling (Logistic Regression/Random Forest). Explored survival trends by class, gender, and family size. #DataScience #MachineLearning"
# Titanic Dataset Analysis & Survival Prediction

![Titanic](https://upload.wikimedia.org/wikipedia/commons/thumb/f/fd/RMS_Titanic_3.jpg/1200px-RMS_Titanic_3.jpg)

## 📌 Overview
This project explores the Titanic dataset using **Exploratory Data Analysis (EDA)** and builds a **machine learning model** to predict passenger survival.

## 🔍 Key Steps
1. **Data Cleaning**: Handled missing values in `Age`, `Cabin`, and `Embarked`.
2. **Feature Engineering**:
   - Extracted `Title` (Mr, Mrs, Master) from `Name`.
   - Created `FamilySize` from `SibSp` and `Parch`.
   - Derived `Deck` from `Cabin` letters.
3. **Data Visualization**:
   - Survival rates by `Sex`, `Pclass`, `Age`, and `Fare`.
   - Heatmaps, histograms, and bar plots for trends.
4. **Model Building**:
   - Logistic Regression / Random Forest / XGBoost.
   - Achieved **XX% accuracy** (if applicable).

## 📊 Key Insights
- 🚺 **Women (Sex=female)** had a **~74% survival rate** vs. **~19% for men**.
- 💰 **1st-class passengers (Pclass=1)** had the highest survival rate (**~63%**).
- 👶 **Children (<10)** were prioritized (survival rate **~59%**).
- 👨‍👩‍👧‍👦 **Families of size 2-4** survived more than solo travelers.

## 🛠️ Tools Used
- Python (Pandas, NumPy, Matplotlib, Seaborn)
- Scikit-learn (Logistic Regression, Random Forest)
- Jupyter Notebook

## 📂 Files
- `Data_Science_Task_Titanic_Dataset.ipynb` - Main analysis notebook.
- `train.csv`, `test.csv` - Dataset files (if included).

## 🔗 References
- Dataset source: [Kaggle Titanic Competition](https://www.kaggle.com/c/titanic)
