# Titanic Survival Prediction — ML Model Comparison

This is my Project 02 submission for the Pluto Academy AI & ML Internship.

## What this project does

I used the **Titanic Survival Prediction** dataset from Kaggle to build and compare
3 different classification models:

- Cleaned the data (filled missing Age/Embarked, dropped Cabin/Name/Ticket/PassengerId)
  and explained why for each column
- Encoded categorical columns (`Sex`, `Embarked`) into numbers
- Split into an 80/20 train/test set
- Looked at correlation + Random Forest feature importance to see which features actually matter
- Trained 3 models: **Logistic Regression**, **Random Forest**, and **KNN**
- Compared them with Accuracy, Precision, Recall, and F1 Score in one table
- Picked the best model (Random Forest, ~83% accuracy) and plotted its confusion matrix
- Wrote a 5-line conclusion on why it won

## Files in this repo

| File | What it is |
|---|---|
| `Project02_Titanic_ML.ipynb` | The main notebook — all code + outputs already run |
| `titanic.csv` | The dataset used in the notebook |
| `README.md` | This file |

## Dataset source

Titanic — Machine Learning from Disaster, originally from Kaggle
(https://www.kaggle.com/c/titanic), contains passenger info (class, sex, age, fare,
family aboard, etc.) and whether they survived the sinking.

## Tools used

Python, Pandas, NumPy, Matplotlib, Seaborn, scikit-learn, Google Colab

## How to run it yourself

1. Open `Project02_Titanic_ML.ipynb` in Google Colab
2. Upload `titanic.csv` to the Colab file browser
3. Run all cells top to bottom (`Runtime > Run all`)

Every chart, table, and metric will regenerate exactly the same way.
