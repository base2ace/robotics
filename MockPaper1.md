**COMPUTER APPLICATIONS**

**Maximum Marks: 100**

**Time allowed: Two hours**

**Instructions:**
- Answers to this Paper must be written on the paper provided separately.
- You will not be allowed to write during the first 15 minutes. This time is to be spent in reading the question paper.
- The time given at the head of this Paper is the time allowed for writing the answers.
- This Paper is divided into two Sections.
- Attempt all questions from Section A and any four questions from Section B.
- The intended marks for questions or parts of questions are given in brackets [ ].

---

### SECTION A (40 Marks)

(Attempt all questions from this Section.)

**Question 1**

Choose the correct answers to the questions from the given options.  

(Do not copy the questions, write the correct answers only.)

[20]

1. **Which of the following is not a Java keyword?**
   - (a) `static`
   - (b) `Boolean`
   - (c) `void`
   - (d) `private`

2. **Which method can be used to find the length of a string in Java?**
   - (a) `length()`
   - (b) `size()`
   - (c) `getSize()`
   - (d) `getLength()`

3. **What is the result of 5 + 2 * 3?**
   - (a) 21
   - (b) 11
   - (c) 16
   - (d) 13

4. **Which of the following is used to terminate a loop in Java?**
   - (a) `exit`
   - (b) `break`
   - (c) `stop`
   - (d) `terminate`

5. **Identify the return type of a constructor.**
   - (a) `void`
   - (b) `class name`
   - (c) `int`
   - (d) `No return type`

6. **What will be the output of the following code snippet?**

   ```java
   int x = 5;
   System.out.println(x++);
   ```

   - (a) 5
   - (b) 6
   - (c) 4
   - (d) 7

7. **Which of the following is a bytecode in Java?**
   - (a) `Class code`
   - (b) `Object code`
   - (c) `Source code`
   - (d) `Machine code`

8. **What is encapsulation in Java?**
   - (a) Hiding complexity
   - (b) Hiding implementation details
   - (c) Using single inheritance
   - (d) Using multiple inheritance

9. **Which of the following is a checked exception in Java?**
   - (a) `NullPointerException`
   - (b) `ArrayIndexOutOfBoundsException`
   - (c) `IOException`
   - (d) `ArithmeticException`

10. **Which operator is used to allocate memory for an object in Java?**
    - (a) `alloc`
    - (b) `new`
    - (c) `malloc`
    - (d) `allocate`

11. **Which access modifier allows visibility only within the same package?**
    - (a) `public`
    - (b) `private`
    - (c) `protected`
    - (d) `default`

12. **What is the default value of a boolean variable in Java?**
    - (a) `true`
    - (b) `false`
    - (c) `1`
    - (d) `0`

13. **Which collection class does not allow duplicate elements?**
    - (a) `List`
    - (b) `Set`
    - (c) `Map`
    - (d) `Queue`

14. **What is the result of `Math.pow(2, 3)`?**
    - (a) `8`
    - (b) `6`
    - (c) `9`
    - (d) `12`

15. **Which of the following can be declared as abstract?**
    - (a) `Methods`
    - (b) `Classes`
    - (c) `Interfaces`
    - (d) `All of the above`

16. **Which method can be used to check if a string starts with a specified prefix?**
    - (a) `begins()`
    - (b) `startsWith()`
    - (c) `hasPrefix()`
    - (d) `init()`

17. **In which package is the String class defined?**
    - (a) `java.util`
    - (b) `java.lang`
    - (c) `java.io`
    - (d) `java.string`

18. **Which of the following is not a valid Java identifier?**
    - (a) `myVariable`
    - (b) `myVariable1`
    - (c) `1myVariable`
    - (d) `my_variable`

19. **What does the `equals()` method of the Object class compare?**
    - (a) References
    - (b) Values
    - (c) Memory addresses
    - (d) Hash codes

