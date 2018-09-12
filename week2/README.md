# Week 2
The week 2 tutorial for the Fall 2018 CSC411/CSC2515 (Introduction to Machine Learning) at the University of Toronto.

## Getting Started

This week consists of a lecture using both a set of slides with an instructor run jupyter notebook, followed by an exercise for the students.
 
First, present the slides `linear_algebra_goodfellow.pdf`.  The slides are located [here](https://www.deeplearningbook.org/slides/02_linear_algebra.pdf) and should take about 25 minutes.

Second, present the jupyter notebook `CSC411_Fall_2018_Tutorial1_lecture.ipynb`.
Jupyter notebooks can be launched with `jupyter notebook` within a python environment.
<b>Please verify that you have numpy in your python environment and can run the `.ipynb`!</b>
This should amount to running each line of code and explaining what it does (if not obvious to the class).
Note how one of the inverse functions rasies an exception because the matrix is singular.
Additionally, now how there are 3 solutions to linear systems.
The first system has a unique solution, while the second system has many solutions (and raises an exception), and the final system has no solutions (and raises an exception).
This presentation should take about 20 minutes.

Finally, present the exercise `CSC411_Fall_2018_Tutorial1_worksheet.ipynb`.
To do this, present each problem to the class.
Ask the class to to implement the problem twice (on paper) - without using numpy and with numpy.
Run both the non-vectorized and vectorized examples from `CSC411_Fall_2018_Tutorial1_worksheet.ipynb` to illustrate the speed differences.
Repeat for each problem.
The exercise should take about 15 minutes.

## Citations

Presentation Slides:

@book{Goodfellow-et-al-2016,
    title={Deep Learning},
    author={Ian Goodfellow and Yoshua Bengio and Aaron Courville},
    publisher={MIT Press},
    note={\url{http://www.deeplearningbook.org}},
    year={2016}
}

https://www.deeplearningbook.org/lecture_slides.html

https://www.deeplearningbook.org/slides/02_linear_algebra.pdf

