# Machine-Learning-Statistics-Tasks

## About the Assignment
Four tasks will be listed here at different times during the semester. You should complete all tasks in a single jupyter notebook. This, along with relevant files like a README, should be in a single git repository synced with a hosting provider like GitHub [1]. That URL should then be submitted using the link on the Moodle page.

### TASKS
**1. October 5th, 2020:** Write a Python function called sqrt2 that calculates and prints to the screen the square root of 2 to 100 decimal places. Your code should not depend on  any module from the standard library1 or otherwise. You should research the task first and include references and a description of your algorithm.

**2. November 2nd, 2020:** The Chi-squared test for independence is a statistical hypothesis test like a t-test. It is used to analyse whether two categorical variables are independent. The Wikipedia article gives the table below as an example [4], stating the Chi-squared value based on it is approximately 24.6. Use scipy.stats to verify this value and calculate the associated p value. You should include a short note with references justifying your analysis in a markdown cell.

![alt text](https://github.com/EoinStankard/Machine-Learning-Statistics-Tasks/blob/main/images/task2.PNG)

**3. November 16th, 2020:** The standard deviation of an array of numbers x is calculated using numpy as np.sqrt(np.sum((x - np.mean(x))**2)/len(x)) .However, Microsoft Excel has two different versions of the standard deviation calculation, STDEV.P and STDEV.S . The STDEV.P function performs the above calculation but in the STDEV.S calculation the division is by len(x)-1 rather than len(x) . Research these Excel functions, writing a note in a Markdown cell about the difference between them. Then use numpy to perform a simulation demonstrating that the STDEV.S calculation is a better estimate for the standard deviation of a population when performed on a sample. Note that part of this task is to figure out the terminology in the previous sentence.

## How to view the Assignment

The assignment can be viewed the following ways

1. Downloading the Repo and running jupyter notebook in the command line. (Recommended)
2. Clicking on the "MLS-Tasks2020.ipynb" file above,

I recommend that you download and run the assignment on your own machine as erros may occur when directly clicking on the "MLS-Tasks2020.ipynb" file above

## What is needed to run the Assignment

1. Anaconda Python as it contains all libraries
2. The Repo will need to be cloned or downloaded
