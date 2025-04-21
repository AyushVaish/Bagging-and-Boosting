# OLA – Ensemble Learning
Abstract
The gig economy has revolutionized urban transportation, yet companies like Ola face substantial challenges in retaining their driver workforce. This case study focuses on predicting driver attrition using machine learning techniques—particularly ensemble methods such as Bagging and Boosting. By leveraging driver demographic information, tenure data, and performance metrics, we aim to build a predictive model that helps the company proactively manage driver churn. The analysis also involves handling imbalanced datasets, imputing missing values via KNN, and engineering new features for improved prediction accuracy.

Problem Description
Ola experiences a high churn rate among its drivers, making recruitment and retention a major business challenge. Acquiring new drivers is expensive, especially when drivers frequently leave or switch to competitors like Uber. High attrition negatively impacts operational stability and morale within the organization. The goal is to use historical driver data to predict the likelihood of driver attrition and take preemptive action, thereby reducing operational disruptions and recruitment costs while improving workforce stability.

Business Questions
What are the key factors driving driver attrition at Ola?

Can we predict whether a driver is likely to leave the organization using past performance and demographic data?

How do driver income trends and ratings correlate with their likelihood of staying or leaving?

What is the impact of location, gender, education level, and age on attrition?

Can machine learning models such as Bagging and Boosting improve the accuracy of attrition prediction?

What actionable insights can be derived to retain drivers and improve their engagement?

Dataset & Column Profiling
MMMM-YY: Reporting Date (Monthly)

Driver_ID: Unique identifier for each driver

Age: Age of the driver

Gender: Male (0), Female (1)

City: City code of the driver

Education_Level: 0 = 10+, 1 = 12+, 2 = Graduate

Income: Monthly average income of the driver

Date_Of_Joining: Date when the driver joined

LastWorkingDate: Date when the driver last worked

Joining_Designation: Designation at the time of joining

Grade: Grade of the driver at the time of reporting

Total_Business_Value: Total business value acquired by the driver in a month (negative values indicate cancellations/refunds or EMI adjustments)

Quarterly_Rating: Quarterly performance rating (1–5, higher is better)

Concepts Tested
Ensemble Learning: Bagging

Ensemble Learning: Boosting

KNN Imputation for Missing Values

Handling Imbalanced Datasets
