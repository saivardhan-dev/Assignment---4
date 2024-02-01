# Assignment---4
Assignment - 4

## Question - 1

# 1.The script starts by importing the necessary libraries, including Pandas and Matplotlib.
# 2.The fitness dataset is loaded from 'data.csv' into a Pandas DataFrame named df.
# 3.df.describe(): Provides statistical summary of the dataset.
# 4.df.isnull().sum(): Displays the count of missing values in each column.
# 5.Missing values in the 'Calories' column are filled with the mean value.df['Calories'] = df['Calories'].astype(int): Converts the 'Calories' column to integer type.
# 6.df[['Calories', 'Pulse']].agg(['min', 'max', 'count', 'mean']): Calculates statistics for 'Calories' and 'Pulse'.
# 7.df[(df['Calories'] >= 500) & (df['Calories'] <= 1000)]: Filters rows with 'Calories' between 500 and 1000.
# 8.df[(df['Calories'] > 500) & (df['Pulse'] < 100)]: Filters rows based on conditions.
# 9.Scatter plot between 'Duration' and 'Calories' using Matplotlib.


## Question - 2

# 1.The script starts by importing necessary libraries, including Pandas, scikit-learn, and Matplotlib.
# 2.The salary dataset is loaded from 'Salary_Data (2).csv' into a Pandas DataFrame named df2.
# 3.train_test_split: Splits the dataset into training and testing sets for input features (X) and target variable (y).
# 4.LinearRegression(): Initializes a linear regression model.model.fit(): Fits the model to the training data.Predictions are made on both training and testing sets.
# 5.Mean Squared Error (MSE) is calculated for both training and testing sets.
# 6.Scatter plot of the training and testing data with the regression line.
