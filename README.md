# EXperiment-3

## Aim
To demonstrate the usage of arithmetic, assignment, and comparison operators in C++.

## Theory
Operators in programming languages are symbols that specify which operations to perform on operands. In C++, operators are used extensively to perform various operations on variables and values.

 ## Arithmetic Operators
Arithmetic operators are used to perform mathematical operations.
+ (Addition): Adds two operands.
- (Subtraction): Subtracts the second operand from the first.
* (Multiplication): Multiplies two operands.
/ (Division): Divides the numerator by the denominator.
% (Modulus): Returns the remainder of a division operation.

##Code
~~~
*AARYA JIRWANKAR
23070123161
ENTC B3 
EXPERIMENT 3- TYPES OF OPERATORS(ARITHEMATIC, LOGICAL, COMPARSION)
*/


#include<iostream>
using namespace std;

int main()
{
    int a,b;
    printf("Enter 2 variables: ");
    scanf("%d %d",&a, &b);
    int c = a+b;
    cout << "The addition of 2 numbers "<<c<<endl;
    int d = a-b;
    cout << "The subtraction of 2 numbers "<<d<<endl;
    int e = a*b;
    cout << "The multiplication of 2 numbers "<<e<<endl;
    float f = a/b;
    cout << "The division of 2 numbers "<<f<<endl;
    if(a==b)
    {
        cout << "The numbers are equal" << endl;
    }
    else if(a>b)
    {
        cout <<"The first number is greater than the second one "<< endl;
    }
    else
    {
        cout <<"The second number is greater than the first one" << endl;
    }
    float g = a%b;
    cout<< "The reminder of the numbers is: " <<g<<endl;
    long int k = a*a;
    cout<<"The square of the first number is: "<<k<<endl;
    for(int i = 0;i<2;i++)
    {
        if(a<b && a!=b)
        {
            b =- 10;
            a =+ 1;
        }
        else if(a>b || a==b)
        {
            a =-10;
            b += 1;
        }
        cout<<a<<endl;
        cout<<b<<endl;
    }

}

/* OUTPUT
Enter 2 variables: 15
19
The addition of 2 numbers 34
The subtraction of 2 numbers -4
The multiplication of 2 numbers 285
The division of 2 numbers 0
The second number is greater than the first one
The reminder of the numbers is: 15
The square of the first number is: 225
1
-10
-10
-9
*/
~~~

## Conclusion
The code successfully demonstrates the use of arithmetic, assignment, and comparison operators in C++. Each section of the code outputs the results of the operations performed, validating the correct implementation and understanding of these operators. Arithmetic operators perform basic mathematical calculations, assignment operators modify the value of a variable based on the operation, and comparison operators help in making decisions by comparing values. This provides a clear understanding of how these operators function in C++.
