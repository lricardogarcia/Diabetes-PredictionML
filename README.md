# Diabetes Prediction using Machine Learning

This project uses Machine Learning to predict whether a person is **diabetic** or **non-diabetic** based on the **PIMA Diabetes Dataset**. The model used for prediction is the **Support Vector Machine (SVM)**.

## Project Overview

The goal of this project is to predict the likelihood of diabetes in patients based on various medical features, such as the number of pregnancies, glucose level, blood pressure, and more.

## Dataset

The dataset used is the **PIMA Diabetes Dataset**, which includes several medical characteristics and a binary label (`0` for non-diabetic and `1` for diabetic).

- You can download the dataset from this [Google Drive link](https://drive.google.com/drive/folders/16cHz4eXscPLUVRuPQQPFoYgaDTIj6Haj?usp=sharing).

## Dependencies

The following libraries are used in this project:

- `pandas`
- `numpy`
- `scikit-learn`


### Key Features:
- **Dataset**: The PIMA Diabetes dataset provides all the necessary medical features for prediction.
- **Model**: SVM is chosen due to its effectiveness with binary classification problems.
- **Prediction**: Predicts whether an individual is diabetic based on medical records.

To install all dependencies, run the following command:

```bash
pip install -r requirements.txt