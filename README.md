Stroke Prediction – Data Visualization & Preprocessing

* Project Overview :

This project focuses on exploring, cleaning, and preparing a healthcare dataset for future Machine Learning applications in stroke prediction.

The project uses the Stroke Prediction Dataset from Kaggle.

Target Variable: "stroke"

- "0" = No Stroke
- "1" = Stroke

* Project Objectives :

- Understand the structure and characteristics of healthcare data.
- Perform Exploratory Data Analysis (EDA).
- Identify and handle missing values.
- Detect potential outliers.
- Transform categorical features into numerical representations.
- Split data into training and testing sets.
- Apply feature scaling.
- Handle class imbalance using SMOTE.

* Dataset Information :

Dataset: Stroke Prediction Dataset

File Name: "healthcare-dataset-stroke-data.csv"

The dataset contains patient information and health-related features, including:

- Gender
- Age
- Hypertension
- Heart Disease
- Ever Married
- Work Type
- Residence Type
- Average Glucose Level
- BMI
- Smoking Status
- Stroke (Target Variable)

* Technologies & Libraries :

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- Imbalanced-learn

* Project Workflow :

1. Data Loading & Initial Inspection

- Imported the required Python libraries.
- Loaded the dataset using Pandas.
- Inspected the first five rows.
- Examined data types, missing values, and statistical summaries.

2. Exploratory Data Analysis (EDA)

- Visualized the distribution of the target variable.
- Compared stroke distribution across gender, work type, and smoking status.
- Removed the single record with "Other" gender.
- Created histograms and KDE plots for numerical features.
- Generated a correlation heatmap.

3. Data Preprocessing (Cleaning)

- Identified missing values.
- Filled missing BMI values using the median.
- Verified missing values after cleaning.
- Checked and removed duplicate records.
- Dropped the ID column.
- Used a boxplot to investigate outliers in average glucose level.

4. Feature Transformation

- Identified categorical variables.
- Reset the DataFrame index.
- Applied One-Hot Encoding using "pd.get_dummies()".

5. Data Splitting

- Separated features (X) and target (y).
- Split the dataset into:
  - 80% Training Data
  - 20% Testing Data
- Used "random_state=42".

6. Feature Scaling

- Applied StandardScaler.
- Scaled the following numerical features:
  - Age
  - Average Glucose Level
  - BMI
- Fitted the scaler on training data only.
- Transformed both training and testing data.

7. Handling Class Imbalance

- Examined the distribution of the target variable.
- Applied SMOTE to the training data.
- Verified the balanced class distribution.
- Kept the testing data unchanged.

* Final Outcome :

The dataset was cleaned, explored, transformed, and prepared for future Machine Learning model development.

The project demonstrates the importance of data preprocessing and exploratory data analysis in healthcare-related Machine Learning tasks.

* Learning Outcomes :

Through this project, I practiced:

- Data Cleaning and Preparation.
- Exploratory Data Analysis.
- Data Visualization.
- Handling Missing Values.
- Outlier Detection.
- Categorical Encoding.
- Train-Test Splitting.
- Feature Scaling.
- Handling Imbalanced Datasets using SMOTE.

** Author **

## Engineer : Abdelrahman Omar  

Field: Data Science | Machine Learning
