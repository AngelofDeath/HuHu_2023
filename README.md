# HuHu_2023

This repository contains our team's participation (IIMAS TextMining FC) in the HuHu Challenge at IberLEF 2023.

The objective of the HuHu challenge was to examine how humor is used to express prejudice toward minorities, divided into three subtasks, using a dataset of Spanish tweets

* HUrtful HUmour Detection (Subtask 1): Determine whether a prejudiced tweet is intended to be humorous.
* Prejudiced Target Detection (Subtask 2a): Identify the targeted minority groups in each tweet as a multi-label classification task. The groups include women and feminists, the LGBTIQ community, immigrants, racially discriminated individuals, and overweight individuals.
* Prejudice Degree Prediction (Subtask 2b): Predict the degree of prejudice on a continuous scale from 1 to 5 for messages targeting minority groups.

# Our solution

We applied traditional machine learning techniques. First, we computed feature vectors using word embeddings and conducted an ablation study to analyze the contribution of different features to classification performance.

* For Subtasks 1 and 2a, we used Logistic Regression, Support Vector Machines (SVM), and Random Forests.
* For Subtask 2b, we employed Ridge Regression, Lasso, XGBoost, and other models.

For more details about our system, please refer to our article:
"Using Vector Embeddings and Feature Vectors for Humor Identification."
