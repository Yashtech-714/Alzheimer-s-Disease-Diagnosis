# Comparative Study of Machine Learning and Deep Learning Models for Alzheimer's Disease Diagnosis

## Overview

This project presents a comparative study of various Machine Learning (ML) and Deep Learning (DL) models for Alzheimer's disease diagnosis. The objective is to evaluate and compare the performance of different approaches on binary and multi-class classification tasks while ensuring robustness and generalization on unseen data.

## Objectives

* Develop predictive models for Alzheimer's disease diagnosis.
* Compare the performance of traditional ML and DL techniques.
* Perform both binary and four-class classification.
* Improve model robustness through data validation and preprocessing.
* Analyze the strengths and limitations of each approach.

## Dataset

The study utilizes Alzheimer's disease datasets containing clinical and diagnostic features. Extensive data validation was performed to ensure schema consistency and handle missing values and edge cases.

## Methodology

### Data Preprocessing

* Data cleaning and validation
* Handling missing values
* Feature scaling and normalization
* Exploratory Data Analysis (EDA)
* Train-test splitting

### Feature Engineering

* Feature selection techniques
* Correlation analysis
* Dimensionality reduction (if applicable)

### Machine Learning Models

* Logistic Regression
* Support Vector Machine (SVM)
* Decision Tree
* Random Forest
* K-Nearest Neighbors (KNN)
* XGBoost

### Deep Learning Models

* Artificial Neural Network (ANN)
* Multi-Layer Perceptron (MLP)

### Hyperparameter Tuning

* Grid Search
* Cross Validation
* Performance optimization

## Evaluation Metrics

The models were evaluated using:

* Accuracy
* Precision
* Recall
* F1 Score
* Confusion Matrix
* ROC-AUC Score

## Results

| Model         | Task                       | Accuracy |
| ------------- | -------------------------- | -------- |
| Random Forest | Binary Classification      | 98%      |
| XGBoost       | Binary Classification      | 97%      |
| SVM           | Binary Classification      | 96%      |
| ANN           | Multi-Class Classification | 90%      |
| Random Forest | Multi-Class Classification | 88%      |

The study demonstrates that ensemble methods and deep learning architectures provide strong predictive performance for Alzheimer's disease diagnosis, with binary classification achieving up to **98% accuracy** and four-class classification reaching **90% accuracy**.

## Technologies Used

* Python
* Pandas
* NumPy
* Scikit-learn
* TensorFlow / Keras
* Matplotlib
* Seaborn
* Jupyter Notebook

## Project Structure

```
├── data/
├── notebooks/
├── models/
├── results/
├── plots/
├── src/
├── requirements.txt
└── README.md
```

## Key Contributions

* Developed and optimized ML and DL pipelines for Alzheimer's disease diagnosis.
* Conducted comparative analysis across multiple models.
* Applied systematic feature selection and hyperparameter tuning.
* Improved robustness through comprehensive data validation.
* Documented data quality findings and recommendations for maintaining consistency across project iterations.

## Future Work

* Incorporate larger datasets.
* Explore transfer learning techniques.
* Investigate explainable AI (XAI) methods.
* Deploy the best-performing model as a web application.

## Authors

Research Internship – CDSAML, PES University

## License

This project is intended for research and educational purposes.
