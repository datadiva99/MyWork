
R Programming lesson

We are going to make functions in order to investigate the Collatz problem from Mathematics.  This is a famous and unsolved problem involving a simple function.  The Collatz function C(x) takes any integer x as an input, and then follows these steps:

	If x is odd then C(x) = 3x + 1
	If x is even then C(x)=x/2

The sequence of numbers that arises from applying this function over and over is called a trajectory or an orbit.  It is an open question whether every trajectory eventually reaches 1. 

The Collatz problem is to prove the following conjecture: Starting from any positive integer n, iterations of the Collatz function C(x) will eventually reach the number 1. Thereafter iterations will cycle, taking successive values 1, 4, 2, 1, …

We will not solve this problem today – despite the best efforts of many mathematicians over the past 50 years, it remains unsolved.

If you are interested in the research that has been done in this area, look at the paper “The 3x+1 problem: An overview” by Jeffrey Lagarias, found in his book “The Ultimate Challenge: The 3x+1 Problem”.



Suggestions:

If you are new to programming, start at Task 1.  If you are more experienced, start at Task 5.  For a challenge, start with Task 9.



Task 1: Make a function which takes a number x as an argument and returns 3x + 1.

Task 2: Make a function which takes a number x as an argument and returns x/2.

Task 3: Make a function that implements the Collatz function.

Task 4: Make a function that iterates the Collatz function a user specified number of times, and returns the trajectory.

Task 5: Make a function that iterates the Collatz function and stops when the trajectory reaches 1.  It should then print out the trajectory.   Try this for several numbers and plot the trajectory using plot(iterateCollatz(x)).

Task 6: Make a function which takes a number x as an argument and returns a list that contains the orbit of x and the number of iterations of the Collatz function it takes to reach the number 1. 

Task 7: Make a function which takes a vector x as an argument and returns a data frame consisting of a column for the numbers in x and a column for how many iterations each takes to reach 1. 

Task 8: Use your function from Task 5 to create a function which takes a number x as an argument and returns the largest number in the trajectory of x (we will define the end of a trajectory as the first time that trajectory reaches 1).

Task 9: Make a function which takes a numeric vector as an argument, and returns a data frame with three columns: the original number, the largest element of that number’s trajectory, and the number of iterations it takes to reach 1.  Each row of the data frame should correspond to one number in the input vector.  So if the input is 1:3, then the output should be


number	maxinorbit	iterations
1	1	1	0
2	2	2	1
3	3	16	7
 









# MyWork
