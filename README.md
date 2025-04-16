#  Diabetes Disease Detector

This project is a Machine Learning-based system that predicts whether a person has diabetes or not based on various medical attributes. 
---

###  What’s included in this project?

-  **Data Preprocessing** (missing values, type conversions)
-  **Exploratory Data Analysis**
  - Glucose vs. Insulin Correlation (Scatter Plot)
  - BMI vs. Number of Diabetes Cases (Bar Plot)
-  **Model Training**
  - **SVC (Support Vector Classifier)** with hyperparameter tuning using GridSearchCV
  - **XGBoost Classifier** with hyperparameter tuning
-  **Evaluation**
  - Confusion Matrix (for both models)
  - ROC-AUC Curve (for both models)
  - Accuracy, Precision, Recall, F1-Score
-  **Interactive Prediction**
  - Accepts user input for medical values
  - Predicts diabetes using the trained model in real-time

---

###  How to Use

1. **Clone the Repo**  
   ```bash
   git clone https://github.com/MayankSethi27/Diabetes_Disease-Detector.git
   cd Diabetes_Disease-Detector
   ```

2. **Install Libraries**  
   ```bash
   pip install pandas numpy matplotlib seaborn scikit-learn xgboost
   ```

3. **Run Notebook**  
   Open `Diabetes_Disease_Detector.ipynb` in Jupyter/Colab and run all cells.

4. **Test User Input**  
   Scroll to the user input section and enter your values to see predictions.

---

###  ML Models Used
- SVC (Support Vector Classifier)
- XGBoost Classifier

---

###  Goal
To use supervised machine learning to assist in early detection of diabetes and help build an end-to-end diagnostic tool for medical professionals or analysts.

---

>  _This project is educational and not intended for real-world medical diagnosis._
