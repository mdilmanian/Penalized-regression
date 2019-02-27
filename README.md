## Comparing penalized regression methods

This repository contains the second part of a group project submitted for Machine Learning & Data Mining (ST443), a postgraduate course at the LSE taught by Professor Xinghao Qiao.

My collaborators were Zhou Lu, Jun Jie Ng and Zijun Wu, all of them (at the time) postgraduate students at the LSE. 

The objective of this part of the project was to compare two penalized regression methods &ndash; the lasso and the elastic net &ndash; and to demonstrate that the latter tends to dominate the former in terms of prediction accuracy. To do this, we implemented coordinate descent algorithms considered in Friedman et al. (2007) to solve the two optimization problems on simulated data. 

The data simulation, algorithm implementation and testing of parameters were hand-coded in R without the use of special packages. 

---
Reference:

- Friedman, J., Hastie, T., Höfling, H., & Tibshirani, R. (2007). Pathwise coordinate optimization. _The Annals of Applied Statistics_, 1(2), 302-332.
