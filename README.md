# Studies

The example above is a corner case that only pops up if there is a handful (<5) of datapoints. If there is >100 data points, and the data is linear or close to it, then Pearson will be very similar to Spearman.
If you feel that linear regression is a suitable method to analyze your data, then the output of Pearsons will match the sign and magnitude of a linear regression slope (is this strictly correct, anyone?).
If your data has some non-linear components that linear regression won't pick up, then first try to straighten out the data into a linear form by applying a transform (perhaps log e). 
If that doesn't work, then Spearman may be appropriate.
would suggest (on a strictly practical level) that you compute both of the coefficients and look at the differences.
In many cases, they will be exactly the same, so you don't need to worry.

If however, they are different then you need to look at whether or not you met 
the assumptions of Pearsons (constant variance and linearity) and if these are not met, you are probably better off using Spearmans.


It measures the strength of the linear relationship between normally distributed variables. When the variables are not normally distributed or the relationship between the variables is not linear, it may be more appropriate to use the Spearman rank correlation method

Its  calculation  and  subsequent  significance  testing  of  it  requires the following data assumptions to hold: 1.  interval or ratio level;  2. linearly  related;  3. bivariate normally distributed. If  your  data  does  not  meet  the  above  assumptions  then  use  Spearman’s  rank correlation


https://en.wikipedia.org/wiki/Silhouette_(clustering)
https://en.wikipedia.org/wiki/Dunn_index
https://en.wikipedia.org/wiki/K-medoids
