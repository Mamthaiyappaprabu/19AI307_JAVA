# Ex.No:1(B) VARIABLES AND OPERATOR

## AIM:
To write a Java program to get values of variables 'a' and 'b' and then check if both the conditions 'a < 50' and 'a < b' are true. [Class name is ‘Demo’]

## ALGORITHM :
1.	Start the program.
2.	Import the necessary package 'java.util'
3.	Define a class named 'Demo'
4.	Implement the main method
5.	Create a new instance of the 'Scanner' class named 'sc' to read user input
6.	Read an integer 'a' from the user using the 'nextInt' method of 'sc'
7.	Read another integer 'b' from the user using the 'nextInt' method of 'sc'
8.	Check if 'a' is less than 50 or if 'a' is less than 'b'
a)	If the condition is true, print "true" using the 'print' method of 'System.out'
b)	If the condition is false, print "false" using the 'print' method of 'System.out'
9.	End





## PROGRAM:
 ```
/*
Program to implement a variable and operators using Java
Developed by: MAMTHA I
RegisterNumber:  212222230076
*/
```

## Sourcecode.java:

```Python
import java.util.*;
public class Demo
{
    public static void main(String[]args)
    {
        int a,b;
        Scanner in=new Scanner(System.in);
        a=in.nextInt();
        b=in.nextInt();
        if(a<50 && a<b && b>60)
        {
            System.out.println("true");
        }
        else
        {
            System.out.println("false");
        }
    }
}

```








## OUTPUT:

```Python
Input                   Expected          Got

45                       true              true
67

124                      false             false 
45      

```







## RESULT:
Thus, the Java program to get values of variables 'a' and 'b' and then check if both the conditions 'a < 50' and 'a < b' are true is created successfully.
