# Task 3 

In this lab we will use data collected from the Sr90 source used in the previous labs. The number of β− decay reactions, x, occurring from our Sr90 sample within a given time interval ∆t, was collected for different lengths of time T.

If we look at the Poisson distribution:

![Poisson](Poisson.png)

We can find the rate, r, if we fit plot out μ values found from each histogram versus the time interval ∆t.
######## TO DO:
-   [1] [Download Sr90 root Data](http://boson.physics.sc.edu/~nick/root_data.html)
-   [2] Plot data from all the files into histograms.
-   [3] Fit Poisson function to all the histograms.
-   [4] Extract the value μ for all the histograms.
-   [5] Plot μ versus ∆t from the different runs to determine whether the rate is constant.

[Fitting with Optimize in Python](https://docs.scipy.org/doc/scipy/reference/generated/scipy.optimize.curve_fit.html)

