# Supervised_learnin_1_Reg_fit_pred:
I fit a linear regression and predict life expectancy using just one feature. 
In this exercise, I used the 'fertility' feature of the Gapminder dataset (.csv file is loaded in the folder). 
Since the goal is to predict life expectancy, the target variable here is 'life'. 
A scatter plot with 'fertility' on the x-axis and 'life' on the y-axis has been generated. Regression line is fit
on this scatter plot and noticed a very strong -ve correlation. 
This negative correlation is varified by computing pearson's coefficients.

# Important module for this excercise
1. pandas 
2. matplotlib.pyplot
3. LinearRegression from sklearn.linear_model
4. numpy 
5. pearsonr from scipy.stats 
