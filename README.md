# Yield Curve Estimation
A weekend project on US Treasury yield curve estimation via cubic spline interpolation.

We use the method of cubic spline interpolation to model the US Treasury Yield Curve. A general method is given to construct the curve given a set of data and a desired date. We then check our model against the true yield curve to analyze the accuracy of the model. This was a project I used to get familiar with some basic interpolation methods, to understand the yield curve, and was a good exercise in collecting appropriate data.
This interpolation method follows the methods of Roi Polanitzer (https://medium.com/@polanitzer/cubic-spline-in-python-estimate-the-dollar-risk-free-yield-curve-in-isreal-as-of-december-31-2022-b365b9d19c31).
A good deal of help came from [Alex Kazachek](https://akazachek.com), who helped with the structure of the program, as well as writing the code to generate an appropriate number of points in each interval of durations (and showing me how to use seaborn). Alex also gave me the framework for plotting the true yields against the estimated yields.
