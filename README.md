# Campus_Placement_Prediction_System
Campus Placement Prediction System is a predictive analytics system that leverages supervised learning models to determine whether a student is likely to be placed in campus recruitment. The project includes robust data preprocessing, exploratory data analysis (EDA), multiple classification algorithms, and model evaluation. It is designed for scalability and deployment as a backend API or dashboard.

## Key Features
* Predicts placement status (Placed / Not Placed) using real-world student data.
* Implements and compares multiple ML models:
* Logistic Regression
* Decision Tree Classifier
* Random Forest Classifier
* K-Nearest Neighbors (KNN)
* Achieves ~88% accuracy using ensemble-based methods.
* Performs feature engineering: encoding, correlation filtering, and anomaly handling.
* Visualizes key patterns in placement trends using statistical plots.

## Dataset Description
Dataset link (https://www.kaggle.com/benroshan/factors-affecting-campus-placement)

Attributes in the dataset:




## Workflow
1.Data Preprocessing
* Categorical encoding (gender, specialisation, workex).
* Null value handling.
* Outlier detection (optional).
* Feature selection via correlation heatmaps.

2.Exploratory Data Analysis
* Distribution analysis of placement by gender, stream, CGPA.
* Pair plots, box plots, and count plots.
* Correlation matrix.

3.Model Training & Evaluation
* Train-test split (typically 80/20).
* Trained multiple classification models.
* Evaluated via:
    * Accuracy Score
    * Confusion Matrix
    * Precision, Recall, F1-score

4.Deployment Ready Design
* Modular notebook structure for easy API or dashboard integration.
* Prepped for integration with Flask or Streamlit backend.
