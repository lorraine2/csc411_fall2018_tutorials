# CSC411 F18 Bayesian Optimization Tutorial

What follows is a description of the Bayesian Optimization tutorial for CSC411/2515 Fall 2018.

## Getting Started

The tutorial consists of a set of slides, followed ipython notebooks which implement a basic Bayesian optimization algorithm.
To get the code examples you may run the following commands:

```
git clone https://github.com/fmfn/BayesianOptimization.git
cd BayesianOptimization
python setup.py install
```

Alternatively, if you only want to install the Bayesian optimization library:
```
pip install bayesian-optimization
```

### Prerequisites

You will need:

```
numpy
scipy
scikit-learn
matplotlib
jupyter notebook
```

## Lesson Plan

The first goal is to present the power point.
This should take about 35 minutes.

The second goal is to present the ipython notebooks which are located in `BayesianOptimization/examples`.
This can be done with:

```
cd BayesianOptimization/examples
jupyter notebook
```

First, present `visualization.ipynb`, then with any remaining time present `exploration_vs_exploitation.ipynb`.
This should take the final 15 minutes.


## Acknowledgments

* Ryan P. Adams for the powerpoint.
* Fernando Nogueira for Bayesian Optimization library
* CSC411 Teaching staff
