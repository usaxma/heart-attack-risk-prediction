# Heart Attack Risk Prediction

Predict whether a patient is at higher risk of heart attack from clinical measurements (UCI Heart Disease data).

The notebook trains several classifiers, compares accuracy, then uses **EvalML** AutoML as a second pass.

## Skills

- Clinical EDA (age, sex, chest pain, cholesterol, max heart rate, ST depression)
- Train/test split and encoding
- Logistic Regression, Decision Tree, Random Forest, KNN, SVM, AdaBoost
- Model comparison table
- EvalML AutoML search

## Dataset

`heart.csv` is included (303 rows, 14 columns). Target: `0` = lower chance, `1` = higher chance.

## Run

```bash
pip install -r requirements.txt
jupyter notebook Heart_Attack_Risk_Predictor.ipynb
```

## Structure

```
heart-attack-risk-prediction/
├── Heart_Attack_Risk_Predictor.ipynb
├── heart.csv
├── requirements.txt
└── README.md
```

## Notes

This is a small educational dataset. It is not a medical device and should not be used for clinical decisions.
