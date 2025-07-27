# Diabetes-prediction-using- Logistic Regression
# Objective 
To develop a predictive model that can classify whether a patient is diabetic or not based on health-related attributes using Logistic Regression.

# Dataset
Source: Kaggle / UCI-style — consists of features like:
Age, BMI, Blood Pressure, Glucose, etc.
Target Variable: diabetes (0 = no, 1 = yes)

# Process Overview
1. Data Preprocessing
Feature-Target Split: Separated features (x) and target variable (y).
Scaling: Standardized the feature set using StandardScaler to normalize data (mean = 0, std = 1).
Train-Test Split: 80% training, 20% testing using train_test_split with stratify=y to maintain class balance.

2. Model Building
Used Logistic Regression from sklearn.linear_model.
Trained the model using training data.
Performed predictions on the test set.

3. Model Evaluation
Accuracy Score: Measured overall performance of the model.
Classification Report: Included precision, recall, and F1-score for both classes.
Confusion Matrix: Visualized the model's true positives, false positives, true negatives, and false negatives.
# Results
Metric    	  Value (Example)
Accuracy	    85% (depends on run)
Precision  	  High precision for non-diabetic class
Recall	      Balanced recall for both classes
F1-Score  	  Good trade-off between precision and recall
Confusion     Matrix	Showed balanced prediction with fewer false negatives

The model performs well in identifying diabetic patients while minimizing false negatives, which is critical in healthcare applications.

# Tech Stack
Language: Python
Libraries: Pandas, NumPy, Matplotlib, Seaborn, Scikit-learn
Environment: Jupyter Notebook
