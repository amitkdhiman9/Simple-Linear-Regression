# Simple Linear Regression
Simple Linear Regression is a modeling technique that uses one continuous variable to predict an another continuous variable. The variable that is being predicted is called the dependent variable, while the variable that is used to predict is called the independent variable. <br>
**Why is it called "Simple" Linear Regression?** Because it only considers "1" independent variable to predict the dependent variable. <br>
**Why is it called Simple "Linear" Regression?** Because the dependent and the independent variable has a "linear" relationship between them. If one increases by certain units, the other either increases or decreases by certain units depending on whether they have a positive linear relationship between them or a negative linear relationship between them. <br>
**Why is it called Simple Linear "Regression"?** Because the dependent variable is a continuous variable.

I will be working on a **Sales and Market Campaigning Dataset**. This dataset will tell us a company's marketing spend on different typesof marketing. Namely TV, Radio and Social Media. This dataset also includes the Sales number taken over a period period of time.

**Construction:** For the construction part I will be using the Ordinary Least Square (OLS) Method of construction. The OLS method constructs a line from which the sum of the squares of the distance from data points is the least.

**Assumption:** There are 4 important assumptions that are considered in Simple Linear Regression:
1. Linearity: The dependent and independent variable have a linear relationship between them. <br>
2. Independence: All the samples that have been recorded are independent of each other. <br>
3. Normality: The difference between the predicted and actual value of dependent variable for a particular independent variable is called a Residue. Normality assumption states that the Residuals are normally distributed. <br>
4. Homoscedasticity: The Homoscedasticity (constant variance) assumption is that the residuals have a constant variance for all values of X. <br>
Although assumptions are always considered before the model is constructed, some assumptions can only be checked once the model is built. Out of the above mentioned assumptions, first 2 are checked before the model is built and last 2 are checked after the model is built as they involve residuals and residuals can only be calculated after the model is built.
**Evaluation:** For the evaluation part we will try to predict the uncertainity around our model. We will also evaluate how well our dependent and independent variable are related to each other.
