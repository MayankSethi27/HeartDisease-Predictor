# Heart Disease Prediction

## Project Overview

This project is aimed at predicting the likelihood of heart disease in patients based on various medical attributes. The project uses machine learning models, including Random Forest and Logistic Regression, to classify whether a patient has heart disease or not. 

The dataset used contains features like age, sex, chest pain type, resting blood pressure, cholesterol levels, and more.

## Models Used

1. **Random Forest Classifier**: A robust ensemble learning model used for classification tasks.
2. **Logistic Regression**: A statistical model used for binary classification.

### Evaluation Metrics:
- **Accuracy Score**
- **Confusion Matrix**: Used to evaluate the classification performance and to visualize the performance of the models.
- **ROC AUC Curve**: A curve to evaluate the classifier's performance at various thresholds.

Both the confusion matrix and ROC AUC curve were created within the project file to compare the performance of the models.

## Features

- Data preprocessing and cleaning.
- Hyperparameter tuning using `GridSearchCV` for both models.
- Visualizations, including Confusion Matrix and ROC AUC curve.
- Command-line interface for user input to predict heart disease.

## How to Run the Code

1. Clone the repository:

   ```bash
   git clone https://github.com/MayankSethi27/HeartDisease-Predictor.git
   ```

2. Navigate into the project directory:

   ```bash
   cd HeartDisease-Predictor
   ```

3. Install the required libraries (use a virtual environment if needed):

   ```bash
   pip install -r requirements.txt
   ```

4. Open and run the Jupyter Notebook `Heart_Disease_Predictor.ipynb` to see the entire workflow, from data preprocessing to model evaluation.

## Data Description

The dataset contains the following features:

- **Age**: Age of the patient
- **Sex**: Gender of the patient
- **ChestPainType**: Type of chest pain experienced
- **RestingBP**: Resting blood pressure
- **Cholesterol**: Serum cholesterol levels
- **FastingBS**: Fasting blood sugar level
- **RestingECG**: Resting electrocardiographic results
- **MaxHR**: Maximum heart rate achieved
- **ExerciseAngina**: Whether the patient experienced exercise-induced angina
- **Oldpeak**: Depression induced by exercise relative to rest
- **ST_Slope**: Slope of the peak exercise ST segment

## Conclusion

The models trained and evaluated in this project can predict whether a patient has heart disease based on medical attributes. The performance was evaluated using various metrics, including ROC AUC and confusion matrix, with the models showing good accuracy in predicting heart disease.