20. **What is the size of an `int` in Java?**
    - (a) 8 bits
    - (b) 16 bits
    - (c) 32 bits
    - (d) 64 bits

---

**Question 2**

Answer the following questions briefly:

1. **Write the Java expression for \((a + b) \times (c + d)\).**  
   [2]

2. **Evaluate the expression when \( x = 5 \):**

   \[
   x \times = x + 2 - x++ 
   \]
   
   [2]

3. **Convert the following while loop to a for loop:**

   ```java
   int i = 0;
   while (i < 10) {
       System.out.println(i);
       i++;
   }
   ```

   [2]

4. **Give the output of the following Character class methods:**

   (a) `Character.toLowerCase('A')`  
   (b) `Character.isDigit('9')`  
   
   [2]

5. **Rewrite the following code using the ternary operator:**

   ```java
   int x = 25;
   if (x > 10) {
       x = x + 5;
   } else {
       x = x - 5;
   }
   ```

   [2]

6. **Give the output of the following program segment:**

   ```java
   int n = 7531;
   int d;
   while(n > 0) {
       d = n % 10;
       System.out.println(d);
       n = n / 10;
   }
   ```

   [2]

7. **Give the output of the following String class methods:**

   (a) `"HELLO WORLD".indexOf('O')`  
   (b) `"apple".compareTo("banana")`  
   
   [2]

8. **Consider the given array and answer the questions given below:**

   ```java
   int x[] = {8, 14, 3, 27, 56, 42};
   ```

   (a) What is the length of the array?  
   (b) What is the value in `x[3]`?  
   
   [2]

9. **Name the following:**

   (a) The blueprint for creating objects.  
   (b) A variable that holds a memory address of an object.  

   [2]

10. **Write the value of `n` after execution:**

    ```java
    char ch = 'x';
    int n = ch + 10;
    ```

    [2]

---

### SECTION B (60 Marks)

(Answer any four questions from this Section.)

**Question 3**

Define a class with the following specifications:

- **Class name:** `Employee`
- **Member variables:**
  - `name` – name of the employee
  - `id` – ID of the employee
  - `salary` – salary of the employee

  (Declare the variables using appropriate data types)

- **Member methods:**

  - `void input()` – Accept name, id, and salary using methods of the Scanner class.
  - `void bonus()` – Calculate bonus based on the following criteria:
    - `salary > 50000` -> bonus is 20% of salary
    - `salary > 30000 and <= 50000` -> bonus is 15% of salary
    - `salary <= 30000` -> bonus is 10% of salary

  - `void display()` – Display employee name, id, salary, and bonus.

Call all the above methods in the main method using an object.

[15]

---

**Question 4**

Define a class to accept 5 integers from a user. Using selection sort technique, arrange them in descending order. Display the sorted array and the original array.

[15]

---

**Question 5**

Define a class to overload the function `calculate` as follows:

- `void calculate(int n)` - Print the

 factorial of `n`.
- `void calculate(int a, int b)` - Print the GCD of `a` and `b`.

[15]

---

**Question 6**

Define a class to accept a string and print the number of vowels, consonants, and spaces in the string.

Example: `S = “HELLO WORLD"`

Output: 
- Number of vowels – 3
- Number of consonants – 7
- Number of spaces – 1

[15]

---

**Question 7**

Define a class to accept values into an array of float data type of size 15. Accept a float value from the user and search in the array using the binary search method. If the value is found, display the message “Found” with its position where it is present in the array. Otherwise, display the message “Not found”.

[15]

---

**Question 8**

Define a class to accept values in an integer array of size 12. Find the product of even numbers and the sum of odd numbers entered. Display them separately.

Example: Input: `a[] = {2, 5, 4, 9, 8, 15, 3, 12, 6, 7, 11, 20}`

Output:
- Product of even numbers: \(2 \times 4 \times 8 \times 12 \times 6 \times 20\)
- Sum of odd numbers: \(5 + 9 + 15 + 3 + 7 + 11\)

[15]
