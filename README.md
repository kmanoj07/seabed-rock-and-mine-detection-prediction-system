# Seabed Rock and Mine Detection Prediction System

## Project Overview

In this project, we designed and implemented a seabed Rock and Mine detection prediction system using Logistic Regression. The system aims to classify underwater objects as either rocks or mines based on the SONAR dataset. We achieved an 83.06% accuracy rate on the training data and a 76.19% accuracy rate on the test data. This project was developed using Python, and key libraries utilized include Pandas, NumPy, and Scikit-Learn (SKLearn).

## Dataset

We used the SONAR dataset, which consists of sonar signals bounced off various objects in the ocean, including rocks and metal mines. The dataset contains 208 samples, each with 60 features (sonar signal measurements) and a binary label indicating whether the object is a rock (R) or a mine (M).

## Tools and Technologies Used

- Python
- Pandas: For data manipulation and preprocessing.
- NumPy: For numerical operations and array handling.
- Scikit-Learn (SKLearn): For implementing the Logistic Regression model and evaluating its performance.

## Implementation

### Data Preprocessing

1. Loaded the SONAR dataset into a Pandas DataFrame.
2. Checked for missing values and performed necessary data cleaning.
3. Encoded the binary labels 'R' (rock) and 'M' (mine) as numerical values (0 and 1).
4. Split the dataset into training and testing sets.

### Logistic Regression Model

1. Implemented a Logistic Regression classifier using SKLearn's `LogisticRegression` class.
2. Trained the model on the training data.
3. Evaluated the model's performance on the test data.

### Evaluation

We achieved the following results:

- Training Accuracy: 83.06%
- Test Accuracy: 76.19%

The model demonstrates good predictive performance, indicating its ability to differentiate between rocks and mines in seabed sonar data.

## Usage

To use this Seabed Rock and Mine Detection Prediction System, follow these steps:

1. Install the required Python libraries: Pandas, NumPy, and Scikit-Learn.
2. Load your own SONAR dataset or use the provided dataset.
3. Preprocess the data as described in the "Data Preprocessing" section.
4. Implement the Logistic Regression model as shown in the "Logistic Regression Model" section.
5. Train and evaluate the model on your dataset.

## Conclusion

In this project, we successfully designed and implemented a seabed Rock and Mine detection prediction system using Logistic Regression. The model achieved a training accuracy of 83.06% and a test accuracy of 76.19% on the SONAR dataset. This system can be used to assist in underwater object classification and has potential applications in various marine and defense-related fields.

