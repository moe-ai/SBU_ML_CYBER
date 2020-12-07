## Sanger Anomaly Detection Workshop Code

This repository contains code used for the unsupervised learning in a workshop at Sanger.

The idea is based on Chapter 4, *More Complex, Adaptive Models* from
[Practical Machine Learning](https://www.safaribooksonline.com/library/view/practical-machine-learning/9781491914151/ch04.html)
by Ted Dunning and Ellen Friedman.

**Action**: read the following article:[Clustering of Time Series Subsequences is Meaningless](http://www.cs.ucr.edu/~eamonn/meaningless.pdf).
Is there any issue with the approach described here? 
This material still serves as an introduction to unsupervised learning and
clustering, but **beware in using it for anomaly detection in practice**.

### Contents

* `Clustring example 1.ipynb` is an IPython notebook demonstrating a simple example of unsupervised learning: time-series anomaly detection. you can open this file in google colab and upload data nd required .py files
https://github.com/moe-ai/SBU_ML_CYBER/tree/main/week6/Practical%201-%20sanger
* `a02.dat` is a set of EKG data from PhysioNet used to demonstrate the
  algorithms.
* `ekg_data.py` is a module for reading the EKG data.
* `learn_utils.py` is a collection of helper functions developed in the
  notebook, saved as a module for reuse.
* `learn.py` is a complete listing for the code developed in the notebook.


### Requirements

 Moe: I have modified the notebook so you can easily upload and run in google colab

Python is required, along with the following modules:
* NumPy
* matplotlib
* scikit-learn

IPython Notebook dependencies are also required, if running the notebook.

If you're on Ubuntu:
```
$ sudo apt-get install ipython-notebook python-numpy python-matplotlib python-sklearn
```
Or on any system with pip:
```
$ pip install ipython[notebook] numpy matplotlib scikit-learn
```
