Cervical Cancer Risk Prediction

Overview

This project is my first machine learning project, where I have built a predictive model to assess the risk of cervical cancer based on patient data. The model utilizes various features related to lifestyle, medical history, and personal health records to make predictions.

Features Used

The dataset includes features such as:

Age

Number of sexual partners

First sexual intercourse

Number of pregnancies

Smoking habits (years, packs per year)

Use of hormonal contraceptives (years)

History of sexually transmitted diseases (STDs)

Medical test results (e.g., Hinselmann, Schiller, Cytology, etc.)

Model & Techniques

Data Preprocessing: Handled missing values, standardized numerical features using StandardScaler, and mapped categorical variables appropriately.

Feature Selection: Identified key contributing features using XGBoost feature importance visualization.

Model Used: XGBoost classifier, trained on labeled patient data.

Performance Metrics: Evaluated using accuracy, precision, recall, and confusion matrix.

How to Use

Install Dependencies:

pip install pandas numpy scikit-learn xgboost matplotlib plotly

Run the Model:

python cervical_cancer_prediction.py

Input Patient Data: Provide relevant health parameters for prediction.

Get Prediction: The model will output whether the patient is at high or low risk of cervical cancer.

Challenges Faced

Mapping feature importance from XGBoost to actual column names.

Handling imbalanced data in the dataset.

Ensuring meaningful predictions through proper preprocessing.

Future Improvements

Improve data preprocessing by handling missing values more effectively.

Tune hyperparameters for better model performance.

Implement a web-based UI for easier user interaction.

This project was a great learning experience for me, and I look forward to refining it further. 🚀
