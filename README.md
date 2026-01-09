# Micro-Level Indicators and Machine Learning as an Early Warning Signal Tool: Predicting Loan Defaults with Support Vector Model vs Logistic Regression (by Jessica P. Hutalla)

This project investigates the use of machine learning models to predict borrower-level loan default risk using granular loan-level data. Motivated by the limitations of traditional macroprudential surveillance tools that rely on aggregate indicators, the study emphasizes the role of micro-level predictors as early-warning signals for emerging credit risk.
The project compares the performance of two supervised classification models—Logistic Regression and Support Vector Machines (SVM)—in detecting loan defaults, with particular attention to class imbalance and minority (default) borrower identification.

## Table of Contents

I.	Introduction	
II.	Objectives	
III.	Research Questions	
IV.	Significance of the Study	
V.	Methodology	
VI.	Modeling: Support Vector Machine (SVM)	
VII.	Evaluation & Diagnostics	
VIII.	Modeling: Logistic Regression	
IX.	Comparative Results of the Two Models	
X.	Resulting Confusion Matrix Using SVM only	
XI.	ROC Curve Plot of SVM only	11
XII.	Recommendation for Early Warning Indicator	
XIII.	Role in Surveillance Tools	12

## Data Description
The analysis uses granular loan-level data from Kaggle.com.

## Methodology

1.	Data Preprocessing
    o	Cleaning and feature selection
    o	Handling class imbalance
    o	Train-test split
2.	Models Implemented
    o	Logistic Regression (baseline model)
    o	Support Vector Machine (SVM)
3.	Evaluation Metrics
    o	Precision
    o	Recall
    o	F1-score
    o	Confusion Matrix
    o	ROC Curve and AUC

## Key Results (Preliminary)
•	Logistic Regression performs reasonably well for the majority class but struggles to identify default cases.

•	SVM demonstrates near-perfect performance across both classes, with precision, recall, and F1-scores exceeding 0.96.

