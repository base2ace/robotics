## SECTION A Solutions

### Multiple-Choice Questions

1. **Which of the following is a valid declaration of an array in Java?**

   **Answer:** a) `int arr[] = new int[5];`  
   **Explanation:** This syntax correctly declares and initializes an integer array of size 5.

2. **Which of the following loops is guaranteed to execute at least once?**

   **Answer:** c) `do-while` loop  
   **Explanation:** A `do-while` loop executes the block of code at least once before checking the condition.

3. **What is the output of the following code snippet?**

   ```java
   int a = 10, b = 5;
   System.out.println(a > b ? a : b);
   ```

   **Answer:** b) 10  
   **Explanation:** The ternary operator evaluates to `a` because `a > b` is true.

4. **Which of the following is not a feature of Java?**

   **Answer:** b) Platform-dependent  
   **Explanation:** Java is platform-independent, which is one of its core features due to the JVM.

5. **Which method is used to convert a string to a primitive float value?**

   **Answer:** c) `Float.parseFloat()`  
   **Explanation:** The `parseFloat()` method converts a string to a `float` primitive.

6. **Which of the following statements is true about constructors?**

   **Answer:** c) They must have the same name as the class.  
   **Explanation:** Constructors in Java must have the same name as the class and have no return type.

7. **What is the size of a `char` in Java?**

   **Answer:** b) 16 bits  
   **Explanation:** In Java, the `char` data type is 16 bits to support Unicode characters.

8. **Which keyword is used to inherit a class in Java?**

   **Answer:** c) `extends`  
   **Explanation:** The `extends` keyword is used to inherit a class in Java.

9. **Which of the following is a superclass of every class in Java?**

   **Answer:** b) `Object`  
   **Explanation:** Every class in Java implicitly extends the `Object` class.

10. **Which of the following data types is not a primitive type in Java?**

    **Answer:** d) `String`  
    **Explanation:** `String` is a class in Java, not a primitive data type.

11. **What will be the output of the following code?**

    ```java
    String str = "Hello, World!";
    System.out.println(str.substring(7, 12));
    ```

    **Answer:** b) World  
    **Explanation:** The `substring()` method extracts characters from index 7 to 11 (12 is exclusive).

12. **Which of the following is used to find and fix bugs in Java programs?**

    **Answer:** d) Debugger  
    **Explanation:** A debugger is a tool used to test and debug programs.

13. **Which of the following is not a valid access modifier in Java?**

    **Answer:** d) `package`  
    **Explanation:** `package` is not an access modifier. The valid modifiers are `public`, `protected`, `private`, and default (package-private, which has no keyword).

14. **What will be the output of the following code snippet?**

    ```java
    int i = 0;
    while (i < 5) {
        System.out.print(i + " ");
        i++;
    }
    ```

    **Answer:** a) 0 1 2 3 4  
    **Explanation:** The loop prints numbers from 0 to 4 because `i` starts at 0 and increments until it is less than 5.

15. **Which of the following methods is used to find the character at a specific index in a string?**

    **Answer:** a) `charAt()`  
    **Explanation:** The `charAt()` method returns the character at a specific index in a string.

16. **What is the default value of a `char` array element in Java?**

    **Answer:** b) `\u0000`  
    **Explanation:** The default value of a `char` array element is the null character `\u0000`.

17. **Which of the following operators is used to compare two values for equality?**

    **Answer:** b) `==`  
    **Explanation:** The `==` operator is used to compare two primitive values for equality.

18. **Which exception is thrown when dividing by zero in Java?**

    **Answer:** b) `ArithmeticException`  
    **Explanation:** An `ArithmeticException` is thrown when an arithmetic operation, such as division by zero, occurs.

19. **Which of the following is the correct syntax for creating a two-dimensional array in Java?**

    **Answer:** a) `int[][] arr = new int[3][3];`  
    **Explanation:** This syntax correctly declares a 3x3 two-dimensional array.

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

    **Answer:** c) 0 1 2 4  
    **Explanation:** The `continue` statement skips the iteration when `i == 3`, so 3 is not printed.

---

## SECTION B Solutions

### Question 2

