*Introduction*

Before diving into the concept of operators in Java, it’s essential to practice with simple problem-solving examples. In this blog, we’ll cover basic yet practical problems that will strengthen your understanding of Java’s syntax and logic-building skills.

*1.Adding Two Numbers*

public class AddTwoNumbers {
    public static void main(String[] args) {
        int num1 = 55;
        int num2 = 5;
        int sum = num1 + num2;
        System.out.println("Sum: " + sum);
    }
}

This program takes two numbers, adds them, and displays the result.

You can easily modify this code to perform subtraction, multiplication, or division.


*Explanation:*
We declared two variables num1 and num2 to store the numbers and a third variable sum to store their result after addition. The output is displayed using the System.out.println method.


*2.Checking Even or Odd*

public class EvenOrOdd {
    public static void main(String[] args) {
        int number = 67;
        if (number % 2 == 0) {
            System.out.println(number + " is even.");
        } else {
            System.out.println(number + " is odd.");
        }
    }
}

This program checks whether a number is even or odd using the modulus operator (%).

The logic: If the number is completely divisible by 2 (remainder = 0), it’s even; otherwise, it’s odd.


*Explanation:*
We declared a variable number with a value of 67. The condition number % 2 == 0 checks divisibility. Based on the result, the program outputs whether the number is even or odd.


*3. Factorial of a Number*

public class Factorial {
    public static void main(String[] args) {
        int number = 3;
        int factorial = 1;
        for (int i = 1; i <= number; i++) {
            factorial = factorial * i;
        }
        System.out.println("Factorial of " + number + " is: " + factorial);
    }
}

This program calculates the factorial of a number using a for loop.

The factorial of a number (n) is the product of all positive integers less than or equal to n.


*Explanation:*
The for loop runs from 1 to number (inclusive). In each iteration, the factorial variable is multiplied by i. For example:

1. factorial = 1 * 1 = 1
2. factorial = 1 * 2 = 2
3. factorial = 2 * 3 = 6



The result is printed after the loop ends.


*What’s Next?*

In our next blog, we’ll explore operators in Java and learn how to build our own calculator step by step. This will take your problem-solving skills to the next level!


*Conclusion:*

Practice these basic problems to strengthen your Java fundamentals. Remember, consistent practice is key to mastering programming. If you have any questions or would like to share your own solutions, feel free to comment below.

*Happy Coding!*
