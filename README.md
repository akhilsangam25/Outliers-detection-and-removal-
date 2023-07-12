# Outliers-detection-and-removal-
Problem Statement

Outlier detection and removal using:

1).Z-score
2).Percentile

Z-score method

Z-score method can only be applied on columns with normal or almost normal distribution.
Here, If a certain value falls outside of 3 standard deviations we can say it an outlier.
Temperature, CO2 Emissions, Sea Level Rise are almost normal distribution. So, we will choose z-score method for it.

Percentile Method

Percentile - describes how a compare to other scores from the same set.
If a value is in kth percentile, it is greater than k percent of the total values.
In percentile method, if a value is greater than 99/95 percentile(depends upon the problem statement) or less than 1/5 percentile than it is consider an outlier.
