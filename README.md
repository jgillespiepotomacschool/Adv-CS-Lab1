Lab 1

Create a class called Lab1.  This class will have multiple methods, each do a different operation.  Then create a main method to test each method, and print out the results. 

Note: You must use a loop structure to solve these problems.  Using a math formula to determine a solution is not acceptable.

Note: You must write the comment for each method in Java Doc Format.  If all you do is copy/paste the instructions, you will receive zero credit for the comments.

This method will return the sum of all integers from 0 to x using a for loop
Note: x could be any integer, positive, or negative
public static int forSum( int x )


This method will return xy
x & y can be negative or zero, so return the values properly
Which loop structure you use is up to you: for, while, do while
public static double power( int x , int y )


Create a method that will generate the xth prime number.  You must use a loop structure to solve this.  
precondition: x is a positive whole number
precondition: keep x smaller than 20
public static int findPrime( int x )


precondition: x is a positive whole number
This method will determine if x is a self divisor
123 is not a self divisor.  Divisible by 1 and 3, but not 2
4180 will return false because you can’t divide by 0
124 is a self divisor.  Divisible by 1, 2 and 4
you may use any loop technique you want.  
Hint:   %10  & /10 are your friends
public static boolean selfDivisor( int x )



Extended Challenge
Create a program that will return the nth number in the Fibonacci sequence.  
precondition: x is a positive whole number.
public static int findFibonacci( int x )
