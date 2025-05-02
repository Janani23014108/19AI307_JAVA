# Ex.No:1(B) VARIABLES AND OPERATOR

## AIM:
To Write a Java programs to get marks and find the average and display the grade.

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
Developed by: J.JANANI
RegisterNumber:  212223230085
*/

import java.util.Scanner;
public class Main{
    public static void main(String[] args)
    {
        int m1,m2,m3,m4,m5;
        float total=0,avg;
        Scanner s=new Scanner(System.in);
        m1=s.nextInt();
        m2=s.nextInt();
        m3=s.nextInt();
        m4=s.nextInt();
        m5=s.nextInt();
        
        total=m1+m2+m3+m4+m5;
        avg=total/5;
        System.out.print("The student Grade is: ");
        if(avg >=80)
        {
            System.out.print("A");
        }
        else if(avg<80 && avg>=60)
        {
          System.out.print("B");
        }
        else if(avg <60 && avg>=40)
        {
            System.out.print("C");
        }
        else
        {
            System.out.print("D");
        }
    }
}


```



## OUTPUT:

"C:\Users\admin\Pictures\Screenshots\Screenshot 2025-05-02 155000.png"

## RESULT:
Thus, the Java program  to get marks and find the average and display the grade is created successfully.
