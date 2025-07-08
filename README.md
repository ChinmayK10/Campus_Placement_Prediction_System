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

### Attributes in the dataset:
Here are all the attributes (columns) present in the campus placement dataset:
* sl_no – Serial number (identifier)
* gender – Gender of the student (Male/Female)
* ssc_p – Secondary Education Percentage (10th grade)
* ssc_b – Board of Education for SSC (Central/Other)
* hsc_p – Higher Secondary Education Percentage (12th grade)
* hsc_b – Board of Education for HSC (Central/Other)
* hsc_s – Specialization in HSC (Science, Arts, Commerce)
* degree_p – Percentage in Undergraduate Degree
* degree_t – Type of Undergraduate Degree (Sci & Tech, Comm & Mgmt, Others)
* workex – Work Experience (Yes/No)
* etest_p – Employability Test Percentage
* specialisation – MBA Specialization (Marketing & Finance, Marketing & HR)
* mba_p – MBA Percentage
* status – Placement Status (Placed/Not Placed)
* salary – Salary offered (if placed)



## Workflow
1. Data Preprocessing
* Categorical encoding (gender, specialisation, workex).
* Null value handling.
* Outlier detection (optional).
* Feature selection via correlation heatmaps.

2. Exploratory Data Analysis
* Distribution analysis of placement by gender, stream, CGPA.
* Pair plots, box plots, and count plots.
* Correlation matrix.

3. Model Training & Evaluation
* Train-test split (typically 80/20).
* Trained multiple classification models.
* Evaluated via:
    * Accuracy Score
    * Confusion Matrix
    * Precision, Recall, F1-score

4. Deployment Ready Design
* Modular notebook structure for easy API or dashboard integration.
* Prepped for integration with Flask or Streamlit backend.

## Technologies used
* Language: Python 3.x
* ML/DS Libraries: scikit-learn, pandas, numpy
* Visualization: seaborn, matplotlib
* Notebook Environment: Jupyter / Google Colab

## Future Improvements
* Hyperparameter tuning (GridSearchCV, RandomizedSearchCV)
* Integration with a Flask API + UI dashboard
* Model explainability with SHAP / LIME
* Adding salary prediction as regression extension

## Results
Multiple classification algorithms were trained and evaluated to determine the most effective model for predicting student placements. Logistic Regression and Decision Tree classifiers offered solid baseline performance, effectively identifying linear and rule-based patterns in the data. K-Nearest Neighbors provided reasonable results but was slightly more sensitive to scaling and less interpretable.

The Random Forest Classifier outperformed the others in terms of accuracy and generalization, making it the preferred choice for deployment. It captured complex feature interactions and demonstrated robust performance across various data splits. Overall, the ensemble-based approach proved most reliable for this classification task.

## License
This project is open-source under the MIT License.
