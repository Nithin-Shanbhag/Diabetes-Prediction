# Diabetes-Prediction

## Goal: Predict whether or not a patient has diabetes, based on certain diagnostic measurements included in the dataset.

## Housing parameters:
```
- Pregnancies - Number of times pregnant
- Glucose - Plasma glucose concentration a 2 hours in an oral glucose tolerance test
- BloodPressure - Diastolic blood pressure (mm Hg)
- SkinThickness - Triceps skin fold thickness (mm)
- Insulin - 2-Hour serum insulin (mu U/ml)
- BMI - Body mass index (weight in kg/(height in m)^2)
- DiabetesPedigreeFunction - Diabetes pedigree function
- Age - Age (years)
- Outcome - Class variable (0 or 1) 268 of 768 are 1, the others are 0
```

## Software and tool requirement
1. [Github Account](https://github.com)
2. [VS Code IDE](https://code.visualstudio.com/)
3. [GitCLI](https://git-scm.com/book/en/v2/Getting-Started-The-Command-Line)

### Step 1:
Download the dataset from Kaggle: [Pima Indians Diabetes Database](https://www.kaggle.com/datasets/uciml/pima-indians-diabetes-database/data?select=diabetes.csv)

### Step 2:
Check missing values (nan)

### Step 3:
Perform correlation

### Step 4:
Change dependent variable from boolean to number - 0 or 1
Check for imbalanced dataset

### Step 5:
Perform train test split

### Step 6:
Impute mean value of the respective feature for the values that are not possible for the feature.

### Step 7:
Apply Random Forest Classifier on train set, predict on test set and check accuracy score - 0.736

### Step 8:
Apply XGBoost classifier algorithm with hyperparameter optimization on train set, predict and check the metrics - acc score - 0.76, cv score - 0.78