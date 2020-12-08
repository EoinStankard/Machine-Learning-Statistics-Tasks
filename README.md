# Machine-Learning-Statistics-Tasks

## About the Assignment
Four tasks will be listed here at different times during the semester. You should complete all tasks in a single jupyter notebook. This, along with relevant files like a README, should be in a single git repository synced with a hosting provider like GitHub [1]. That URL should then be submitted using the link on the Moodle page.

### TASKS
**1. October 5th, 2020:** Write a Python function called sqrt2 that calculates and prints to the screen the square root of 2 to 100 decimal places. Your code should not depend on  any module from the standard library1 or otherwise. You should research the task first and include references and a description of your algorithm.

**2. November 2nd, 2020:** The Chi-squared test for independence is a statistical hypothesis test like a t-test. It is used to analyse whether two categorical variables are independent. The Wikipedia article gives the table below as an example [4], stating the Chi-squared value based on it is approximately 24.6. Use scipy.stats to verify this value and calculate the associated p value. You should include a short note with references justifying your analysis in a markdown cell.

![alt text](https://github.com/EoinStankard/Machine-Learning-Statistics-Tasks/blob/main/images/task2.PNG)

**3. November 16th, 2020:** The standard deviation of an array of numbers x is calculated using numpy as np.sqrt(np.sum((x - np.mean(x))**2)/len(x)) .However, Microsoft Excel has two different versions of the standard deviation calculation, STDEV.P and STDEV.S . The STDEV.P function performs the above calculation but in the STDEV.S calculation the division is by len(x)-1 rather than len(x) . Research these Excel functions, writing a note in a Markdown cell about the difference between them. Then use numpy to perform a simulation demonstrating that the STDEV.S calculation is a better estimate for the standard deviation of a population when performed on a sample. Note that part of this task is to figure out the terminology in the previous sentence.

**4. November 30th, 2020:** Use scikit-learn to apply k-means clustering to Fisher’s famous Iris data set. You will easily obtain a copy of the data set online. Explain in a Markdown cell how your code works and how accurate it might be, and then explain how your model could be used to make predictions of species of iris.


## How to view the Assignment

The assignment can be viewed the following ways

1. Downloading the Repo and running jupyter notebook in the command line. (Recommended)
2. Clicking on the "MLS-Tasks2020.ipynb" file above,

I recommend that you download and run the assignment on your own machine as erros may occur when directly clicking on the "MLS-Tasks2020.ipynb" file above

## What is needed to run the Assignment

1. Anaconda Python as it contains all libraries
2. The Repo will need to be cloned or downloaded

## Quick Overview of MLS-Tasks2020.ipynb File

### Task 1
For task one you will see the code used to develop the square root formula, Function take in a valuse and then divides it by itself until it reaches a certain accuracy, It then returns that value with 100 decimal places.
Tests were on numbers 2,4,16 and then i used the square root formula that comes with the python library math to see how accurate my results are

### Task 2
In task two we are asked to prove that the Chi-squared value of a table was 24.6 and to get its p value

### Task 3
In task three we are asked to demonstrate how STDEV.S is better than STDEV.P on a sample, Standard deviation population(STDEV.P) is the sample in its entirety so to use this formula you would need to have the full table of data
Standard Deviation Sample(STDEV.S) is where you only need a portion of the data to generate an output.

### Task 4
Task four is using k-means clustering on the iris dataset, In this you will first see plots of the datasets that are grouped by species of flower, Then we compare that data against the clusters that are generated by k-means

## References

1. https://tour.golang.org/flowcontrol/8
2. https://docs.python.org/3/tutorial/floatingpoint.html
3. https://realpython.com/python-square-root-function/
4. https://en.wikipedia.org/wiki/Chi-squared_test
5. https://towardsdatascience.com/gentle-introduction-to-chi-square-test-for-independence-7182a7414a95
6. https://exceljet.net/excel-functions/excel-stdev.p-function#:~:text=of%20the%20numbers.-,The%20STDEV.,S%20function.
7. https://exceljet.net/excel-functions/excel-stdev.s-function#:~:text=The%20STDEV.,The%20STDEV.
8. https://stackoverflow.com/questions/10897339/python-fetch-first-10-results-from-a-list
9. https://www.youtube.com/watch?v=W7q8kfs1bNI
10. https://www.khanacademy.org/math/statistics-probability/summarizing-quantitative-data/variance-standard-deviation-sample/a/population-and-sample-standard-deviation-review
11. https://support.microsoft.com/en-us/office/stdev-p-function-6e917c05-31a0-496f-ade7-4f4e7462f285
12. https://numpy.org/doc/stable/reference/random/generated/numpy.random.standard_normal.html
13. https://gist.github.com/curran/a08a1080b88344b0c8a7
14. https://towardsdatascience.com/making-plots-in-jupyter-notebook-beautiful-more-meaningful-23c8a35c0d5d
15. https://stackoverflow.com/questions/22071987/generate-random-array-of-floats-between-a-range
