# Data_Analysis_for_Employee_Dataset
The provided code is a Python script that performs data preprocessing, analysis, visualization, and machine learning tasks on a dataset.  
1. It imports the necessary libraries: pandas, numpy, seaborn, and matplotlib.pyplot.
2. Reads the dataset from a CSV file using pandas and displays the first few rows of the dataset.
3. Prints information about the dataset, including the column names and data types.
4. Defines several functions to fix and transform specific columns in the dataset.
5. Applies the defined functions to clean and transform the data in the respective columns.
6. Fills missing values with the mode of each column.
7. Removes any duplicate rows from the dataset.
8. Performs various data analysis tasks and prints the results:
   - Average income of the employees in the dataset.
   - Percentage of employees earning more than $50,000.
   - Percentage of employees who have purchased a bike.
   - Most common occupation in the dataset.
   - Number of employees with no children.
   - Average number of cars owned by employees.
   - Number of employees living in the Pacific region.
   - Average age in the dataset.
   - Percentage of employees with a commute distance of 5-10 miles and own a home.
   - Most common commute distance in the dataset.
   - Most common gender in the dataset.
   - Average income of male employees.
   - Average income of female employees.
   - Percentage of male employees in the dataset.
   - Percentage of female employees in the dataset.
   - Number of employees with 2 or more cars and income < $50,000.
   - Percentage of individuals who are home owners and have purchased a bike.
   - Highest income in the dataset.
   - Number of employees with a partial college education.
   - Number of employees over 50 years old.
   - Percentage of male employees over 50 years old.
   - Number of employees with a skilled manual occupation.
   - ID(s) of rows with the highest income.
   - Number of employees with a graduate degree.
   - Average income in Europe.
   - Average income in the Pacific region.
   - Most common marital status in the dataset.
   - Average income for single individuals.
   - Average income for married individuals.
9. Generates several visualizations using seaborn and matplotlib:
   - Bar chart showing the average income by the number of cars owned.
   - Box plot for the income distribution.
   - Box plot for the age distribution.
   - Heatmap of the count of education levels by occupation.
   - Count plot of occupations.
   - Heatmap of the correlation matrix.
   - Scatter plot of age versus income.
10. Saves the modified dataset to a new CSV file called 'Data_after.csv'.
11. Performs machine learning tasks using logistic regression:
    - Converts categorical variables to numerical using one-hot encoding.
    - Splits the dataset into training and testing sets.
    - Initializes and trains a logistic regression model.
    - Scales the features using standardization.
    - Predicts the income category for the test data.
    - Evaluates the accuracy of the model.
