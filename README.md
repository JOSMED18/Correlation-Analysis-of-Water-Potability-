# Correlation-Analysis-of-Water-Potability-🫗
Simple correlation analysis fulfilling all the assumptions it requires. Data cleaning of outliers and normal distribution test.

When working with correlation analysis and either simple linear regression or logistic regression there are some assumptions that need to be fulfilled in order to continue with analysis. In this case I treat with 2 of them:

❗ Data must be normally distributed

❗ No outliers in data

You will see that the completion of the first assumption allows the completion of the second one. Finally, a conclusion is given where I differentiate causation and correlation. 

*The Python code and complete analysis is inside the notebook.*

## _Insights_ 

The results from the normal distribution test where as follows:

![image](https://user-images.githubusercontent.com/101015892/211207453-5a610345-acb2-47ca-b87a-55e6dd2c0759.png)

Where a p value less than 0.05 means the data is normally distributed. This helps to identify outliers and replace them with either the mean, mode or median. In this case, the mean is used.

![image](https://user-images.githubusercontent.com/101015892/211207390-0dacd7e3-1c00-41b7-8987-e0121db15690.png)

This outliers where replaced for the mean since data follows a normal distribution in those columns.

Once this assumptions were fulfilled, a correlation analysis was performed where the correlation between variables was weak, and precise conclusions cannot be driven. So more data has to be collected in order to find out which parameter or problem should be attacked first. 

![image](https://user-images.githubusercontent.com/101015892/211207672-497a5230-c926-41de-9645-eee32413b13c.png)

A coefficient near to 0 means there is no correlation between variables, and a coefficient near 1 means a perfect linear correlation.

#### _The end_
