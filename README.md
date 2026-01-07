# Career Switch Prediction

**Author**
- Tanvirul Hoque 

## About The Project
This project explores why employees leave their jobs and predicts if they're likely to switch careers. We used the **Career Switch Prediction Dataset** to analyze factors like experience, education, and company size, aiming to help understand employee turnover better.

## What We Did
We approached this problem in a few key steps:

1.  **Data Analysis:** We started by exploring the data, checking for missing values, and visualizing relationships to see what factors influence career changes.
2.  **Preprocessing:** To get the data ready for modeling, we filled in missing information, converted categorical text into numbers (encoding), and balanced the dataset using **SMOTE** so our models wouldn't be biased.
3.  **Modeling:** We trained and tested several machine learning models to see which one performed best, including:
    *   Logistic Regression
    *   Decision Tree & Random Forest
    *   Gradient Boosting
    *   SVM & KNN
    *   Naive Bayes
    *   Neural Network (TensorFlow/Keras)

We evaluated everything using standard metrics like accuracy, precision, and ROC-AUC scores to ensure our predictions are reliable.

## How to Run
You'll need Python and a few standard libraries installed (`pandas`, `numpy`, `matplotlib`, `seaborn`, `sklearn`, `imblearn`, `tensorflow`).

Simply open the `CSE422_career_switch_prediction.ipynb` notebook and run all the cells. The notebook takes you through the entire process from raw data to final predictions.
