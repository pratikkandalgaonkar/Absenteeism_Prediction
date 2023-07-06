# Absenteeism Prediction

1.  This Machine Learning project is developed to predict Absenteeism of Employees based on specific characteristics provided to us through data

2.  Analyzed past absenteeism data of employees and Designed a logistic regression model, to predict whether that employee will be absent for more than 3 hours, the 3-hour cap is based on average employee absenteeism throughout the organization, we then used those predictions to visualize the prediction data by comparing it with several important characteristics of our data using Tableau.

3.  Our output is split into two classes one is "Moderately absent" which equates to "0" & other is "Excessively absent" which equates to "1". and then visualize that data using Tableau, so that, we can get insights on our predictions.

4.  The predictions made are based on specific employee characteristics and behavior patterns This information will help us solve various problems the employee might be facing, which is reflecting poorly through their time away during working hours so that we can try and help them as much as we can from the organization, and improve the work environment, So better working environment would result in better output from employees, and we can improve our productivity throughout the organization.

**Key Achievements: Developed a Logistic Regression model with a test accuracy of 0.73**


**The Files in this Repository -**

i. Absenteeism-data.csv = The Original Data file which was used before preprocessing the data for Analysis

ii. Absenteeism_preprocessed.csv = Preprocessed the original Absenteeism-data.csv file to create this file, it contains the preprocessed vesrion of the original file

iii. Absenteeism Predictions.csv = After the analysis on our data by using Logistic Regression algorithm, we added two separate columns to our Absenteeism_preprocessed.csv file, the first column is the probabilities column, it provides us probabilities of getting a "0" or "1" for an employee, so that we can further use those probabilities for visualising our predictions in Tableau public, and second column we attached is Predicted_Absenteeism column, it provides us with the "hard class values" that we got from our analysis i.e "0" or "1".

iv. Absenteeism Preprocessed.ipynb = The preprocessing code for the original Absenteeism-data.csv file, is stored in this Jupyter Notebook file

v. Abseenteeism - Logistic Regression.ipynb = The code to perform analysis on Absenteeism Preprocessed.ipynb file, to create a Logistic Regression model for the data.

vi. Absenteeism Predictions vs features.twbx = It's a  tableau packaged workbook that consists of visualization on the test data in "Abseenteeism - Logistic Regression.ipynb".
