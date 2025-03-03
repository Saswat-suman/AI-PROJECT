# Healthcare Dataset Analysis and Model Training

## Project Overview
This project focuses on **Exploratory Data Analysis (EDA)** and **Machine Learning Model Training** using a healthcare dataset. The dataset contains information about patient demographics, medical conditions, billing details, and test results. The goal is to analyze the dataset, visualize key insights, and train multiple machine learning models to predict test results based on patient attributes.

## Dataset Information
- **Source**: Healthcare records
- **Number of Rows**: 55,500
- **Number of Columns**: 15
- **Key Features**:
  - Age
  - Gender
  - Medical Condition
  - Billing Amount
  - Room Number
  - Admission Type
  - Insurance Provider
  - Test Results (Target Variable)

## Exploratory Data Analysis (EDA)
The project includes **four different visualizations**:
1. **Distribution of Billing Amount** – Histogram with Kernel Density Estimation (KDE)
2. **Admission Type vs Billing Amount** – Boxplot
3. **Medical Condition Distribution** – Count plot
4. **Age vs Billing Amount by Gender** – Scatter plot

## Data Preprocessing
- Handled missing values using forward fill.
- Encoded categorical variables using Label Encoding.
- Standardized numerical features using `StandardScaler`.

## Machine Learning Models Used
The following four models were trained and tested:
1. **Random Forest Classifier**
2. **Logistic Regression**
3. **Support Vector Machine (SVM)**
4. **K-Nearest Neighbors (KNN)**

## Model Evaluation
- The models were evaluated based on **accuracy score**.
- The best-performing model was determined and displayed at the end.


## Results
- Each model's accuracy is printed in the console.
- The **best-performing model** is highlighted at the end of execution.

## Future Improvements
- Feature engineering to enhance model accuracy.
- Trying deep learning models for better performance.
- Using advanced hyperparameter tuning techniques.

## Author
Developed as a beginner AI project to explore **EDA** and **Machine Learning Model Training** using real-world healthcare data.

