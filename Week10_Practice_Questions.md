# Week 10 Practice Questions
## Topics: Functions (Declaration, Definition, Calling), Passing Values, Passing Arrays, Pointers with Functions (Pass by Value & Reference)

---

## Part A: Basic Functions

### Easy Level

1. **Simple Function**
   - Write a function to print "Hello, World!" and call it from main.

2. **Function with Return**
   - Create a function that returns the square of a number.
   ```c
   int square(int n);
   ```

3. **Function with Parameters**
   - Write a function that takes two integers and returns their sum.

4. **Void Function**
   - Create a void function that prints the multiplication table of a given number.

5. **Function to Check Even/Odd**
   - Write a function that returns 1 if a number is even, 0 if odd.

### Medium Level

6. **Function Prototype**
   - Demonstrate the use of function declaration (prototype) before main and definition after main.

7. **Multiple Return Points**
   - Write a function with multiple return statements (e.g., checking if a number is positive, negative, or zero).

8. **Factorial Function**
   - Create a function to calculate factorial of a number.

9. **Prime Number Function**
   - Write a function to check if a number is prime (return 1 for prime, 0 for not prime).

10. **Power Function**
    - Create a function to calculate x^y (x raised to power y).

### Hard Level

11. **Fibonacci Function**
    - Write a function that returns the nth Fibonacci number.

12. **GCD Function**
    - Create a function to find GCD of two numbers using Euclidean algorithm.

13. **LCM Function**
    - Write a function to calculate LCM using the GCD function.

14. **Armstrong Number Function**
    - Create a function to check if a number is an Armstrong number.

15. **Digit Sum Function**
    - Write a function that returns the sum of digits of a number.

---

## Part B: Pass by Value

### Easy Level

16. **Basic Pass by Value**
    - Demonstrate that modifying a parameter inside a function doesn't affect the original variable.
    ```c
    void modify(int x) {
        x = 100;
    }
    int main() {
        int num = 10;
        modify(num);
        printf("%d", num); // Still prints 10
    }
    ```

17. **Swap Function (Pass by Value)**
    - Try to swap two numbers using pass by value and observe that it doesn't work.

18. **Increment Function**
    - Write a function that increments a number by 1 (pass by value) and show it doesn't change the original.

19. **Calculate Area**
    - Create a function that takes length and width, returns the area of a rectangle.

20. **Temperature Converter**
    - Write a function to convert Celsius to Fahrenheit (pass by value, return result).

### Medium Level

21. **Multiple Parameters**
    - Create a function that takes 3 numbers and returns their average.

22. **Character Function**
    - Write a function that takes a character and returns 1 if it's a vowel, 0 otherwise.

23. **Digit Count Function**
    - Create a function that counts the number of digits in an integer.

24. **Reverse Number Function**
    - Write a function that returns the reverse of a number.

25. **Perfect Number Function**
    - Create a function to check if a number is perfect.

---

## Part C: Pass by Reference (Using Pointers)

### Easy Level

26. **Basic Pass by Reference**
    - Write a function that modifies the original variable using pointers.
    ```c
    void modify(int *x) {
        *x = 100;
    }
    ```

27. **Swap Function (Pass by Reference)**
    - Write a function to swap two numbers using pointers.
    ```c
    void swap(int *a, int *b);
    ```

28. **Increment by Reference**
    - Create a function that increments a number using pointer.

29. **Double the Value**
    - Write a function that doubles the value of a variable using pointer.

30. **Make Positive**
    - Create a function that makes a number positive (absolute value) using pointer.

### Medium Level

31. **Multiple Outputs**
    - Write a function that takes two numbers and returns both sum and product using pointers.
    ```c
    void calculate(int a, int b, int *sum, int *product);
    ```

32. **Quotient and Remainder**
    - Create a function that returns both quotient and remainder of division using pointers.

33. **Min and Max**
    - Write a function that finds both minimum and maximum from two numbers using pointers.

34. **Circle Properties**
    - Create a function that calculates both area and circumference of a circle using pointers.

35. **Roots of Quadratic Equation**
    - Write a function that calculates both roots of a quadratic equation using pointers.

### Hard Level

36. **Sort Two Numbers**
    - Write a function that sorts two numbers in ascending order using pointers.

