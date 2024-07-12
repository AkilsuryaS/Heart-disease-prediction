# Heart-disease-prediction

![](https://github.com/AkilsuryaS/Heart-disease-prediction/blob/main/images/cover%20pic.jpeg)

# Predicting heart disease using Machine Learning

- This notebook looks into using various Python-based machine learning and data science libraries in an attempt to build a machine learning model capable of predicting whether or not someone has heart disease based on their medical attributes.

**We are going to take the following approach:**
1. Problem definition
2. Data (**UCI Heart Disease dataset**)
3. Evaluation
4. Features
5. Modelling
6. Experimentation

## 1. Problem Definition

In a statement,
> Given clinical parameters about a patient, can we predict whether or not they have heart disease?

## 1. Data
**UCI Heart Disease Dataset from:**https://www.kaggle.com/datasets/redwankarimsony/heart-disease-data


## 3. Evaluation
> If we can reach 95% accuracy during the proof of concept, we'll pursue the project.

## 4. Features
This is where you'll get different information about each of the features in our data.

**Data Description:**


1.id (Unique id for each patient)

2.age (Age of the patient in years)
3.origin (place of study)
4.sex (Male/Female)
5. cp chest pain type ([typical angina, atypical angina, non-anginal, asymptomatic])
6.trestbps resting blood pressure (resting blood pressure (in mm Hg on admission to the hospital))
7.chol (serum cholesterol in mg/dl)
8.fbs (if fasting blood sugar > 120 mg/dl)
9.restecg (resting electrocardiographic results) --Values: [normal, stt abnormality, lv hypertrophy]
10.thalach: maximum heart rate achieved
11.exang: exercise-induced angina (True/ False)
12.oldpeak: ST depression induced by exercise relative to rest
13.slope: the slope of the peak exercise ST segment
14.ca: number of major vessels (0-3) colored by fluoroscopy
15.thal: [normal; fixed defect; reversible defect]
16.num: the predicted attribute

## EDA

The goal here is to find out more about the data and become a subject matter
export on the dataset we're working with.

### Checklist
1. What question(s) are we trying to solve?
2. What kind of data do we have and how do we treat different types?
3. What's missing from the data and how should we handle it?
4. Where are the outliers and how should we treat them?
5. How can we add, change, or remove features from the dataset?

## Machine Learning Models
We're going to try three ML Models:
1. Logistic Regression
2. K-Nearest Neighbours
3. Random Forest Classifier

## Hyperparameter tuning
1. By hand
2. Using Randomized SearchCV
3. Using GridSearchCV

## Evaluating our tuned ML classifier, beyond accuracy

* ROC curve and AUc curve
* Confusion Matrix
* classification_report
* Precision
* Recall
* F1-score

### Feature Importance

"**Which features/variables contribute most to the outcomes of the model and
how did they contribute?**"

Finding feature importance is different for each machine learning model.
