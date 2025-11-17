# Ex.No:2(E) ACCESS MODIFIERS

## QUESTION:
Create a class Calculator with: One non-static method add(int a, int b) that returns the sum, One static method info() that says "Calculator is ready".



## AIM:
To write a Java program that defines a class Calculator with one non-static method for addition and one static method for displaying information.

## ALGORITHM :
1. Create a class named Calculator.
2. Define a non-static method add(int a, int b) that returns the sum.
3. Define a static method info() that prints "Calculator is ready".
4. In main(), call the static method directly and the non-static method using an object.
5. Display the result.



## PROGRAM:
 ```
/*
Program to implement a Access Modifiers using Java
Developed by: RISHAB P DOSHI
RegisterNumber:  212224240134
*/
```

## SOURCE CODE:
```
import java.util.Scanner;

class Calculator {

    // Non-static method to add two numbers
    int add(int a, int b) {
        return a + b;
    }

    // Static method to display info
    static void info() {
        System.out.println("Calculator is ready");
    }
}

public class Main {
    public static void main(String[] args) {
        Scanner sc = new Scanner(System.in);

        int num1 = sc.nextInt();
        int num2 = sc.nextInt();

        // Call static method
        Calculator.info();

        // Create object to call non-static method
        Calculator calc = new Calculator();
        int sum = calc.add(num1, num2);

        System.out.println("Sum: " + sum);

        // Do not close scanner in online judges
    }
}
```






## OUTPUT:

<img width="1242" height="363" alt="image" src="https://github.com/user-attachments/assets/aa3d7e7d-b207-433e-aa1a-8334b0c25139" />



## RESULT:
The program successfully demonstrates the use of static and non-static methods in a class.