**Write a Java program to accept an integer array of size 10. Then, search for a given number in the array using linear search and print its index. If the number is not found, display a message indicating so.**

```java
import java.util.Scanner;

class LinearSearch {
    int[] array = new int[10];

    void input() {
        Scanner scanner = new Scanner(System.in);
        System.out.println("Enter 10 integers:");
        for (int i = 0; i < array.length; i++) {
            array[i] = scanner.nextInt();
        }
    }

    void search(int key) {
        boolean found = false;
        for (int i = 0; i < array.length; i++) {
            if (array[i] == key) {
                System.out.println("Element found at index: " + i);
                found = true;
                break;
            }
        }
        if (!found) {
            System.out.println("Element not found in the array.");
        }
    }

    public static void main(String[] args) {
        LinearSearch ls = new LinearSearch();
        ls.input();
        Scanner scanner = new Scanner(System.in);
        System.out.print("Enter the number to search: ");
        int key = scanner.nextInt();
        ls.search(key);
    }
}
```

**Explanation:**  
- **Input Method:** Accepts 10 integers from the user and stores them in an array.
- **Search Method:** Performs a linear search to find the specified number and prints its index if found; otherwise, it indicates the number is not present.

---

### Question 3

**Define a class to accept a string from the user and print it in reverse order. Also, count and print the number of vowels in the string.**

```java
import java.util.Scanner;

class StringManipulation {
    String input;

    void input() {
        Scanner scanner = new Scanner(System.in);
        System.out.println("Enter a string:");
        input = scanner.nextLine();
    }

    void reverseAndCountVowels() {
        String reversed = "";
        int vowelCount = 0;
        String vowels = "aeiouAEIOU";

        for (int i = input.length() - 1; i >= 0; i--) {
            char ch = input.charAt(i);
            reversed += ch;
            if (vowels.indexOf(ch) != -1) {
                vowelCount++;
            }
        }

        System.out.println("Reversed String: " + reversed);
        System.out.println("Number of vowels: " + vowelCount);
    }

    public static void main(String[] args) {
        StringManipulation sm = new StringManipulation();
        sm.input();
        sm.reverseAndCountVowels();
    }
}
```

**Explanation:**  
- **Reverse and Count Vowels Method:** Reverses the string and counts the number of vowels by checking if each character is in the set of vowels.

---

### Question 4

**Define a class to accept an integer array of size 8. Sort the array in ascending order using bubble sort and print the sorted array.**

```java
import java.util.Scanner;

class BubbleSort {
    int[] array = new int[8];

    void input() {
        Scanner scanner = new Scanner(System.in);
        System.out.println("Enter 8 integers:");
        for (int i = 0; i < array.length; i++) {
            array[i] = scanner.nextInt();
        }
    }

    void bubbleSort() {
        int n = array.length;
        for (int i = 0; i < n - 1; i++) {
            for (int j = 0; j < n - i - 1; j++) {
                if (array[j] > array[j + 1]) {
                    // Swap array[j] and array[j+1]
                    int temp = array[j];
                    array[j] = array[j + 1];
                    array[j + 1] = temp;
                }
            }
        }
    }

    void display()

 {
        System.out.println("Sorted array:");
        for (int i : array) {
            System.out.print(i + " ");
        }
        System.out.println();
    }

    public static void main(String[] args) {
        BubbleSort bs = new BubbleSort();
        bs.input();
        bs.bubbleSort();
        bs.display();
    }
}
```

**Explanation:**  
- **Bubble Sort Method:** Iterates over the array, repeatedly swapping adjacent elements if they are in the wrong order, thus sorting the array.

---

### Question 5

**Define a class to overload the method `calculate` to perform the following operations:**

- `void calculate(double radius)` - Calculate and print the area of a circle using the formula:  
  \[\text{Area} = \pi \times \text{radius}^2\]
  
- `void calculate(double length, double breadth)` - Calculate and print the area of a rectangle using the formula:  
  \[\text{Area} = \text{length} \times \text{breadth}\]

