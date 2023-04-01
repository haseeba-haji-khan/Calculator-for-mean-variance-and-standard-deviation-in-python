# calculator-for-mean-variance-and-standard-deviation-in-python
I entered for prompt user:
Enter a Number: 1
Enter a Number: 2
Enter a Number: 3
Enter a Number: Exit
output:
Total observation: 3
average: 2.0
variance: 0.6666666666666666
standard deviation: 0.816496580927726
# Explanation for Codes:
First, we have created an empty list using a while loop, it stops reading from input as soon as a certain condition becomes true(the loop breaks when We enter Exit). we use float() to convert the user input float type. Then we add enter numbers to the empty list using the append() method.
We first calculate the number of observations (n) in our data using the built-in function len(). Then, we calculate the mean of the data, dividing the total sum of the observations by the number of observations.
The next step is to calculate the square deviations from the mean. To do that, we use a list comprehension that creates a list of square deviations using the expression (x - mean) ** 2 where x stands for every observation in our data.
variance ** 0.5 used for calculating standard deviation.
