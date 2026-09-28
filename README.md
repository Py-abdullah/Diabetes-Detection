# Diabetes Detection using Machine Learning

This project is a machine learning-based diabetes detection system developed using patient medical and biochemical data.

The project analyzes health-related features such as age, blood urea, creatinine, HbA1c, cholesterol, triglycerides, HDL, LDL, VLDL, and BMI to classify diabetes-related patient status.

## Project Objective

The objective of this project is to develop a machine learning classification model that can identify diabetes-related patient classes using medical and laboratory measurements.

The project demonstrates the complete machine learning workflow, including:

- Data loading
- Data exploration
- Data cleaning
- Exploratory data analysis
- Feature preparation
- Machine learning classification
- Model evaluation

## Dataset

The dataset contains **1,000 patient records and 14 columns**.

The main features include:

- ID
- Patient Number
- Gender
- Age
- Urea
- Creatinine (Cr)
- HbA1c
- Cholesterol (Chol)
- Triglycerides (TG)
- HDL
- LDL
- VLDL
- BMI
- CLASS

The `CLASS` column is used as the target variable.

## Features

### Patient Information

- **Gender** — Patient gender
- **AGE** — Patient age
- **BMI** — Body Mass Index

### Medical and Biochemical Measurements

- **Urea** — Blood urea measurement
- **Cr** — Creatinine measurement
- **HbA1c** — Glycated hemoglobin measurement
- **Chol** — Cholesterol level
- **TG** — Triglycerides level
- **HDL** — High-density lipoprotein level
- **LDL** — Low-density lipoprotein level
- **VLDL** — Very-low-density lipoprotein level

## Methodology

The project follows these main steps:

1. Import the required Python libraries.
2. Load the dataset using Pandas.
3. Inspect the first rows of the dataset.
4. Check the dataset shape and data types.
5. Generate descriptive statistics.
6. Check for duplicate records.
7. Explore the dataset and target classes.
8. Prepare the data for machine learning.
9. Train classification models.
10. Evaluate the model performance.
11. Analyze the classification results.

## Technologies Used

- Python
- Pandas
- NumPy
- Scikit-learn
- Matplotlib
- Seaborn

## Machine Learning

The project uses machine learning classification techniques to classify patient records based on the available medical and biochemical features.

The target variable is:

```text
CLASS
