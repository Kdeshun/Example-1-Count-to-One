Pictures – 
 ![image](https://github.com/Kdeshun/Example-1-Count-to-One/assets/122183169/371b24a9-b50d-4de8-95d2-61da0eb0c49f)
 ![image](https://github.com/Kdeshun/Example-1-Count-to-One/assets/122183169/17f1d92c-f60c-4daf-ab3f-8f62b9ae40f4) 
Step 1 – 
The attached C# code is a console program that accepts a user-supplied number and performs a mathematical operation to arrive at the value 1. The code is explained below:
1.	Importing the System Namespace:
using System;
2.	The System namespace is included in this line, which contains the Console class, which is used for input and output activities.
The Program Class:
namespace ConsoleAppExample1
{
    class Program
    {
        // ...
    }
}
The code is structured into a C# namespace called ConsoleAppExample1, and there is a Program class within that namespace.
3.	The Main Method:
static void Main(string[] args)
The Main method is the program's starting point. It is the point at which the program begins to run. Here's what goes on inside Main:
•	• It shows a notice requesting that the user provide an integer.
•	• It gets the user's input from the console and stores it as an integer in the startingNumber variable after parsing it.
•	• If the parsing succeeds (the user enters a valid integer), the CountToOne method is called to conduct the mathematical operation. If the parsing fails (for example, the user submits non-integer input), an error message is displayed.
4.The CountToOne Method:
static public int CountToOne(int n)
{
    // ...
}
CountToOne is a recursive procedure that accepts an integer n as input and returns an integer. It applies a mathematical procedure on the supplied value to reduce it to 1. What occurs inside the CountToOne function is as follows:It displays the current value of n using Console.WriteLine.
•	• It determines if n equals 1. If it is, the procedure returns 1, which is the recursion's base case.
•	• whether n is not 1, it tries to see whether n is even. If it's an even number, it divides n by 2 and recursively calls itself with the new value (n / 2).
•	• If n is odd, it adds 1 to n and recursively calls itself with the new number (n + 1).
This recursive loop will continue till n equals 1. The program continues to report the value of n as well as the operation done at each step.
Output of code:
The code's output is determined by the user's input. The code asks the user to enter an integer before performing a mathematical operation to arrive at the result 1. The software displays the current value of n as well as the action carried out at each step. Here's an example of a common output:
![image](https://github.com/Kdeshun/Example-1-Count-to-One/assets/122183169/c2650ee9-cba3-46ee-8fa4-32d8b78581c3)
In this case, the user typed in 10. The code then goes through a sequence of operations, dividing by 2 for even numbers and adding 1 for odd numbers, until it gets the value 1.
Depending on the user's input, the outcome will differ. The code is intended to operate with any positive number as input and will proceed in a similar manner to reach 1.
