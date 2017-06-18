Programming Exercise 1: Linear Regression

Machine Learning
Introduction
In this exercise, you will implement linear regression and get to see it work
on data. Before starting on this programming exercise, we strongly recom-
mend watching the video lectures and completing the review questions for
the associated topics.
To get started with the exercise, you will need to download the starter
code and unzip its contents to the directory where you wish to complete the
exercise. If needed, use the cd command in Octave to change to this directory
before starting this exercise.
You can also nd instructions for installing Octave on the \Octave In-
stallation" page on the course website.
Files included in this exercise
ex1.m - Octave script that will help step you through the exercise
ex1 multi.m - Octave script for the later parts of the exercise
ex1data1.txt - Dataset for linear regression with one variable
ex1data2.txt - Dataset for linear regression with multiple variables
submit.m - Submission script that sends your solutions to our servers
[?] warmUpExercise.m - Simple example function in Octave
[?] plotData.m - Function to display the dataset
[?] computeCost.m - Function to compute the cost of linear regression
[?] gradientDescent.m - Function to run gradient descent
[y] computeCostMulti.m - Cost function for multiple variables
[y] gradientDescentMulti.m - Gradient descent for multiple variables
[y] featureNormalize.m - Function to normalize features
[y] normalEqn.m - Function to compute the normal equations
? indicates les you will need to complete
y indicates extra credit exercises

Throughout the exercise, you will be using the scripts ex1.m and ex1 multi.m.
These scripts set up the dataset for the problems and make calls to functions
that you will write. You do not need to modify either of them. You are only
required to modify functions in other les, by following the instructions in
this assignment.
For this programming exercise, you are only required to complete the rst
part of the exercise to implement linear regression with one variable. The
second part of the exercise, which you may complete for extra credit, covers
linear regression with multiple variables.
