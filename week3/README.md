# Week 3
The week 3 tutorial for the Fall 2018 CSC411/CSC2515 (Introduction to Machine Learning) at the University of Toronto.

## Getting Started

This week consists of a lecture using both a set of slides with an instructor run jupyter notebook, followed by an exercise for the students.
 
(1) First, present the slides `csc411-opt-tut-f18.pdf`.  
This presentation should take no more than 20 minutes.
You may skip slides 12 (GD with line search) and 16 (Checkgrad) if time is a concern.
If extra time, can show class how to get numpy/jupyter notebook setup in a python environment (ex. with conda or pip).

(2) Second, present the jupyter notebook `CSC411_Fall_2018_Tutorial1_lecture.ipynb`.
<b>Please verify that you have numpy in your python environment and can run the `.ipynb`!
You also need to pip install autograd and matplotlib
The students do not have to (but are welcome to) run the ipython notebook on the website.</b>
Jupyter notebooks can be launched with `jupyter notebook` within a python environment.

This should amount to running each line of code and explaining what it does (if not obvious to the class).
If extra time, can ask class about if there are 

This presentation should take about 15 minutes.

(3) Finally, the students will complete the exercise `CSC411_Fall_2018_Tutorial1_worksheet.ipynb`.
We hope the students will have setup a working python environment with jupyter before coming to class.
Ask the students to pair up. 
To mitigate time wasted setting up packages, ask students to assert that at least one person in each pair has a working environment.
Students can call you over for help while they work.
When they are done implementing the update rules they can try different functions, implement unit tests for the updates using scipy [check_grad](https://docs.scipy.org/doc/scipy/reference/generated/scipy.optimize.check_grad.html), or implement Adam.
If they finish those things, have them look over the autograd tutorials on github.

The exercise should take about 15 minutes.

