
### SECTION A

**Question 1**

1. **Which of the following is not a Java keyword?**
   - **(b) Boolean**  
     Explanation: `Boolean` is not a keyword in Java; it should be `boolean`.

2. **Which method can be used to find the length of a string in Java?**
   - **(a) length()**  
     Explanation: The `length()` method is used to find the length of a string in Java.

3. **What is the result of 5 + 2 * 3?**
   - **(d) 11**  
     Explanation: According to operator precedence, multiplication is performed before addition: \(5 + (2 \times 3) = 5 + 6 = 11\).

4. **Which of the following is used to terminate a loop in Java?**
   - **(b) break**  
     Explanation: The `break` statement is used to terminate loops.

5. **Identify the return type of a constructor.**
   - **(d) No return type**  
     Explanation: Constructors do not have a return type, not even `void`.

6. **What will be the output of the following code snippet?**

   ```java
   int x = 5;
   System.out.println(x++);
   ```

   - **(a) 5**  
     Explanation: The `x++` is a post-increment operation, so it returns `5` first and then increments `x` to `6`.

7. **Which of the following is a bytecode in Java?**
   - **(d) Machine code**  
     Explanation: Java bytecode is the intermediate representation executed by the Java Virtual Machine (JVM).

8. **What is encapsulation in Java?**
   - **(b) Hiding implementation details**  
     Explanation: Encapsulation is the technique of hiding implementation details and exposing only the functionality through interfaces.

9. **Which of the following is a checked exception in Java?**
   - **(c) IOException**  
     Explanation: `IOException` is a checked exception that must be handled or declared in the method signature.

10. **Which operator is used to allocate memory for an object in Java?**
    - **(b) new**  
      Explanation: The `new` operator is used to create objects in Java.

11. **Which access modifier allows visibility only within the same package?**
    - **(d) default**  
      Explanation: The default access modifier (no modifier specified) allows package-level access.

12. **What is the default value of a boolean variable in Java?**
    - **(b) false**  
      Explanation: The default value of a boolean variable is `false`.

13. **Which collection class does not allow duplicate elements?**
    - **(b) Set**  
      Explanation: A `Set` does not allow duplicate elements.

14. **What is the result of `Math.pow(2, 3)`?**
    - **(a) 8**  
      Explanation: `Math.pow(2, 3)` calculates \(2^3 = 8\).

15. **Which of the following can be declared as abstract?**
    - **(d) All of the above**  
      Explanation: Methods, classes, and interfaces can all be declared as abstract in Java.

16. **Which method can be used to check if a string starts with a specified prefix?**
    - **(b) startsWith()**  
      Explanation: The `startsWith()` method checks if a string begins with the specified prefix.

17. **In which package is the String class defined?**
    - **(b) java.lang**  
      Explanation: The `String` class is part of the `java.lang` package.

18. **Which of the following is not a valid Java identifier?**
    - **(c) 1myVariable**  
      Explanation: Identifiers cannot start with a digit in Java.

19. **What does the `equals()` method of the Object class compare?**
    - **(b) Values**  
      Explanation: The `equals()` method is used to compare the values of two objects for equality.

20. **What is the size of an `int` in Java?**
    - **(c) 32 bits**  
      Explanation: An `int` in Java is 32 bits in size.

---

**Question 2**

1. **Write the Java expression for \((a + b) \times (c + d)\).**  
   - **Answer:** `(a + b) * (c + d)`

2. **Evaluate the expression when \( x = 5 \):**

   \[
   x \times = x + 2 - x++ 
   \]

   - **Answer:** \( x = 5 \times (5 + 2 - 5) = 5 \times 2 = 10 \)

     Explanation:
     - Initial `x = 5`.
     - Calculate: `x *= x + 2 - x++`.
     - Substitute and evaluate: \(5 \times (5 + 2 - 5) = 5 \times 2 = 10\).

3. **Convert the following while loop to a for loop:**

   ```java
   int i = 0;
   while (i < 10) {
       System.out.println(i);
       i++;
   }
   ```

   - **Answer:**

     ```java
     for (int i = 0; i < 10; i++) {
         System.out.println(i);
     }
     ```

4. **Give the output of the following Character class methods:**

   - **(a) `Character.toLowerCase('A')`**  
     **Answer:** `'a'`

   - **(b) `Character.isDigit('9')`**  
     **Answer:** `true`