```java
class CalculateArea {

    void calculate(double radius) {
        double area = Math.PI * radius * radius;
        System.out.printf("Area of Circle: %.2f\n", area);
    }

    void calculate(double length, double breadth) {
        double area = length * breadth;
        System.out.printf("Area of Rectangle: %.2f\n", area);
    }

    public static void main(String[] args) {
        CalculateArea ca = new CalculateArea();
        ca.calculate(5.0); // Circle
        ca.calculate(4.0, 6.0); // Rectangle
    }
}
```

**Explanation:**  
- **Overloaded Methods:** The `calculate` method is overloaded to handle both circle and rectangle area calculations.

---

### Question 6

**Define a class to accept a string and print the number of uppercase letters, lowercase letters, digits, and special characters in the string.**

```java
import java.util.Scanner;

class CharacterCount {
    String input;

    void input() {
        Scanner scanner = new Scanner(System.in);
        System.out.println("Enter a string:");
        input = scanner.nextLine();
    }

    void countCharacters() {
        int uppercase = 0, lowercase = 0, digits = 0, specialChars = 0;

        for (int i = 0; i < input.length(); i++) {
            char ch = input.charAt(i);
            if (Character.isUpperCase(ch)) {
                uppercase++;
            } else if (Character.isLowerCase(ch)) {
                lowercase++;
            } else if (Character.isDigit(ch)) {
                digits++;
            } else {
                specialChars++;
            }
        }

        System.out.println("Uppercase letters: " + uppercase);
        System.out.println("Lowercase letters: " + lowercase);
        System.out.println("Digits: " + digits);
        System.out.println("Special characters: " + specialChars);
    }

    public static void main(String[] args) {
        CharacterCount cc = new CharacterCount();
        cc.input();
        cc.countCharacters();
    }
}
```

**Explanation:**  
- **Count Characters Method:** Iterates over the string, using `Character` class methods to count uppercase, lowercase, digits, and special characters.

---

### Question 7

**Define a class to accept values into a 5x5 matrix of integers. Calculate and print the sum of each row and each column.**

```java
import java.util.Scanner;

class MatrixSum {
    int[][] matrix = new int[5][5];

    void input() {
        Scanner scanner = new Scanner(System.in);
        System.out.println("Enter 25 integers for the 5x5 matrix:");
        for (int i = 0; i < 5; i++) {
            for (int j = 0; j < 5; j++) {
                matrix[i][j] = scanner.nextInt();
            }
        }
    }

    void calculateSums() {
        int[] rowSums = new int[5];
        int[] colSums = new int[5];

        for (int i = 0; i < 5; i++) {
            for (int j = 0; j < 5; j++) {
                rowSums[i] += matrix[i][j];
                colSums[j] += matrix[i][j];
            }
        }

        System.out.println("Sum of rows:");
        for (int sum : rowSums) {
            System.out.print(sum + " ");
        }
        System.out.println();

        System.out.println("Sum of columns:");
        for (int sum : colSums) {
            System.out.print(sum + " ");
        }
        System.out.println();
    }

    public static void main(String[] args) {
        MatrixSum ms = new MatrixSum();
        ms.input();
        ms.calculateSums();
    }
}
```

**Explanation:**  
- **Calculate Sums Method:** Computes the sum of elements for each row and each column separately, storing results in corresponding arrays.

---

### Question 8

**Define a class to accept values into a double array of size 10. Find and print the maximum and minimum values in the array.**

```java
import java.util.Scanner;

class MaxMinArray {
    double[] array = new double[10];

    void input() {
        Scanner scanner = new Scanner(System.in);
        System.out.println("Enter 10 double values:");
        for (int i = 0; i < array.length; i++) {
            array[i] = scanner.nextDouble();
        }
    }

    void findMaxMin() {
        double max = array[0];
        double min = array[0];

        for (double v : array) {
            if (v > max) {
                max = v;
            }
            if (v < min) {
                min = v;
            }
        }

        System.out.printf("Maximum value: %.2f\n", max);
        System.out.printf("Minimum value: %.2f\n", min);
    }

    public static void main(String[] args) {
        MaxMinArray mma = new MaxMinArray();
        mma.input();
        mma.findMaxMin();
    }
}
```

**Explanation:**  
- **Find Max and Min Method:** Iterates over the array to find the maximum and minimum values by comparing each element.

