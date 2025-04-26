# Credit Risk Prediction Model
This project builds a machine learning model to predict credit risk ("good" or "bad") using the German Credit Dataset.
The workflow covers data preprocessing, training, hyperparameter tuning, and evaluation using multiple ML models.

## Project Structure
### Data:

german_credit_data_labeled.csv – Raw labeled dataset

### Code Highlights:

Data Cleaning and Preprocessing
Label Encoding categorical features
Feature Scaling (Standardization)
Train-test split (stratified)

### Model Training:

- Random Forest Classifier
- XGBoost Classifier
- Hyperparameter Tuning (GridSearchCV)
- Model Evaluation

### Model Training and Tuning:

- Random Forest Classifier
- Tuned with GridSearchCV (n_estimators, max_depth).
- XGBoost Classifier
- Tuned with GridSearchCV (learning_rate, max_depth, n_estimators).
- Cross-validation (cv=5) is used during tuning.

### Model Evaluation:

- Accuracy
- Classification Report (Precision, Recall, F1-score)
- Confusion Matrix

## Results
You can choose the best model based on the evaluation metrics after testing.
