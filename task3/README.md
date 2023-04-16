# Task 3 Part 1

# Task 3 Part 1

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


# Task 3 Part 2


Here we will be looking at experimental data from the CLAS detector at JLAB. The experimental we will be looking at is an electron scattering experiment with a beam energy of 4.8 GeV, along the Z axis, on a liquid hydrogen (proton) target.
![reaction](reaction.png)

The csv file has the information from the scattered electron stored in 4 banks. The momentum is stored in "p" and the cosine of the angle from the beam line is gives in the x, y, and z are given by the "cx", "cy", and "cz" banks respectively. Therefore to get the momentum of the electron in the x direction, Px = P * Cx.

In this section, we will look at calculating W and Q^2 values from the scattered electrons.

######## TO DO:
Download data from:[here](http://boson.physics.sc.edu/~nick/electron-scattering-data.html)
 - [1] Practice how you can create 4-vector and use methods in class LorentzVector
 - [2] Create a 4 vector for the Electron beam, e_mu.
 - [3] Create a 4 vector for the Proton target, p_mu.
 - [4] Create a 4 vector for the scattered Electron beam, e_mu_prime.
 - [5] Calculate q_mu and plot W and Q^2 and W vs Q^2  histograms.
