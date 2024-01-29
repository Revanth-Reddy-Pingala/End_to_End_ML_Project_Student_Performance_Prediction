
# End_to_End_ML_Project_Student_Performance_Prediction

## Problem statement
- This project understands how the student's performance (test scores) is affected by other variables such as Gender, Ethnicity, Parental level of education, Lunch and Test preparation course.

## Steps followed for this Machine Learning Project
- Understanding the Problem Statement
- Dataset
- Data Checks to perform
- Exploratory Data Analysis
- Data Pre-Processing
- Model Training
- Selecting the best model

## Sequence of steps followed until Deployment
- Github and Code Set Up
- Project Structure, Logging And Exception Handling
- Project Problem Statement, EDA And Model Training
- Data Ingestion
- Data Transformation using Pipelines
- Model Training and Model Evaluating Component
- Model Hyper Parameter Tuning
- Created Prediction Pipeline using Flask Web App

## Dataset
- Dataset Source - https://www.kaggle.com/datasets/spscientist/students-performance-in-exams?datasetId=74977
- The data consists of 8 column and 1000 rows.

## Dataset information
- gender : sex of students -> (Male/female)
- race/ethnicity : ethnicity of students -> (Group A, B,C, D,E)
- parental level of education : parents' final education ->(bachelor's degree, some college, master's degree, associate's degree, high school)
- lunch : having lunch before test (standard or free/reduced)
- test preparation course : complete or not complete before test
- math score
- reading score
- writing score

## Data Checks Performed
- Missing values
- Duplicates
- data type
- the number of unique values of each column
- statistics of data set
- various categories present in the different categorical column

## Exploratory Data Analysis (EDA)
- More Description can be found in the [EDA](https://github.com/Revanth-Reddy-Pingala/End_to_End_ML_Project_Student_Performance_Prediction/blob/main/notebook/1%20.%20EDA%20STUDENT%20PERFORMANCE%20.ipynb) and [Modal Training](https://github.com/Revanth-Reddy-Pingala/End_to_End_ML_Project_Student_Performance_Prediction/blob/main/notebook/2.%20MODEL%20TRAINING.ipynb) files.

## Final Conclusions from EDA
- Student's Performance is related with lunch, race, parental level education
- Females lead in pass percentage and also are top-scorers
- Student's Performance is not much related with test preparation course
- Finishing preparation course is benefitial.

## Models used for Training
- Linear Regression
- Lasso
- Ridge
- K-Neighbours Regressor
- Decision Tree
- Random Forest Regressor
- XGB Regressor
- CatBoosting Regressor
- AdaBoost Regressor


## Run Locally in your computer

Clone the project

```bash
  git clone https://github.com/Revanth-Reddy-Pingala/End_to_End_ML_Project_Student_Performance_Prediction
```

Go to the project directory

```bash
  cd my-project
```

After setting up environment and installing packages Run

```bash
  python app.py
```

## Screenshots

<img width="1437" alt="Screenshot 2024-01-29 at 1 59 49 PM" src="https://github.com/Revanth-Reddy-Pingala/End_to_End_ML_Project_Student_Performance_Prediction/assets/125516124/6d62f2dc-70c7-41fd-a5cd-3a41959dc4de">

<img width="1437" alt="Screenshot 2024-01-29 at 2 00 22 PM" src="https://github.com/Revanth-Reddy-Pingala/End_to_End_ML_Project_Student_Performance_Prediction/assets/125516124/e45e947d-6426-44c0-be01-5714ed5de9af">

## Links
[![linkedin](https://img.shields.io/badge/linkedin-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/revanth-reddy-pingala/)
[![Blogger](https://img.shields.io/badge/Blogger-FF5722?style=for-the-badge&logo=blogger&logoColor=white)](https://rrdatadiaries.blogspot.com/)
[![Instagram](https://img.shields.io/badge/Instagram-E4405F?style=for-the-badge&logo=instagram&logoColor=white)](https://www.instagram.com/revanth_reddy.1459/)
