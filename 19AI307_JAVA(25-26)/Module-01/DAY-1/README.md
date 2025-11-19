# Ex.No:1(A) INTRODUCTION TO JAVA PROGRAMMING, DATA TYPES, VARIABLES AND OPERATORS

## QUESTION:
Lovely is learning java basics, can you teach her the different types of datatypes in java? Write a program that uses all datatypes and print them all.

Input Format:

byte - 24

short - 11000

int - 1,34,500

long - 24,23,10,34

float - 24.20

double - 1,30,000.80

boolean - true/false

char - 'u'

String -"Heyyy, Lovely, Let's learn java!"

## AIM:
To write a Java program that demonstrates all basic datatypes and prints their values.

## ALGORITHM :
1.	Start the program and declare variables of all datatypes (byte, short, int, long, float, double, boolean, char, String).
2. Assign the given input values to each variable.
3. Print each variable with a proper label.
4. Ensure numeric values with commas (like 1,34,500) are written without commas in Java.
5. End the program after all values are displayed.


## PROGRAM:
 ```
/*
Program to implement variables and Operators using Java
Developed by: Deeksha P
RegisterNumber:  212222040031
*/
```

## Sourcecode.java:
```
import java.util.Scanner;

public class DataTypesDemo {
    public static void main(String[] args) {
        Scanner sc = new Scanner(System.in);

        
        byte byteVal = sc.nextByte();
        short shortVal = sc.nextShort();
        int intVal = sc.nextInt();
        long longVal = sc.nextLong();
        float floatVal = sc.nextFloat();
        double doubleVal = sc.nextDouble();
        boolean boolVal = sc.nextBoolean();
        char charVal = sc.next().charAt(0);
        sc.nextLine();
        String strVal = sc.nextLine();
       
        System.out.println("Hey Lovely, let's print all types of data received from user using different data types");
        System.out.println("This is byte datatype " + byteVal);
        System.out.println("This is short datatype " + shortVal);
        System.out.println("This is int datatype " + intVal);
        System.out.println("This is long datatype " + longVal);
        System.out.println("This is float datatype " + floatVal);
        System.out.println("This is double datatype " + doubleVal);
        System.out.println("This is boolean datatype " + boolVal);
        System.out.println("This is char datatype " + charVal);
        System.out.println("This is string datatype " + strVal);

       
    }
}
```






## OUTPUT:
<img width="1198" height="660" alt="image" src="https://github.com/user-attachments/assets/6a9e2fef-c892-4545-9f5c-b273d0d23e76" />



## RESULT:
Thus,the program executed successfully and printed all the datatypes with their values.