37. **Sort Three Numbers**
    - Create a function that sorts three numbers using pointers.

38. **Separate Digits**
    - Write a function that separates a 3-digit number into individual digits using pointers.

39. **Time Conversion**
    - Create a function that converts seconds into hours, minutes, and seconds using pointers.

40. **Coordinate Distance**
    - Write a function that calculates distance between two points and also returns the midpoint using pointers.

---

## Part D: Passing Arrays to Functions

### Easy Level

41. **Print Array Function**
    - Write a function that takes an array and its size, then prints all elements.
    ```c
    void printArray(int arr[], int size);
    ```

42. **Sum of Array Function**
    - Create a function that returns the sum of all array elements.

43. **Find Maximum Function**
    - Write a function that finds and returns the maximum element in an array.

44. **Find Minimum Function**
    - Create a function that finds and returns the minimum element in an array.

45. **Count Even Function**
    - Write a function that counts even numbers in an array.

### Medium Level

46. **Reverse Array Function**
    - Create a function that reverses an array in-place.
    ```c
    void reverseArray(int arr[], int size);
    ```

47. **Search Function**
    - Write a function that searches for an element and returns its index (-1 if not found).

48. **Copy Array Function**
    - Create a function that copies one array to another.

49. **Average Function**
    - Write a function that calculates and returns the average of array elements.

50. **Modify Array Elements**
    - Create a function that multiplies each array element by a given number.

### Hard Level

51. **Sort Array Function**
    - Write a function to sort an array in ascending order (use bubble sort or selection sort).

52. **Remove Duplicates Function**
    - Create a function that removes duplicates from an array and returns the new size.

53. **Merge Arrays Function**
    - Write a function that merges two arrays into a third array.

54. **Rotate Array Function**
    - Create a function that rotates an array by K positions.

55. **Second Largest Function**
    - Write a function that finds the second largest element in an array.

---

## Part E: Passing 2D Arrays to Functions

### Easy Level

56. **Print Matrix Function**
    - Write a function to print a 2D array (matrix).
    ```c
    void printMatrix(int mat[][MAX_COLS], int rows, int cols);
    ```

57. **Sum of Matrix Function**
    - Create a function that returns the sum of all elements in a matrix.

58. **Row Sum Function**
    - Write a function that calculates the sum of a specific row.

59. **Column Sum Function**
    - Create a function that calculates the sum of a specific column.

60. **Diagonal Sum Function**
    - Write a function that returns the sum of the primary diagonal.

### Medium Level

61. **Matrix Addition Function**
    - Create a function that adds two matrices.
    ```c
    void addMatrices(int a[][MAX], int b[][MAX], int result[][MAX], int rows, int cols);
    ```

62. **Matrix Transpose Function**
    - Write a function that transposes a matrix.

63. **Search in Matrix Function**
    - Create a function that searches for an element in a matrix and returns its position.

64. **Find Max in Matrix Function**
    - Write a function that finds the maximum element in a matrix.

65. **Check Symmetric Function**
    - Create a function that checks if a matrix is symmetric.

### Hard Level

66. **Matrix Multiplication Function**
    - Write a function to multiply two matrices.
    ```c
    void multiplyMatrices(int a[][MAX], int b[][MAX], int result[][MAX], int r1, int c1, int c2);
    ```

67. **Rotate Matrix Function**
    - Create a function that rotates a matrix by 90 degrees.

68. **Spiral Print Function**
    - Write a function that prints a matrix in spiral order.

69. **Check Identity Matrix Function**
    - Create a function that checks if a matrix is an identity matrix.

70. **Saddle Point Function**
    - Write a function that finds saddle point(s) in a matrix.

---

## Part F: Returning Arrays from Functions

### Medium Level

71. **Return Array Using Pointer**
    - Write a function that creates and returns an array (using static array or pointer).
    ```c
    int* createArray(int size);
    ```

72. **Return Modified Array**
    - Create a function that modifies an array and returns it.

73. **Generate Fibonacci Array**
    - Write a function that generates first N Fibonacci numbers and returns the array.

74. **Generate Prime Array**
    - Create a function that generates first N prime numbers and returns the array.

