
## DAY 3: Linear Regression - The Mathematical Theory

The objective of regression is to **establish if there is a relationship between two variables**.

More statistically, establish if there is a **statistically significant** relationship between the two. 
- Ex: Income and spending, wage and gender, student height and exam scores. 

Then forecast new observations. Can we use what we know about the relationship to forecast unobserved values?
 - Ex: What will the sales be over the next quarter?

### Variable's Roles

Linear equation is the formula that we are going to use:

```
    Y = a + bX
```

Dependent Variable 
 - we denote this as the y variable.
 - This is the variable whose values we want to explain or forecast.
  - this is also known as the **target** variable

Independent Variable
  - the values are independent
  - we denote this as the x variable. 
  - this is also known as the **predictor** variable

so a and b are **linear coefficients**

In statistics, we can use this formula:

y = $\beta_0$ + $\beta_1$ x 

where $\beta_0$ is the **intercept** or constant, and $\beta_1$ which is used to multiply with x. It is also known as the coefficient of x, or the **slope** of x. 

To summarize, we call this linear because it represents a straight line in a bi-dimensional plot.

The linear regression equation will be:
```
    y = ax + b
```


References:
- [Introduction to Simple Linear Regression][youtube-url]
- [Regression Analysis in Machine Learning][linear-url] 
- [Linear Regression in Machine Learning][lin2-url]

[youtube-url]: https://www.youtube.com/watch?v=owI7zxCqNY0&t=122s
[linear-url]: https://www.javatpoint.com/regression-analysis-in-machine-learning
[lin2-url]: https://www.javatpoint.com/linear-regression-in-machine-learning