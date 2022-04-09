# Logistic-Rgression-model-on-HR-Data
This is a machine learning project based on the 'HR-comma-sep.csv' dataset.

This model tries to predict whether or not an employee will resign from the company given a certain parameters. 

This is project uses Logistic Regression to accomplish this task.

The independent variables are:
  a)Satisfaction level: satisfaction level at job of an employee
  b)last_evaluation: Rating between 0 to 1, received by an employee at his last evaluation
  c)number_project: Number of projects, an employee is involved in
  d)average_monthly_hours: Average number of hours in a month, spent by an employee at office
  e)time_spend_company: Number of years spent in the company
  d)Work_accident: 0 - no accident during employee stay, 1 - accident during employee stay
  e)promotion_last_5years: Number of promotions in his stay
  f)Department: Department an employee belongs to
  g)salary: Salary in USD
  
The dependent variable is:
  left: 0 indicates employee stays in the company, 1 indicates - employee left the company
  
Both the dataset and the saved version of the model are provided in this repository. 
The model has an r2 score of 0.802(approximately).
