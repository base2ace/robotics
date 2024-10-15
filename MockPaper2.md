## ICSE Class X Computer Applications Mock Exam

### Time: 2 hours

### SECTION A (40 Marks)

#### Question 1

Select the correct answer for each of the following questions. Each question carries 2 marks.

1. **Which of the following is a valid declaration of an array in Java?**

   a) `int arr[] = new int[5];`

   b) `int arr[5];`

   c) `int arr = new int[5];`

   d) `arr[5] = new int[];`

2. **Which of the following loops is guaranteed to execute at least once?**

   a) `for` loop

   b) `while` loop

   c) `do-while` loop

   d) `foreach` loop

3. **What is the output of the following code snippet?**

   ```java
   int a = 10, b = 5;
   System.out.println(a > b ? a : b);
   ```

   a) 5

   b) 10

   c) true

   d) false

4. **Which of the following is not a feature of Java?**

   a) Object-oriented

   b) Platform-dependent

   c) Secure

   d) Multithreaded

5. **Which method is used to convert a string to a primitive float value?**

   a) `Float.valueOf()`

   b) `Float.toString()`

   c) `Float.parseFloat()`

   d) `Float.floatValue()`

6. **Which of the following statements is true about constructors?**

   a) They can return a value.

   b) They are called explicitly using the `new` keyword.

   c) They must have the same name as the class.

   d) They can be static.

7. **What is the size of a `char` in Java?**

   a) 8 bits

   b) 16 bits

   c) 32 bits

   d) 64 bits

8. **Which keyword is used to inherit a class in Java?**

   a) `implements`

   b) `inherits`

   c) `extends`

   d) `super`

9. **Which of the following is a superclass of every class in Java?**

   a) `String`

   b) `Object`

   c) `Class`

   d) `Array`

10. **Which of the following data types is not a primitive type in Java?**

    a) `int`

    b) `boolean`

    c) `float`

    d) `String`

11. **What will be the output of the following code?**

    ```java
    String str = "Hello, World!";
    System.out.println(str.substring(7, 12));
    ```

    a) Hello

    b) World

    c) , Wor

    d) , Wor!

12. **Which of the following is used to find and fix bugs in Java programs?**

    a) JDK

    b) JRE

    c) JVM

    d) Debugger

13. **Which of the following is not a valid access modifier in Java?**

    a) `public`

    b) `protected`

    c) `private`

    d) `package`

14. **What will be the output of the following code snippet?**

    ```java
    int i = 0;
    while (i < 5) {
        System.out.print(i + " ");
        i++;
    }
    ```

    a) 0 1 2 3 4

    b) 1 2 3 4 5

    c) 0 1 2 3 4 5

    d) 1 2 3 4

15. **Which of the following methods is used to find the character at a specific index in a string?**

    a) `charAt()`

    b) `getChar()`

    c) `indexOf()`

    d) `substring()`

16. **What is the default value of a `char` array element in Java?**

    a) `null`

    b) `\u0000`

    c) `0`

    d) `space`

17. **Which of the following operators is used to compare two values for equality?**

    a) `=`  

    b) `==`

    c) `!=`

    d) `equals()`

18. **Which exception is thrown when dividing by zero in Java?**

    a) `NullPointerException`

    b) `ArithmeticException`

    c) `IndexOutOfBoundsException`

    d) `NumberFormatException`

19. **Which of the following is the correct syntax for creating a two-dimensional array in Java?**

    a) `int[][] arr = new int[3][3];`

    b) `int arr[][] = new int[3,3];`

    c) `int[] arr = new int[3][3];`

    d) `int arr = new int[3][3];`

20. **What is the output of the following code?**

    ```java
    int num = 5;
    for (int i = 0; i < num; i++) {
        if (i == 3) {
            continue;
        }
        System.out.print(i + " ");
    }
    ```

    a) 0 1 2 4 5

    b) 0 1 2 3 4

    c) 0 1 2 4

    d) 1 2 3 4

---

### SECTION B (60 Marks)

#### Question 2

**Write a Java program to accept an integer array of size 10. Then, search for a given number in the array using linear search and print its index. If the number is not found, display a message indicating so.**  

[15]

---

#### Question 3

**Define a class to accept a string from the user and print it in reverse order. Also, count and print the number of vowels in the string.**

Example: `Input: "Hello World"`

Output: 
- Reversed String: `dlroW olleH`
- Number of vowels: `3`

[15]

---

#### Question 4

**Define a class to accept an integer array of size 8. Sort the array in ascending order using bubble sort and print the sorted array.**  

[15]

---

#### Question 5

**Define a class to overload the method `calculate` to perform the following operations:**

- `void calculate(double radius)` - Calculate and print the area of a circle using the formula:  
  \[\text{Area} = \pi \times \text{radius}^2\]
  
- `void calculate(double length, double breadth)` - Calculate and print the area of a rectangle using the formula:  
  \[\text{Area} = \text{length} \times \text{breadth}\]

[15]

---

#### Question 6

**Define a class to accept a string and print the number of uppercase letters, lowercase letters, digits, and special characters in the string.**

Example: `Input: "Hello123!"`

Output: 
- Uppercase letters: `1`
- Lowercase letters: `4`
- Digits: `3`
- Special characters: `1`

[15]

---

#### Question 7

**Define a class to accept values into a 5x5 matrix of integers. Calculate and print the sum of each row and each column.**

Example: 

Input:  
\[  
\[1, 2, 3, 4, 5\],  
\[6, 7, 8, 9, 10\],  
\[11, 12, 13, 14, 15\],  
\[16, 17, 18, 19, 20\],  
\[21, 22, 23, 24, 25\]  
\]  

Output:  
- Sum of rows: `15, 40, 65, 90, 115`
- Sum of columns: `55, 65, 75, 85, 95`

[15]

---

#### Question 8

**Define a class to accept values into a double array of size 10. Find and print the maximum and minimum values in the array.**  

Example: `Input: [2.5, 3.1, 9.7, 4.3, 1.9, 7.6, 8.2, 0.5, 6.4, 5.8]`

Output: 
- Maximum value: `9.7`
- Minimum value: `0.5`

[15]
