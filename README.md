# Stroke-Prediction
# Overview
This project develops and compares multiple machine learning models to predict the likelihood of stroke occurrence based on patient demographic and health-related factors.
This project includes 5 main objectives:
- Objective 1: Identify Key Risk Factors
- - To identify and analyse which features in the dataset make the most contribution to stroke risk.
- Objective 2: Predict Stroke Risk
    To build a predictive model which can classify individuals as “stroke” or “no stroke” based on 
their attributes
- Objective 3: Evaluate and Compare Models
    To compare performance and interpretability by applying at least two machine learning models.
- Objective 4: Visualize Risk Patterns
    To show how stroke risk varies across demographic and lifestyle groups by visualisation.
- Objective 5: Handle Imbalance Class
    To apply optimization or balancing techniques to ensure the model performs well.

# Dataset
This dataset contains 5110 records and 12 columns of features which include health and demographic information of individuals collected. For example, the dataset contains patient information such as age, gender, hypertension status, heart disease, BMI, smoking status, and other health indicators.

# Methodology
The project follows a standard machine learning workflow:
- Data preprocessing and cleaning
- Exploratory Data Analysis (EDA)
- Feature engineering and encoding
- Data Spliting and Imbalance class handling
- Model training and evaluation
- Performance comparison

# Models Implemented
- Logistic Regression
- Random Forest Classifier
- XGBoost Classifier

# Optimization Techniques
- GridSearchCV

# Evaluation & Validation Metrics
- Accuracy
- Precision
- Recall
- F1 Score
- ROC-AUC Score
- Confusion Matrix
- ROC Curve Comparison

# Results
The performance of all three models was compared to determine the most effective approach for stroke prediction.

# Technologies
- Python
- Pandas
- NumPy
- Scikit-learn
- XGBoost
- Matplotlib
- Seaborn
- Jupyter Notebook
