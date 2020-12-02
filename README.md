## Tasks 2020: Emerging Technologies

### Task 1: Calculate a square root
Write a Python function called sqrt2 that calculates and prints to the screen the square root of 2 to 100 decimal places. Your code should not depend on any module from the standard library or otherwise. You should research the task first and include references and a description of your algorithm.


### Task2: Chi-squared test
The Chi-squared test for independence is a statistical hypothesis test like a t-test. It is used to analyse whether two categorical variables are independent. The Wikipedia article gives the table and states the Chi-squared value based on it is approximately 24.6. Use scipy.stats to verify this value and calculate the associated p value. You should include a short note with references justifying your analysis in a markdown cell.


### Task 3: Research STDEV.P and STDEV.S
The standard deviation of an array of numbers x is calculated using numpy as np.sqrt(np.sum((x - np.mean(x)) ** 2)/len(x)).

However, Microsoft Excel has two different versions of the standard deviation calculation, STDEV.P and STDEV.S . The STDEV.P function performs the above calculation but in the STDEV.S calculation the division is by len(x)-1 rather than len(x).

Research these Excel functions, writing a note in a Markdown cell about the difference between them.

Then use numpy to perform a simulation demonstrating that the STDEV.S calculation is a better estimate for the standard deviation of a population when performed on a sample. Note that part of this task is to figure out the terminology in the previous sentence.


### Task 4: Machine Learning
Use scikit-learn to apply k-means clustering to Fisher’s famous Iris data set. 

Explain in a Markdown cell how your code works and how accurate it might be, and then explain how your model could be used to make predictions of species of iris.
