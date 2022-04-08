# Unrolled Approximate Message Passing Algorithm for Nonconvex Regularization

# Description of Files

## [save_problem.py](save_problem.py) 

Creates numpy archives (.npz) and matlab (.mat) files with (y,x,A) for the sparse linear problem y=Ax+w.
These files are not really necessary for any of the deep-learning scripts, which generate the problem on demand.
They are merely provided for better understanding the specific realizations used in the experiments.

## [LISTA.py](LISTA.py)

This is an example implementation of LISTA _Learned Iterative Soft Thresholding Algorithm_ by (Gregor&LeCun, 2010 ICML).

## [LAMP.py](LAMP.py)

Example of Learned AMP (LAMP) with a variety of shrinkage functions.

## [LVAMP.py](LVAMP.py)

Example of Learned Vector AMP (LVAMP).



Thanks to the original code of https://github.com/mborgerding/onsager_deep_learning

