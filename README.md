# Numerical-study-of-granular-kinetic-equation

This project provides codes for paper TBD. In this project, we numerically study the blow-up behavior of granular kinetic equation with different kernels and concentration strength.


# Usage of code
## Spatially homogeneous case
To begin with, we conduct numerical experiments to confirm that the proposed method can accurately capture the blow-up behavior of two special cases for which analytic solutions exist and their blow-up behavior is known.
### \gamma=3
In this case, an infinite time blow-up is expected as two Dirac delta converging to origin with rate O(1/t). First, run 
'''
MR_JKO(5, 121, 3, 4, 1, 5, 0.5, 2e3, 0.0025, 1, 0.5, 0.5, 2e-6,0.02, 0,2,1,1)
'''
Then plot figures
```
ift_bu.m
```
