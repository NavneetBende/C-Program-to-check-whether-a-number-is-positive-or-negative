# C-Program-to-check-whether-a-number-is-positive-or-negative

Check if a Number is Positive or Negative in C++
Given an integer input, The objective is to write a code to Check if a Number is Positive or Negative in C++ Language.

For Instance,
Input : num = 10
Output :The number is Positive
Check if a Number is Positive or Negative in C++
Check if a Number is Positive or Negative in C++
The objective of the C++ code is to check whether a given integer input is Positive or Negative. To do so we have the following Methods,

Method 1: Using Brute Force
Method 2: Using Nested if-else Statements
Method 3: Using Ternary Operators
The Above methods are discussed in depth in the sections below.

Check if a Number is Positive or Negative in C++
While loop in C
Related Pages
Even or Odd number 

Sum of First N Natural numbers

Sum of N natural numbers

Sum of numbers in a given range

Prime number within a given range

Method 1: Using Brute Force
This method uses Brute Force to check whether a given integer is Positive or Negative.

C++ Code
Run

#include <iostream>
using namespace std;

int main()
{
    int num = 96;
    
    //Conditions to check if the number is negative or positive
    if (num > 0)
         cout << "The number is positive";
    else if (num < 0)
        cout << "The number is negative";
    else
        cout << "Zero";
    
    return 0;
}
Output
Enter a number: 96
The number is Positive
Algorithm
This method uses Brute Force to check whether a given integer is Positive or Negative. The Algorithm for the above code is as follows

Step 1. Start
Step 2. Insert the number.
Step 3. If the number is greater than Zero then print “The number is Positive”
Step4: If the number is smaller than zero, then print, “The number is Negative”
Step 5. Else print, “The number is Zero”
Step 6. Stop
Method 2: Using Nested if-else Statements
This method uses a nested if-else Statements to check whether a given number is Positive or Negative.

C++ Code
Run

#include<iostream>
using namespace std;

int main()
{
    int num = -12;
    
    //Condition to check if the number is negative or positive
    if (num >= 0)
    {
        if (num == 0)
            cout << "Zero";
        else
            cout << "The number is positive";
    }
    else
            cout << "The number is negative";
    
    return 0;
}
Output
Enter a number: -12
The number is Negative
Algorithm
This method uses a nested if-else Statements to check whether a given number is Positive or Negative.

Step 1 – Start
Step 2 – Insert the number.
Step 3 – If the number is greater or equal move to the inner nested loop
Step 3.1 – If the number is zero, print Zero
Step 3.2 – Else print The Number is Positive
Step4 – Else the number has to be negative, Print The number is Negative
Step 6 – Stop
Method 3: Using Ternary Operator
This method uses a ternary operator to check whether a number is Positive or Negative.

Ternary Operator Syntax
( Condition ) ? ( if True : Action) : ( if False : Action) ;
C++ Code
Run

#include <iostream>
using namespace std;

int main()
{
    int num = -15;
    
    //Condition to check if the 0, positive or negative
    
    if(num == 0)
            cout << "Zero"; else (num > 0) ? cout << "Positive": cout << "Negative";
    
    return 0;
}
Output
Enter a number: -15
Negative
Algorithm
This method uses a ternary operator to check whether a number is Positive or Negative. The Algorithm for the above code is as follows,
 
Step 1 – Start
Step 2 – Insert the number.
Step 3 – If number is equal to zero, Print Number is Zero
Step 4 – Else do following –            (num > 0) ? cout << “Positive”: cout << “Negative”;
Step 6 – Stop
