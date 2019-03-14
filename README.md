# Detect-and-remove-outliers
In statistics, an outlier is an observation point that is distant from other observations

In this repository, will be showed how to detect and remove outliers from your data, using pandas and numpy in python.
I would like to provide two methods in this post, solution based on "z score" and solution based on "IQR".

Something important when dealing with outliers is that one should try to use estimators as robust as possible. The mean of a distribution will be biased by outliers but e.g. the median will be much less

## The Z-score (Wikipedia Definition) 
Is the signed number of standard deviations by which the value of an observation or data point is above the mean value of what is being observed or measured.

## IQR score (Wikipedia Definition)
The interquartile range (IQR), also called the midspread or middle 50%, or technically H-spread, is a measure of statistical dispersion, being equal to the difference between 75th and 25th percentiles, or between upper and lower quartiles, IQR = Q3 − Q1.In other words, the IQR is the first quartile subtracted from the third quartile; these quartiles can be clearly seen on a box plot on the data.It is a measure of the dispersion similar to standard deviation or variance, but is much more robust against outliers.
