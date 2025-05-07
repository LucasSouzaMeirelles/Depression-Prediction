1.Summary: This project's goal was to develop a ML model to predict the probability of a person's developing depression based on features like age, job satisfaction and sleep hours.

2.Results: The final model (final_model.pkl) is a logistic regression model fit on the binary target variable "depression" (0/1), and several numeric and categorical features. The final model boasts precision, recall and f1 score above 90% for both classes.

3.Approach:

3.1-DW: Data Wrangling

3.1.1-Input: Depression Professional Dataset.csv (raw data)

3.1.2-Output: wrangled_data.csv

3.2-EDA: Exploratory Data Analysis and Visualization

3.2.1-Input: wrangled_data.csv

3.2.2-Output: analyzed_data.csv, dietary_habits_encoding.csv, sleep_duration_encoding.csv

3.3-MDE: Model Development and Evaluation

3.3.1-Input: analyzed_data.csv

3.3.2-Output: final_model.pkl

3.4-Deliverable: A function to generate predictions based on the developed model.
