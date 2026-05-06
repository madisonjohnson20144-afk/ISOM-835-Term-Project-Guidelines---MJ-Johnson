# ISOM-835-Term-Project-Guidelines---MJ-Johnson
Patient Appointment No-Show Prediction

Project Overview
This project applies machine learning techniques to predict whether a patient will miss a scheduled medical appointment. Missed appointments (no-shows) are a major issue in healthcare systems, leading to inefficiencies, increased costs, and reduced access to care for other patients.

Using a real-world dataset, this analysis explores patterns in patient behavior and builds predictive models to help healthcare providers identify high-risk appointments and take proactive action.

Project Objectives
Predict whether a patient will attend or miss an appointment
Identify key factors that contribute to no-shows
Evaluate and compare machine learning models
Provide actionable insights for improving appointment attendance

Dataset
Source: Kaggle – Patient Appointment No-Show Dataset

Description:
The dataset contains over 100,000 medical appointment records, including patient demographics, medical conditions, and scheduling details.
Target Variable:
No-show (Yes = missed appointment, No = attended)

Key Features Include:
Age
Gender
ScheduledDay & AppointmentDay
SMS_received (whether a reminder was sent)
Hypertension, Diabetes, Alcoholism, Handicap

Tools & Technologies
Programming Language: Python
Environment: Google Colab

Libraries:
Pandas
NumPy
Scikit-learn
Matplotlib
Seaborn

Project Workflow
1. Exploratory Data Analysis (EDA)
Analyzed distributions and relationships between variables
Visualized trends using histograms, count plots, and heatmaps
Identified patterns related to no-show behavior

2. Data Preprocessing
Converted categorical variables into numerical format
Engineered a new feature: waiting time (difference between scheduling and appointment dates)
Removed irrelevant columns
Split data into training and testing sets (80/20)

3. Modeling
Two models were implemented and compared:

Logistic Regression
Baseline model
Interpretable and efficient
Random Forest Classifier
Captures complex relationships
Provides feature importance

4. Model Evaluation
Models were evaluated using:

Accuracy
Precision
Recall
F1 Score

Random Forest demonstrated stronger predictive performance compared to Logistic Regression.

Key Insights
Longer waiting times increase the likelihood of no-shows
Patients who did not receive SMS reminders were more likely to miss appointments
Younger patients tend to have higher no-show rates
Predictive models can help identify high-risk patients in advance

Ethical Considerations
Predictions may introduce bias if demographic features are misused
Models should not be used to deny care or disadvantage patients
The system should support proactive outreach (e.g., reminders), not penalization
Transparency and fairness are essential when applying predictive analytics in healthcare