75. **Filter Even Numbers**
    - Write a function that filters even numbers from an array and returns a new array.

---

## Part G: Recursive Functions

### Easy Level

76. **Factorial Recursive**
    - Write a recursive function to calculate factorial.
    ```c
    int factorial(int n) {
        if (n <= 1) return 1;
        return n * factorial(n - 1);
    }
    ```

77. **Sum of N Numbers Recursive**
    - Create a recursive function to find sum of first N natural numbers.

78. **Power Recursive**
    - Write a recursive function to calculate x^n.

79. **Print N to 1 Recursive**
    - Create a recursive function to print numbers from N to 1.

80. **Print 1 to N Recursive**
    - Write a recursive function to print numbers from 1 to N.

### Medium Level

81. **Fibonacci Recursive**
    - Create a recursive function to find nth Fibonacci number.

82. **GCD Recursive**
    - Write a recursive function to find GCD of two numbers.

83. **Sum of Digits Recursive**
    - Create a recursive function to find sum of digits.

84. **Reverse Number Recursive**
    - Write a recursive function to reverse a number.

85. **Binary Search Recursive**
    - Create a recursive function for binary search in a sorted array.

### Hard Level

86. **Tower of Hanoi**
    - Write a recursive function to solve Tower of Hanoi problem.

87. **Array Sum Recursive**
    - Create a recursive function to find sum of array elements.

88. **Palindrome Check Recursive**
    - Write a recursive function to check if a string/number is palindrome.

89. **Permutations Recursive**
    - Create a recursive function to generate all permutations of a string.

90. **Subset Sum Recursive**
    - Write a recursive function to check if a subset with given sum exists.

---

## Part H: Function Pointers

### Easy Level

91. **Basic Function Pointer**
    - Declare a function pointer and call a function through it.
    ```c
    int add(int a, int b) { return a + b; }
    int (*funcPtr)(int, int) = add;
    ```

92. **Function Pointer Array**
    - Create an array of function pointers for basic operations (add, subtract, multiply, divide).

93. **Callback Function**
    - Write a function that takes another function as a parameter (callback).

94. **Function Pointer as Return Type**
    - Create a function that returns a function pointer.

95. **Calculator Using Function Pointers**
    - Build a calculator using function pointers for different operations.

---

## Part I: Advanced Function Concepts

### Medium Level

96. **Static Variables in Functions**
    - Demonstrate the use of static variables inside functions.
    ```c
    void counter() {
        static int count = 0;
        count++;
        printf("%d ", count);
    }
    ```

97. **Inline Functions**
    - Explain and demonstrate inline functions (if supported).

98. **Variadic Functions**
    - Create a function that accepts variable number of arguments.
    ```c
    int sum(int count, ...);
    ```

99. **Function Overloading Simulation**
    - Simulate function overloading using different function names.

100. **Nested Function Calls**
     - Demonstrate nested function calls and trace the execution.

---

## Bonus Challenge Questions

101. **Menu-Driven Program**
     - Create a menu-driven program using functions for each operation.

102. **String Functions**
     - Implement your own strlen, strcpy, strcmp functions.

103. **Matrix Operations Library**
     - Create a library of matrix operations (add, subtract, multiply, transpose).

104. **Sorting Library**
     - Implement multiple sorting algorithms as separate functions.

105. **Mathematical Functions Library**
     - Create a library with functions for factorial, GCD, LCM, prime check, etc.

---

## Tips for Practice:
- Always declare function prototypes before main()
- Use meaningful function names (verbs for actions)
- Keep functions focused on a single task
- Use const for parameters that shouldn't be modified
- For arrays, always pass size as a parameter
- Remember: arrays are always passed by reference (pointer to first element)
- Use pass by reference when you need to modify multiple values
- Document your functions with comments explaining parameters and return values
- Test functions with edge cases (empty arrays, negative numbers, zero, etc.)
- Practice tracing recursive function calls with small inputs
- Understand the difference between:
  - `void func(int arr[])` - array parameter
  - `void func(int *arr)` - pointer parameter (equivalent to above)
  - `void func(int arr[][COLS])` - 2D array parameter
- For pass by reference, always check if pointer is NULL before dereferencing
- Use descriptive parameter names in function declarations
