# Ml-week-3.2
internship at A &amp; D
Feature Engineering and Unsupervised Learning Project
Overview
This project is part of my "Introduction to Machine Learning" course, focusing on feature engineering and unsupervised learning. The goal is to develop skills in creating and selecting features to improve machine learning model performance using a synthetic dataset generated with sklearn.

Dataset
The dataset is generated using sklearn.datasets.make_classification with the following parameters:

1000 samples
20 features (2 informative, 10 redundant, 8 noisy)
Single cluster per class
Class weight imbalance (99% of one class)
No label noise
Activities
1. Feature Creation
Polynomial Features: Generated interaction terms and polynomial features to enrich the dataset.
2. Feature Selection
Tree-based Feature Importance: Used Random Forest to determine feature importance.
Recursive Feature Elimination (RFE): Selected top features iteratively.
SelectKBest (Chi-Square): Selected top features based on Chi-Square statistics, after normalizing features to non-negative values.
3. Model Building
Built and evaluated classification models using Random Forest with different feature sets:
Baseline Model: Using all features.
RFE-selected Features Model.
SelectKBest-selected Features Model.
Results
The project demonstrates the significant impact of feature engineering and selection on model performance. The Jupyter notebook includes detailed steps, code, and performance metrics for each model.

Usage
Clone the repository and run the Jupyter notebook to see the full feature engineering process and model evaluations.

bash
Copy code
git clone https://github.com/yourusername/feature-engineering-unsupervised-learning.git
cd feature-engineering-unsupervised-learning
jupyter notebook
Requirements
Python 3.x
NumPy
Pandas
Scikit-learn
Matplotlib
Install the required packages using:

bash
Copy code
pip install numpy pandas scikit-learn matplotlib
License
This project is licensed under the MIT License. See the LICENSE file for details.

Contact
For any questions or suggestions, please contact gsahabrana@gmail.com or connect with me on linkedin https://www.linkedin.com/in/hasnat-aziz-407259256/
