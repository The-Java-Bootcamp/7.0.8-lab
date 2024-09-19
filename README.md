# Lab: 7.0.8

**Objective:**

- Understand the concept and importance of Method Overloading in Java development.
- Learn how to implement Method Overloading using Java's object-oriented programming features.
- Explore practical applications of Method Overloading in real-world Java projects.
- Identify common pitfalls and best practices when working with Method Overloading.
- Gain hands-on experience with a complete Java example that demonstrates Method Overloading.

**Prerequisites:**

- Basic understanding of Java programming.
- Familiarity with object-oriented programming concepts.
- Understanding of method declaration and invocation in Java.

**What You'll Achieve:**

- Develop a solid understanding of Method Overloading in Java.
- Implement practical examples of Method Overloading that can be applied in real-world scenarios.
- Enhance your skills in creating flexible and readable code using Method Overloading.

**Assignment Details**

You are provided with the following `CalculatorDemo` class:

1. Inside the `CalculatorDemo` class, implement the following overloaded methods:
    - `add(int a, int b)`: Returns the sum of two integers.
    - `add(double a, double b)`: Returns the sum of two doubles.
    - `add(int a, int b, int c)`: Returns the sum of three integers.
    - `add(String a, String b)`: Concatenates two strings and returns the result.
2. Implement a multiply method with the following overloads:
    - `multiply(int a, int b)`: Returns the product of two integers.
    - `multiply(double a, double b)`: Returns the product of two doubles.
    - `multiply(int a, int b, int c)`: Returns the product of three integers.
3. Create a `printInfo` method with these overloads:
    - `printInfo(String name)`: Prints "Name: [name]".
    - `printInfo(String name, int age)`: Prints "Name: [name], Age: [age]".
    - `printInfo(String name, int age, String city)`: Prints "Name: [name], Age: [age], City: [city]".
4. In the `main` method:
    - Call each of the overloaded `add` methods with appropriate arguments and print the results.
    - Call each of the overloaded `multiply` methods with appropriate arguments and print the results.
    - all each of the overloaded `printInfo` methods with appropriate arguments.

**Example Output**

```
Addition Results:
5 + 3 = 8
3.5 + 2.7 = 6.2
1 + 2 + 3 = 6
Hello + World = HelloWorld

Multiplication Results:
4 * 3 = 12
2.5 * 3.0 = 7.5
2 * 3 * 4 = 24

Print Info Results:
Name: John
Name: Jane, Age: 25
Name: Bob, Age: 30, City: New York
```

**Starter Code**

The `CalculatorDemo.java` file contains the following starter code:

```java
package academy.javapro.lab;

public class CalculatorDemo {
    public static void main(String[] args) {
        // TODO: Implement method calls here
    }

    // TODO: Implement overloaded add methods

    // TODO: Implement overloaded multiply methods

    // TODO: Implement overloaded printInfo methods
}

```

**Hints**

- Remember that Method Overloading is based on the number, type, and order of parameters, not on the return type.
- Be careful with type promotion in overloaded methods. For example, Java will automatically promote an int to a double
  if necessary.
- When overloading methods with similar functionality (like add and multiply), try to maintain consistent parameter
  ordering across overloads.
- Consider using varargs for methods that might take a variable number of parameters of the same type.

**Submission Instructions**

1. Fork the repository
2. Clone your fork
3. Navigate into the repository
4. Implement the required methods in the `BankingOperations.java` file
5. Test your implementation with various inputs
6. Git add, commit, and push to your fork
7. Submit a pull request
    - Set the title of the pull request to your first name and last name
    - In the comment, briefly explain your implementation approach and any challenges you faced

Remember, the goal is to learn and have fun! Don't hesitate to ask for help if you get stuck.