# Customer Booking Prediction Project

## Project Overview
This project aims to predict customer bookings for a dataset provided by British Airways. It explores the dataset, engineers features, applies machine learning models, and evaluates their performance to provide accurate booking predictions. The project also includes hyperparameter tuning and data visualization.

## Key Features
1. **Data Exploration and Preprocessing**:
   - Read and inspect the dataset for structure and completeness.
   - Handle missing values.
   - Encode categorical variables.

2. **Feature Engineering**:
   - Created new features like `short_trip`, `last_minute_booking`, and more to enhance model performance.
   - Added flight-related features such as `is_morning_flight` and `is_weekend_flight`.

3. **Model Training and Evaluation**:
   - Trained multiple machine learning models:
     - Random Forest Classifier
     - XGBoost
     - Logistic Regression
     - Support Vector Machines (SVM)
   - Evaluated models using metrics like accuracy, confusion matrix, classification report, and ROC-AUC.

4. **Oversampling and Hyperparameter Tuning**:
   - Addressed class imbalance using SMOTE.
   - Tuned hyperparameters for Random Forest and SVM using GridSearchCV and RandomizedSearchCV.

5. **Visualizations**:
   - Feature importance visualization.
   - Confusion matrix plots.
   - ROC curve and PCA variance explanation.


## Steps to Run the Project
1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/customer-booking-prediction.git
2. Install Dependencies: Ensure Python (>=3.8) is installed. Then, install the required libraries:
   ```bash
   pip install -r requirements.txt
3. Set Up the Dataset: Place the dataset file (e.g., bookings.csv) in the data/ directory.
4. Create a conda virtual environment using conda venv
5. Run the BA booking prediction.ipynb notebook in the terminal 

