# Description
- The objective of this dataset is to build a predictive model for diagnosing diabetes in female patients who are at least 21 years old Pregrenant ladies and of Pima Indian heritage.
- The model should predict whether a patient has diabetes (Outcome = 1) or does not have diabetes (Outcome = 0) based on several diagnostic measurements, including glucose level, blood pressure, skin thickness, insulin level, BMI, diabetes pedigree function, and age.

# Data description
1. Pregnancies = Number of pregnancies
2 Glucose = Glucose level in blood
3 BloodPressure = Blood pressure measurement
4 SkinThickness = Thickness of the skin
5 Insulin = Insulin level in blood
6 BMI = Body mass index
7 DiabetesPedigreeFunction = Diabetes percentage
8 Age = Age
9 Outcome = Final result (1: Yes, the individual has diabetes; 0: No, the individual does not have diabetes)

# Project Workflow:
1. Data Preparation:
- Loaded the dataset using mlbench.
- Visualized key variables like glucose levels with histograms.
- Explored data statistics and structure.

2. Data Preprocessing:
- Handled missing values by removing rows with NaN.
- Encoded the target variable (diabetes) into binary (0 for negative, 1 for positive).
- Split the data into training (70%) and testing (30%) sets.

3.Model Training:
- Built a decision tree classifier using the DecisionTreeClassifier from sklearn.
- Visualized the decision tree structure.
- Evaluated the model using a confusion matrix and accuracy score.

4.Hyperparameter Tuning:
- Performed grid search with cross-validation to find the best hyperparameters.
- Optimized the max_depth and min_samples_split for better model performance.

# Technologies Used:
- Language: Python
- Libraries:
 - Data Analysis: pandas, numpy
 - Machine Learning: scikit-learn
 - Visualization: matplotlib, seaborn

# Key Results:
- Baseline Accuracy: Achieved with the initial decision tree model.
- Optimized Accuracy: Improved after tuning hyperparameters.

# Contact:
- Feel free to reach out with suggestions or feedback:
- Email: ankuvashisht.4@gmail.com
- LinkedIn: https://www.linkedin.com/in/ankita-vashisht-6209a51a2/
- GitHub: https://github.com/Vashishtankita
