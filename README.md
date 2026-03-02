# Heart Disease Prediction 🫀
# 📝 Project Overview
This project aims to build a robust Machine Learning pipeline to predict the presence of heart disease based on clinical parameters. By leveraging a variety of classification algorithms—ranging from linear models to advanced gradient boosting frameworks—this project explores which features are the most significant predictors of cardiovascular health.

# 📊 Dataset Features
The dataset includes several clinical features used to determine heart health:

Age & Sex: Demographic information.

Chest Pain Type (CP): Categorized levels of chest pain.

Trestbps: Resting blood pressure.

Chol: Serum cholesterol in mg/dl.

FBS: Fasting blood sugar > 120 mg/dl.

Restecg: Resting electrocardiographic results.

Thalach: Maximum heart rate achieved.

Exang: Exercise-induced angina.

Oldpeak: ST depression induced by exercise relative to rest.

Slope: The slope of the peak exercise ST segment.

Thallium: Stress test results.

Target: Heart Disease (Presence or Absence).

# 🛠️ Tech Stack & Methodology
# Data Engineering
Manipulation: Pandas, Numpy.

Visualization: Matplotlib, Seaborn.

Preprocessing: MinMaxScaler, Train_Test_Split.

Progress Tracking: tqdm.

# Model Selection
The project evaluates a wide spectrum of classifiers:

Baseline Models: Logistic Regression, Naive Bayes (GaussianNB).

Instance-based: K-Nearest Neighbors (KNN), Support Vector Classifier (SVC).

Tree-based: Decision Trees, Random Forest, Extra Trees.

Advanced Boosting: XGBoost, CatBoost, LightGBM, AdaBoost, GradientBoosting.

Ensemble Methods: VotingClassifier and StackingClassifier for meta-learning.

# 📈 Evaluation Metrics
To ensure the model is reliable for medical contexts, we evaluate using:

Accuracy & Balanced Accuracy

Precision & Recall (Focusing on minimizing False Negatives).

F1-Score

Confusion Matrix

ROC-AUC & Precision-Recall Curves

Confusion Matrix Analysis
