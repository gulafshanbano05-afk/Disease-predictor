# Disease-predictor
The Disease Predictor Model is a machine learning–based system designed to analyze patient health data and predict the likelihood of specific diseases. It uses input features such as age, gender, medical history, symptoms, and clinical test results, which are preprocessed and scaled before being passed into a trained predictive algorithms.

1. Data Preprocessing

Upload dataset from Kaggle to Google Colab.

Handle missing values by filling numeric columns with the mean.

Encode categorical features using One-Hot Encoding.

Normalize numeric features with StandardScaler.

2. Exploratory Data Analysis (EDA)

Histograms to visualize distribution of features.

Heatmap to analyze correlations between features.

3. Model Training

Logistic Regression

Accuracy ~ 84.7%

Evaluated using accuracy score, confusion matrix, and classification report.

Random Forest Classifier

Higher accuracy and robustness.

Feature importance visualization to identify key predictors.

4. Model Saving

Trained Random Forest model and StandardScaler are saved using Joblib.

A sample user input template (Heart_user_template.csv) is created for predictions.

5. Prediction with User Data

Users can upload their own dataset (heart_dataset.csv).

Preprocessing steps are applied to align user data with training data.

Model predicts whether the patient is likely to have heart disease.

 Results

Logistic Regression Accuracy: ~84.7%

Random Forest Accuracy: (Varies, usually higher than Logistic Regression)

Feature importance plot shows top contributing health indicators.
