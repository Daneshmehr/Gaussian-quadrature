# Gaussian quadrature
We choose a function on a closed interval (the function cannot be a low-order polynomial, but need not be too complicated). The function that you can calculate the integral for analytically.

Then, we implement *two different* numerical integration methods, one with fixed interval sizes, one with Gaussian quadrature, to integrate this function. These don't need to be of very high order. the code that we can change the number of sub-intervals (and number of evaluation points).

Finally, we compare the difference between the two numerical integrals, and their difference with the correct/analytic answer, as a function of the number sub-intervals. Is the difference between the two estimates a good indicator of the actual error?!
