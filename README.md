Student Exam Performance Prediction


Project Overview

This project is about predicting students’ exam scores based on different factors such as study hours, attendance, sleep, and other personal and academic conditions.

The main idea is to understand which factors affect student performance the most and then use machine learning models to predict exam scores as accurately as possible.

Dataset

Dataset Name: Student Exam Performance Dataset

Features used in the dataset:

-Hours_Studied

-Attendance

-Parental_Involvement

-Access_to_Resources

-Sleep_Hours

-Previous_Scores

-Motivation_Level

-Internet_Access

-Tutoring_Sessions

-Family_Income

-Teacher_Quality

-School_Type

-Peer_Influence

-Physical_Activity

-Learning_Disabilities

-Parental_Education_Level

-Distance_from_Home

-Gender

Target Variable:

-Exam_Score

-Data Preprocessing

Before building the model, the dataset was cleaned and prepared:

-Missing values were handled using the mode for categorical features

-Categorical data was converted into numerical form using one-hot encoding (pd.get_dummies)

-The dataset structure, shape, and data types were checked to ensure everything was ready for modeling

-Exploratory Data Analysis

-Basic data analysis was performed using Matplotlib and Seaborn. The following visualizations were created:

-Scatter plots

-Histograms

-Correlation heatmap

From the analysis, it was clear that Hours_Studied has the strongest positive relationship with exam scores.

Machine Learning Models
Two models were used to predict exam scores:

-Linear Regression

R² Score: 0.77

MAE: 0.45

-Random Forest Regressor

R² Score: 0.65

MAE: 1.18

Model Comparison

Linear Regression performed better than Random Forest in this case.

This suggests that the relationship between the input features and exam score is mostly linear, which makes Linear Regression a better choice for this dataset.

Technologies Used:-

-Python
-Pandas
-NumPy
-Matplotlib
-Seaborn
-Scikit-learn


Conclusion

This project shows how machine learning can be applied to predict student performance and understand the key factors that influence exam results.
