# Ex.No:1(A) INTRODUCTION TO JAVA PROGRAMMING, DATA TYPES, VARIABLES AND OPERATORS

## QUESTION:

Lovely found a magic machine that tells her how two numbers relate to each other.
The machine supports all 6 relational operators:

Operator	Meaning

==	Is equal to

!=	Is not equal to

Greater than >

<	Less than

Greater than or equal to >=

<=	Less than or equal to

Lovely enters two numbers. The machine prints the result (true or false) for each operator.

## AIM:
To read two integers from the user and display the results of all relational comparisons between them.

## ALGORITHM :
1. Start the program and read two integers from the user.
2. Store the first value in variable **a** and the second value in **b**.
3. Compare **a** and **b** for equality, inequality, greater than and less than.
4. Compare **a** and **b** for greater-than-or-equal-to and less-than-or-equal-to.
5. Display all comparison results to the user and stop.




## PROGRAM:
 ```
/*
Program to implement variables and Operators using Java
Developed by: Rishab p doshi
RegisterNumber:  212224240134
*/

```

## Sourcecode.java:
```


import java.util.*;
public class main{
public static void main(String[] args){
Scanner sc = new Scanner(System.in);
int a = sc.nextInt();
int b= sc.nextInt();
System.out.println("a == b: "+(a==b));
System.out.println("a != b: "+(a!=b));
System.out.println("a > b: "+(a>b));
System.out.println("a < b: "+(a<b));
System.out.println("a >= b: "+(a>=b));
System.out.println("a <= b: "+(a<=b));
}}

```




## OUTPUT:

<img width="442" height="259" alt="image" src="https://github.com/user-attachments/assets/02d91517-53b5-4ac8-9e5a-f4da9f940515" />


## RESULT:
The program successfully accepted two integers from the user and displayed the outcomes of all relational comparison operations (==, !=, >, <, >=, <=).
