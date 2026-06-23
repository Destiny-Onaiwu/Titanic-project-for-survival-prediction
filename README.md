# Titanic Project for Survival Prediction

A machine learning project to predict survival rates on the Titanic dataset using various classification algorithms.

## Project Overview

This project analyzes the famous Titanic dataset and builds predictive models to determine which passengers were more likely to survive based on features like:
- Age
- Gender
- Passenger class
- Fare paid
- Number of family members aboard
- Port of embarkation

## Dataset

The Titanic dataset contains information about 891 passengers from the Titanic disaster. The dataset includes:
- **Features:** PassengerId, Pclass, Name, Sex, Age, SibSp, Parch, Ticket, Fare, Cabin, Embarked
- **Target:** Survived (0 = No, 1 = Yes)

## Project Structure

```
titanic-project-for-survival-prediction/
├── README.md
├── requirements.txt
├── titanic_ml_pipeline.ipynb
└── data/
    └── titanic.csv (to be downloaded)
```

## Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/Destiny-Onaiwu/titanic-project-for-survival-prediction.git
   cd titanic-project-for-survival-prediction
   ```

2. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```

3. Download the Titanic dataset from [Kaggle](https://www.kaggle.com/c/titanic/data) and place `train.csv` in the `data/` folder

## Usage

Open the Jupyter notebook:
```bash
jupyter notebook titanic_ml_pipeline.ipynb
```

## Models Implemented

- Logistic Regression
- Random Forest Classifier
- Gradient Boosting Classifier
- Support Vector Machine (SVM)
- K-Nearest Neighbors (KNN)

## Evaluation Metrics

- Accuracy
- Precision
- Recall
- F1-Score
- ROC-AUC Score
- Confusion Matrix

## Results

Results and visualizations are generated within the Jupyter notebook, including:
- Feature importance plots
- Confusion matrices
- ROC curves
- Cross-validation scores

## Author

Destiny Onaiwu

## License

MIT License
