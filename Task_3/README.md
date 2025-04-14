# Task 3 

In this lab we will use data collected from the Sr90 source used in the previous labs. The number of β− decay reactions, x, occurring from our Sr90 sample within a given time interval ∆t, was collected for different lengths of time T.
(note : strontium-90 (28.79 years) ->yttrium-90 (64 hours)-> zirconium-90 (stable: 2.0×1019 years))

If we look at the Poisson distribution:

P(x,r∆t)= e^(-r∆t)*(r∆t)^x / x!  = e^(-μ) μ^x / x!

We can find the rate, r, if we fit plot out μ values found from each histogram versus the time interval ∆t.

-   [1] [Download Sr90 Data]
-   [2] Plot data from all the files into histograms, label them.
-   [3] Fit Poisson function to each of the histograms.
-   [4] Use for loop to plot and fit all the data at once.
-   [5] Extract the value μ for all the histograms and make a list for ∆t and T based on the data sets given.
-   [6] Plot μ versus ∆t from the different runs to determine whether the rate is constant.

[Fitting with Optimize in Python](https://docs.scipy.org/doc/scipy/reference/generated/scipy.optimize.curve_fit.html)
