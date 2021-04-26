# **Regression**

## Defined As -
### M.M Blair defined Regression as "the measure of the average relationship between two or more variables ".

## What is it ?
### It is a STATISTICAL METHOD that helps us to analyze and understand the relationship between two or more variables .

## When was it First Used ?
### The earliest form of regression was the method of least squares, which was published by Legendre in 1805, and by Gauss in 1809. The term "regression" was coined by Francis Galton in the 19th century to describe a biological phenomenon. The phenomenon was that the heights of descendants of tall ancestors tend to regress down towards a normal average (a phenomenon also known as regression toward the mean).

## Why is it called regression ?
### The general formula of regression is 
### Y=F(x)
### Y- dependent variable 
### X- independent Variable 
### we try to “regress” the value of dependent variable “Y” with the help of the independent variables. In other words, we are trying to understand, how does the value of ‘Y’ change w.r.t change in ‘X’.

## Where is it used ? :
### Regression analysis is used for prediction and forecasting. This has a substantial overlap to the field of machine learning. 
### This statistical method is used across different industries such as,
### Financial Industry- Understand the trend in the stock prices, forecast the prices, evaluate risks in the insurance domain
### Marketing- Understand the effectiveness of market campaigns, forecast pricing and sales of the product. 
### Manufacturing- Evaluate the relationship of variables that determine to define a better engine to provide better performance
### Medicine- Forecast the different combination of medicines to prepare generic medicines for diseases.

## Important Terms used in regression analysis :
**Dependent Variable:** This is the variable that we are trying to understand or forecast.
**Independent Variable:** These are factors that influence the analysis or target variable and provide us with information regarding the relationship of the variables with the target variable.
**outliers:** Outliers are extreme values that fall a long way outside of the other observations
**Multicollinearity:**  it  occurs when independent variables in a regression model are correlated.
**Heteroscedasticity:** When the variation between the target variable and the independent variable is not constant, it is called heteroscedasticity.
overfit: Overfitting means that our algorithm works well on the training set but is unable to perform better on the test sets. It is also known as a problem of high variance.
**underfit:** When our algorithm works so poorly that it is unable to fit even a training set well, then it is said to underfit the data. It is also known as a problem of high bias.
**Interpolation and Extrapolation :** Regression models predict a value of the Y variable given known values of the X variables. 
Prediction within the range of values in the dataset used for model-fitting is known informally as interpolation. 
Prediction outside this range of the data is known as extrapolation. Performing extrapolation relies strongly on the regression assumptions. The further the extrapolation goes outside the data, the more room there is for the model to fail due to differences between the assumptions and the sample data or the true values.
*It is generally advised that when performing extrapolation, one should accompany the estimated value of the dependent variable with a prediction interval that represents the uncertainty. Such intervals tend to expand rapidly as the values of the independent variable(s) moved outside the range covered by the observed data.*

## Power and sample size calculations
### There are no generally agreed methods for relating the number of observations versus the number of independent variables in the model. One rule of thumb 
### conjectured by Good and Hardin is }N=m^{n}, where N is the sample size, n is the number of independent variables and m is the number of observations needed to 
### reach the desired precision if the model had only one independent variable. For example, a researcher is building a linear regression model using a dataset that 
### contains 10000 patients (N). If the researcher decides that five observations are needed to precisely define a straight line (m), then the maximum number of 
### independent variables the model can support is 5, because
### log(10000)/log(5)=5.7227
