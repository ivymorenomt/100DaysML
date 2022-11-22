### Cost Function Analysis

When using linear regression model, we make our predictions by drawing a line that fits approximately to a data set. The question is how do find the line that fits the data set?

The best fit would look like below:

![Graph](https://github.com/ivymorenomt/100DaysML/blob/master/images/sampleofbestfit.png)

Example, we are predicting the house prices using sq ft area(x) and the price of a house(single variable data set).
Supposedly, the prediction line below:
![BadErrors](https://github.com/ivymorenomt/100DaysML/blob/master/images/errors.png)
If the predicting line looks like the above, then this means, we need to find the best fitting line with least errors. This is where the Cost Function comes into picture.

**Cost Function** represents the error between the actual value and the predicting value. The formula will be:

cost = $(x - \hat{y})^2$ - this only looks for difference of one data point. 

    x - actual value
    y is the predicting value.

Multiple data points:

Cost =  $ \frac{1}{2m} \displaystyle\sum_{i=1}^m(y - \hat{y})^2$

    summation of i=1 to m points, where m = no. of datapoints, multiply it by $\frac{1}{2m}$. Why 1 over 2m? it is for averaging purpose.

    m = no of predictions

    $\hat{y}$ = predictions/prediction value

Cost function, is also known as the **Mean-Squared Error**, which measures how close the regression line is to a set of data points.