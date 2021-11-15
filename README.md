# MANE 3351 - Manufacturing Engineering Analysis

## Laboratory 5 Assignment

#### Assigned: November 15, 2021

#### Due: November 23, 2021

---

#### Learning Goals

1.  Utilize Numpy functions to create an array of integers
2.  Utilize Scipy function to calculate upper percentage points for the Chi-Squared distribution

#### Description

Create and print an array containing the upper 0.075 percentage points of the Chi-squared distribution.

#### Step 1

Create an array of ten integers with values 1, 2, …, 10 to store the degrees of freedom using the Numpy arange command. The documentation for Numpy arange is available at [https://numpy.org/doc/stable/reference/generated/numpy.arange.html](https://numpy.org/doc/stable/reference/generated/numpy.arange.html).

#### Step 2

Utilize ppf function from scipy.stats.chi2 to create an array containing the (upper) 0.075 percentage point for the Chi-Squared distribution. Documentation for scipy.stats.chi2 is available at [https://docs.scipy.org/doc/scipy/reference/generated/scipy.stats.chi2.html](https://docs.scipy.org/doc/scipy/reference/generated/scipy.stats.chi2.html). Note that the function returns the q-th quantile which is not the upper percentage point.

#### Step 3

Print the array created in Step 2 containing the upper 0.075 percentage point of the Chi-squared distribution with degrees of freedom ranging from 1 to 10.

#### Step 4

Upload your repository using the git commands.