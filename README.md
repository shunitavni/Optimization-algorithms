# Optimization-algorithms
Implementation and exploration of different optimization algorithms.


# ADAM analysis
One of the complaints about ADAM is that still, the adjusted learning rates (see third math line in https://docs.google.com/presentation/d/1UFmncokDwUC4xLChHOfhe26MJucMyrjPjP9iLcKo30A/edit#slide=id.g5871948b3d_0_86) can be extream (very high or very low). Let's try to confirm this:

Modify your step_adam code to calculate the smallest and largest adjusted rates in the network in every step, and plot that as a curve (X axis is step number, and Y axis is the adjusted LR value). Plot two curves: one for min and one for max. What's your conclusions?