5. **Rewrite the following code using the ternary operator:**

   ```java
   int x = 25;
   if (x > 10) {
       x = x + 5;
   } else {
       x = x - 5;
   }
   ```

   - **Answer:**

     ```java
     int x = 25;
     x = (x > 10) ? (x + 5) : (x - 5);
     ```

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

   - **Answer:**

     ```
     1
     3
     5
     7
     ```

     Explanation: The loop extracts each digit from the number starting from the least significant digit.

7. **Give the output of the following String class methods:**

   - **(a) `"HELLO WORLD".indexOf('O')`**  
     **Answer:** `4`  
     Explanation: The index of the first occurrence of `'O'` is 4 (zero-based index).

   - **(b) `"apple".compareTo("banana")`**  
     **Answer:** `-1` (or any negative number)  
     Explanation: `"apple"` is lexicographically less than `"banana"`, so the result is a negative number.

8. **Consider the given array and answer the questions given below:**

   ```java
   int x[] = {8, 14, 3, 27, 56, 42};
   ```

   - **(a) What is the length of the array?**  
     **Answer:** `6`  
     Explanation: There are 6 elements in the array.

   - **(b) What is the value in `x[3]`?**  
     **Answer:** `27`  
     Explanation: The value at index 3 is `27`.

9. **Name the following:**

   - **(a) The blueprint for creating objects.**  
     **Answer:** `Class`

   - **(b) A variable that holds a memory address of an object.**  
     **Answer:** `Reference variable`

10. **Write the value of `n` after execution:**

    ```java
    char ch = 'x';
    int n = ch + 10;
    ```

    - **Answer:** `130`  
      Explanation: The ASCII value of `'x'` is 120, so `n = 120 + 10 = 130`.

---

### SECTION B

**Question 3**

Define a class with the following specifications:

```java
import java.util.Scanner;

class Employee {
    // Member variables
    String name;
    int id;
    double salary;
    double bonus;

    // Member methods
    void input() {
        Scanner scanner = new Scanner(System.in);
        System.out.print("Enter name: ");
        name = scanner.nextLine();
        System.out.print("Enter ID: ");
        id = scanner.nextInt();
        System.out.print("Enter salary: ");
        salary = scanner.nextDouble();
    }

    void bonus() {
        if (salary > 50000) {
            bonus = salary * 0.20;
        } else if (salary > 30000 && salary <= 50000) {
            bonus = salary * 0.15;
        } else {
            bonus = salary * 0.10;
        }
    }

    void display() {
        System.out.println("Name: "

 + name);
        System.out.println("ID: " + id);
        System.out.println("Salary: " + salary);
        System.out.println("Bonus: " + bonus);
    }

    public static void main(String[] args) {
        Employee emp = new Employee();
        emp.input();
        emp.bonus();
        emp.display();
    }
}
```

**Explanation:**

- **`input()` Method:** Uses the `Scanner` class to accept user input for `name`, `id`, and `salary`.
- **`bonus()` Method:** Calculates the bonus based on salary using the given conditions.
- **`display()` Method:** Prints the employee's details along with the calculated bonus.

---

**Question 4**

Define a class to accept 5 integers from a user and sort them in descending order using selection sort.

```java
import java.util.Scanner;

class SelectionSortDescending {
    int[] numbers = new int[5];
    
    void input() {
        Scanner scanner = new Scanner(System.in);
        System.out.println("Enter 5 integers:");
        for (int i = 0; i < numbers.length; i++) {
            numbers[i] = scanner.nextInt();
        }
    }

    void selectionSortDescending() {
        for (int i = 0; i < numbers.length - 1; i++) {
            int maxIndex = i;
            for (int j = i + 1; j < numbers.length; j++) {
                if (numbers[j] > numbers[maxIndex]) {
                    maxIndex = j;
                }
            }
            int temp = numbers[maxIndex];
            numbers[maxIndex] = numbers[i];
            numbers[i] = temp;
        }
    }

    void display() {
        System.out.println("Original Array: ");
        for (int num : numbers) {
            System.out.print(num + " ");
        }
        System.out.println("\nSorted Array in Descending Order: ");
        for (int num : numbers) {
            System.out.print(num + " ");
        }
    }

    public static void main(String[] args) {
        SelectionSortDescending obj = new SelectionSortDescending();
        obj.input();
        obj.selectionSortDescending();
        obj.display();
    }
}
```

**Explanation:**

- **`input()` Method:** Accepts 5 integers from the user.
- **`selectionSortDescending()` Method:** Sorts the array in descending order using selection sort.
- **`display()` Method:** Displays both the original and sorted arrays.

---

**Question 5**

Define a class to overload the function `calculate`.

