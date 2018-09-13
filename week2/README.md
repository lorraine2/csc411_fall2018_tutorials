# Week 2
The week 2 tutorial for the Fall 2018 CSC411/CSC2515 (Introduction to Machine Learning) at the University of Toronto.

## Getting Started

This week consists of a lecture using both a set of slides with an instructor run jupyter notebook, followed by an exercise for the students.
 
(1) First, present the slides `linear_algebra_goodfellow.pdf`.  The original slides are located [here](https://www.deeplearningbook.org/slides/02_linear_algebra.pdf).
Do not cover material about eigenvalues - this is for a later tutorial.
If extra time, can show class how to get numpy/jupyter notebook setup in a python environment (ex. with conda or pip).
This presentation should take about 20 minutes.

(2) Second, present the jupyter notebook `CSC411_Fall_2018_Tutorial1_lecture.ipynb`.
<b>Please verify that you have numpy in your python environment and can run the `.ipynb`!
The students do not have to (but are welcome to) run the ipython notebook on the website.</b>
Jupyter notebooks can be launched with `jupyter notebook` within a python environment.

This should amount to running each line of code and explaining what it does (if not obvious to the class).
Explain why vectorized computations run faster - ex. better use of hardware because of Single Instruction Multiple Data (SIMD).
It is often better to say what (ex. with numpy) you want done instead of how (ex. with loops), because of existing efficient implementations.
Note how one of the inverse functions raises an exception because the matrix is singular.
Mention how matrix is not commutative with dot product.
There are three linear systems at the end.
The first system has a unique solution, while the second system has no solutions (and raises an exception), and the final system has many solutions (and raises an exception).
Mention potential solutions to this - perhaps smallest norm solution if many, or closest solution if none.
If extra time, can ask class about any operations they are interested in, and show to reference numpy documentation (ex. with a web browser).

This presentation should take about 20 minutes.

(3) Finally, present the exercise `CSC411_Fall_2018_Tutorial1_worksheet.ipynb`.
To do this, present each problem to the class.
Ask the class to to implement the problem twice (on paper) - without using numpy and with numpy.
Run both the non-vectorized and vectorized examples from `CSC411_Fall_2018_Tutorial1_worksheet.ipynb` to illustrate the speed differences.
Repeat for each problem.

The exercise should take about 10 minutes.

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

