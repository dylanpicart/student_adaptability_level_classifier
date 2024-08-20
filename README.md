# Online Education Adaptability Predictor

This project aims to build a supervised machine-learning model that predicts students' adaptability to online education using a dataset containing insightful student demographics.

## Dataset

The dataset used in this project is sourced from Kaggle and contains features that are critical in determining the adaptability scores of students. You can find the dataset [here](https://www.kaggle.com/datasets/mdmahmudulhasansuzan/students-adaptability-level-in-online-education).

## Data Context and Bias

The data was collected during the COVID-19 Pandemic from December 10th, 2020 - February 5th, 2021 in Bangladesh. Please note that the education system in Bangladesh differs from that in the United States, which is reflected in the dataset. 

**Disclaimer:** The dataset contains only 1205 data points, which may not represent the entire population of Bangladeshi students. The data's context and collection details are not fully provided, so its applicability may be limited.

## Hypothesis

This project hypothesizes that a student's age, financial conditions, access to educational support, and technology devices significantly influence their adaptability to online education. We will test this hypothesis through Exploratory Data Analysis (EDA) and by building a Machine Learning Classification Model.

## EDA Insights

Our EDA revealed several trends related to student adaptability levels. For detailed insights, please refer to the demographic & technology context sections in the notebook.

## Machine Learning Models

To analyze the models thoroughly and balance the dataset, both Oversampling and Undersampling were used. One Hot Encoding Feature Engineering was utilized for Binary Classification on the three differing adaptability levels. The models used include Naive Bayes, K Nearest Neighbors, and Random Forests. The model accuracies were determined using Cross Validation and F1 score.

## Conclusion

The **Random Forest Classifier** emerged as the best model for predicting students' overall Adaptability Level based on both Accuracy and F1 Scores. However, the model showed inconsistency in classifying students in true positives and true negatives, leading to significant variations in the F1 Score. To improve this, we plan to refine the features and gather more data. Alternative to Supervised Machine Learning, we can next try to evaluate using Unsupervised Machine Learning Models, such as clustering.
