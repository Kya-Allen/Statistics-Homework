# Statistics-Homework
A repository of IPython Notebooks containing statistical analyses I've done as Homework, as well as reports on each. ( 

at present, the work in this repository is from STAT 414: Environmental Statistics.
The Class covered the following topics:
    - Review of Hypothesis testing and Linear Regression
    - Environmental Sampling Methods
    - Statistical Modeling with Binomial, Poisson, and Exponential distributions
    - Testing for Exponentiality/Normality/Lognormality
    - Polynomial Regression
    - Estimation of Censored Data with Maximum-Likelihood Estimation (and Fisher Information) 
    - Modeling Dose-Response relations / risk modeling
    - Multistage Weibull Model

The Data in the assignments were generally given to us with no context, and so we were asked to make up a situation for our reports

## HW 6 - Testing for Exponentiality:
   * Test for Exponentiality in large sample using a chi-square goodness of fit test
   * Test for Exponentiality in small sample by comparing Linear and Quadratic models on a quantile-quantile plot
   
      <img src="https://github.com/Kya-Allen/Statistics-Homework/blob/main/Visualizations/The%20Data%2C%20Graphed.png">
       
       * this Visualization gives us some intuition that the observed data may match an exponential distribution. For more precise knowledge, we can move on to test this with a chi-square goodness of fit test          
      <img src="https://github.com/Kya-Allen/Statistics-Homework/blob/main/Visualizations/Q%E2%80%93Q%20Plot.png">
       
       * This visualization gives us some intuition that the observed data set may not be exponential (we can infer this because the quantile of our exponential data should have an approximately linear relationship with the the theoretical exponential quantile)          
      <img src="https://github.com/Kya-Allen/Statistics-Homework/blob/main/Visualizations/Q%E2%80%93Q%20Plot%20-%20Quadratic%20Fit%20Comparison.png">
       
       * This visualization shows us that a quadratic model may fit better than a linear model on the Q-Q plot, indicating non-linearity, thus indicating non-exponentiality. For a more precise statistical evaluation, we'll see if the Quadratic term in the Ordinary-Least-Square (OLS) regression equation is statistically significant.
   
## HW 7 - Testing for Lognormality:
* The Lognromal Distribution is a distribtuion whose natural Log (ln) is the Normal Distribtuion. So we can test for Lognormality by computing a natural log transformation of our data, and plotting its quantile against the Normal distribtution quantile

<img src="https://github.com/Kya-Allen/Statistics-Homework/blob/main/Visualizations/Q%E2%80%93Q%20Plot%20-%20testing%20for%20Lognormality.png">

* This visualization indicates that the data may be Lognromal, but for a more precise statistical test, we can once again see if a quadratics term (allowing the line to adjust to any possible non-linearities) is statistically significant. 
