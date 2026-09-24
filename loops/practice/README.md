# Practice Questions

## Qn 1.

How many times 'Hello' is printed?

```java
public class Qn1 {
    public static void main(String[] args) {
        for (int i = 0; i < 5; i++) {
            System.out.println("Hello");
            i += 2;
        }
    }
}

// Answer: 2 times
```

## Qn 2.

Write a program that reads a set of integers, and then prints the sum of the even and odd integers.

## Qn 3.

Write a program to find the factorial of any number entered by the user.

(**Hint:** factorial of a number n = n * (n-1) * (n-2) * (n-3) * ...... * 1 and exists for positive numbers only. We write factorial as n! <br>
So, factorial of 0! = 1, 1! = 1, 2! = 2, 3! = 6, 4! = 24 and so on.)

## Qn 4.

Write a program to print the multiplication table of a number N, entered by the user.
    
## Qn 5.

What is wrong in the following program?

```java
public class Qn5 {
    public static void main(String[] args) {
        for (int i = 0; i <= 5; i++ ) {
            System.out.println("i = " + i);
        }
        
        System.out.println("i after the loop = " + i );
    }
}

// Answer: i is declared inside the loop, so it is out of scope and cannot be accessed outside the loop.
```
