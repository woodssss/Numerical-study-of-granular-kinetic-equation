# Numerical-study-of-granular-kinetic-equation

This project provides codes for paper TBD. In this project, we numerically study the blow-up behavior of granular kinetic equation with different kernels and concentration strength.


# Usage of code
## Spatially homogeneous case
To begin with, we conduct numerical experiments to confirm that the proposed method can accurately capture the blow-up behavior of two special cases for which analytic solutions exist and their blow-up behavior is known.
### \gamma=3
In this case, an infinite time blow-up is expected as two Dirac delta converging to origin with rate O(1/t). First, run 
```
MR_JKO(5, 121, 3, 4, 1, 5, 0.5, 2e3, 0.0025, 1, 0.5, 0.5, 2e-6,0.02, 0,2,1,1)
```
Then plot figures
```
ift_bu.m
```

### \gamma=1
In this case, a finite time blow-up is expected with analytic blow-up time. First, run 
```
MR_JKO(4, 121, 1, 10, 1, 5, 0.5, 1e3, 0.0025, 1, 0.05, 0.5, 2e-6,0.02, 0,2,1,1)
```
Then plot figures solution at t=0.5
```
hom_fig(5, 101, 1, 1, 1, 5, 0.2, 1e3, 0.02, 0.5, 0.8, 0.2, 1e-8,0.01, 1,2,1,1)
```
Check 

