# Basic-Statistics
# Measures Of Central Tendency
Central Tendency is a descriptive summary of a dataset through a single value that reflects (center of) the dataset.It id s branch of Descriptive Statistics
# Mean
Mean is central value that is calulated by summing all the data valeus and dividing by the no of values.<br>
example
2,3,4,5,6
Mean = 20/5 = 4
### issue with mean
consider we have data 2,2,2,2,2,2,2,2,2,2 its mean is 20/10 = 2<br>
now consider we have a new data value 100 now the data is 2,2,2,2,2,2,2,2,2,2,100 its mean is 120/11=10.9
# Median
The middle value in a dataset that is arranged in ascending order (from the smallest value to the largest value)

2,2,2,2,2,2,2,2,2,2 its median is 2
2,2,2,2,2,2,2,2,2,2,100 median is also 2
# Mode
Defines the most frequently occurring value in a dataset. In some cases, a dataset may contain multiple modes while some datasets may not have any mode at all.
2,2,2,2,2,2,2,2,2,2 its mode is 2<br>
2,2,2,2,2,2,2,2,2,2,100 mode is also 2<br>
2,3,4,5,6 has no mode<br>
2,3,4,5,6,2,5 has two modes 2,5
# Measures of Dispersion
The mean of 2,2,3,3 is 2.5<br>
The mean of 5,0,0,5 is also 2.5<br>
as we can see for both data mean is sam, hence is not able to uniquely represent data alone, along with central tencdency we need to know about the dispersion of data
# Variance
Variance is the average of squared distance of the data values from mean
# Standard Deviation
square root of variance is standard deviation<br>
it is needed so that the unit of data and dispersion becomes same
# Covariance
when we are dealing with large dataset, we should be able to understand about how and what manner two or more variables interact with each other<br>
Example: distance covered by a car vs Fuel efficiency

So, Covariance measures the **strength of the linear relationship** betweeen two **numerical** random variables X and Y
- A positive covariance indicates positive relationship
- Negative covariance indicates negative relationship
- covariance is 0 if both variables are unrelated

## Limitiations of Covariance
- It is difficult to judge the strength of the relationship(how strong/weak a relation is) from the covariance
- interpreting the value of covariance is purely subjective to the problem you are dealing with
- Basically Covariance just tells us whether the relationship is positive or negative

### Question: How to determine the strength(how strongly two variables are related) of the relationship?
### Answer: Coefficient of Correlation / pearson Coefficient of Correlation / Correlation

- Coefficient of Correlation / pearson Coefficient of Correlation / Correlation gives the strength and direction of **linear relationship** between two **numerical variables**
- Correlation is simply covarince divided by standard deviation of the variables X and Y
- Its range is -1 <= r <= +1 (the closer the value is from +1 or -1, the strong the relation is) 