```java
class Calculator {

    // Method to calculate the factorial of a number
    void calculate(int n) {
        long factorial = 1;
        for (int i = 1; i <= n; i++) {
            factorial *= i;
        }
        System.out.println("Factorial of " + n + " is: " + factorial);
    }

    // Method to calculate the GCD of two numbers
    void calculate(int a, int b) {
        int gcd = 1;
        for (int i = 1; i <= a && i <= b; i++) {
            if (a % i == 0 && b % i == 0) {
                gcd = i;
            }
        }
        System.out.println("GCD of " + a + " and " + b + " is: " + gcd);
    }

    public static void main(String[] args) {
        Calculator calc = new Calculator();
        calc.calculate(5);       // Factorial
        calc.calculate(20, 30);  // GCD
    }
}
```

**Explanation:**

- **Factorial Calculation:** Calculates the factorial of `n` using a loop.
- **GCD Calculation:** Calculates the GCD of two numbers using the Euclidean algorithm.

---

**Question 6**

Define a class to count the number of vowels, consonants, and spaces in a string.

```java
class StringAnalysis {
    void analyzeString(String s) {
        int vowels = 0, consonants = 0, spaces = 0;
        s = s.toLowerCase(); // Convert string to lowercase to simplify comparisons
        for (int i = 0; i < s.length(); i++) {
            char ch = s.charAt(i);
            if (ch == 'a' || ch == 'e' || ch == 'i' || ch == 'o' || ch == 'u') {
                vowels++;
            } else if (ch >= 'a' && ch <= 'z') {
                consonants++;
            } else if (ch == ' ') {
                spaces++;
            }
        }
        System.out.println("Number of vowels: " + vowels);
        System.out.println("Number of consonants: " + consonants);
        System.out.println("Number of spaces: " + spaces);
    }

    public static void main(String[] args) {
        StringAnalysis obj = new StringAnalysis();
        obj.analyzeString("HELLO WORLD");
    }
}
```

**Explanation:**

- **Vowels:** Checks if the character is a vowel.
- **Consonants:** Checks if the character is a letter and not a vowel.
- **Spaces:** Checks if the character is a space.

---

**Question 7**

Define a class to search a float value in an array using binary search.

```java
import java.util.Scanner;
import java.util.Arrays;

class BinarySearchFloat {
    float[] array = new float[15];

    void input() {
        Scanner scanner = new Scanner(System.in);
        System.out.println("Enter 15 float values:");
        for (int i = 0; i < array.length; i++) {
            array[i] = scanner.nextFloat();
        }
        Arrays.sort(array); // Sort the array for binary search
    }

    void binarySearch(float value) {
        int low = 0, high = array.length - 1;
        boolean found = false;
        while (low <= high) {
            int mid = (low + high) / 2;
            if (array[mid] == value) {
                found = true;
                System.out.println("Found at position: " + (mid + 1));
                break;
            } else if (array[mid] < value) {
                low = mid + 1;
            } else {
                high = mid - 1;
            }
        }
        if (!found) {
            System.out.println("Not found");
        }
    }

    public static void main(String[] args) {
        BinarySearchFloat obj = new BinarySearchFloat();
        obj.input();
        Scanner scanner = new Scanner(System.in);
        System.out.print("Enter value to search: ");
        float value = scanner.nextFloat();
        obj.binarySearch(value);
    }
}
```

**Explanation:**

- **Binary Search:** Searches for a float value in a sorted array.
- **Output:** Displays "Found" with the position if the value is found, otherwise "Not found."

---

**Question 8**

Define a class to find the product of even numbers and the sum of odd numbers in an integer array.

```java
class EvenOddProductSum {
    int[] numbers = new int[12];

    void input() {
        Scanner scanner = new Scanner(System.in);
        System.out.println("Enter 12 integers:");
        for (int i = 0; i < numbers.length; i++) {
            numbers[i] = scanner.nextInt();
        }
    }

    void calculate() {
        int productOfEvens = 1, sumOfOdds = 0;
        for (int num : numbers) {
            if (num % 2 == 0) {
                productOfEvens *= num;
            } else {
                sumOfOdds += num;
            }
        }
        System.out.println("Product of even numbers: " + productOfEvens);
        System.out.println("Sum of odd numbers: " + sumOfOdds);
    }

    public static void main(String[] args) {
        EvenOddProductSum obj = new EvenOddProductSum();
        obj.input();
        obj.calculate();
    }
}
```

**Explanation:**

- **Product of Evens:** Multiplies all even numbers in the array.
- **Sum of Odds:** Adds all odd numbers in the array.

