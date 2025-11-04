# Week 7 Practice Questions
## Topics: Basic Loops (for, while, do-while), Referencing, Introduction to Pointers

---

## Part A: Basic Loops

### Easy Level

1. **Sum of N Numbers**
   - Write a program using a `for` loop to calculate the sum of first N natural numbers.
   - Input: N = 5
   - Output: Sum = 15

2. **Print Even Numbers**
   - Use a `while` loop to print all even numbers from 1 to 20.

3. **Factorial Calculator**
   - Write a program using a `do-while` loop to calculate the factorial of a number.
   - Input: 5
   - Output: 120

4. **Multiplication Table**
   - Use a `for` loop to print the multiplication table of a given number (1 to 10).

5. **Count Digits**
   - Write a program using a `while` loop to count the number of digits in a given integer.
   - Input: 12345
   - Output: 5 digits

### Medium Level

6. **Reverse a Number**
   - Use a `while` loop to reverse the digits of a number.
   - Input: 1234
   - Output: 4321

7. **Prime Number Checker**
   - Write a program using a `for` loop to check if a number is prime.

8. **Fibonacci Series**
   - Generate the first N Fibonacci numbers using a `for` loop.
   - Input: N = 7
   - Output: 0, 1, 1, 2, 3, 5, 8

9. **Sum of Digits**
   - Use a `do-while` loop to find the sum of digits of a number until it becomes a single digit.
   - Input: 9875
   - Output: 9+8+7+5 = 29 → 2+9 = 11 → 1+1 = 2

10. **Pattern Printing**
    ```
    *
    **
    ***
    ****
    *****
    ```
    Print this pattern using a `for` loop.

### Hard Level

11. **Armstrong Number**
    - Check if a number is an Armstrong number (sum of cubes of digits equals the number).
    - Input: 153
    - Output: Yes (1³ + 5³ + 3³ = 153)

12. **GCD Calculator**
    - Find the GCD of two numbers using a `while` loop (Euclidean algorithm).

13. **Perfect Number**
    - Check if a number is perfect (sum of divisors equals the number).
    - Input: 28
    - Output: Yes (1+2+4+7+14 = 28)

14. **Number Guessing Game**
    - Create a number guessing game using a `do-while` loop where the user has to guess a number between 1-100.

15. **LCM Calculator**
    - Find the LCM of two numbers using loops.

---

## Part B: Referencing and Pointers

### Easy Level

16. **Basic Pointer Declaration**
    - Declare an integer variable, a pointer to it, and print both the value and address.
    ```c
    int num = 10;
    int *ptr = &num;
    // Print value and address
    ```

17. **Swap Using Pointers**
    - Write a program to swap two numbers using pointers and the dereference operator.

18. **Pointer Arithmetic**
    - Demonstrate incrementing a pointer and printing values.

19. **Value vs Address**
    - Create a program that shows the difference between printing `ptr`, `*ptr`, and `&ptr`.

20. **Null Pointer**
    - Demonstrate the use of NULL pointer and check if a pointer is NULL before dereferencing.

### Medium Level

21. **Pointer to Pointer**
    - Create a pointer to pointer and access the value through double dereferencing.
    ```c
    int num = 25;
    int *ptr = &num;
    int **pptr = &ptr;
    ```

22. **Array and Pointer Relationship**
    - Show that array name is a pointer to the first element.
    - Access array elements using pointer notation.

23. **Modify Value Through Pointer**
    - Write a function that takes a pointer and modifies the original variable's value.

24. **Compare Addresses**
    - Create multiple variables and compare their memory addresses using pointers.

25. **Pointer Size**
    - Print the size of different pointer types (int*, char*, float*, double*) and observe.

### Hard Level

26. **Dynamic Memory Concept**
    - Explain (in comments) why pointers are needed for dynamic memory allocation.

27. **Pointer Array Traversal**
    - Use a pointer to traverse an array without using array indexing.

28. **Const Pointers**
    - Demonstrate the difference between:
      - `const int *ptr` (pointer to constant)
      - `int *const ptr` (constant pointer)
      - `const int *const ptr` (constant pointer to constant)

29. **Function Pointer Introduction**
    - Declare a pointer to a function and call the function through the pointer.

30. **Pointer Comparison**
    - Compare two pointers pointing to different array elements and determine their relative positions.

---

## Bonus Challenge Questions

31. **Loop Conversion**
    - Write the same program (print 1 to 10) using `for`, `while`, and `do-while` loops.

32. **Nested Loop Pattern**
    ```
    1
    2 3
    4 5 6
    7 8 9 10
    ```
    Print this number pattern.

33. **Pointer Chain**
    - Create a chain of 3 pointers where each points to the next, ultimately pointing to an integer value.

34. **Menu-Driven Calculator**
    - Create a calculator using a `do-while` loop with options to add, subtract, multiply, divide, or exit.

35. **Collatz Conjecture**
    - Implement the Collatz conjecture sequence using a `while` loop.
    - If n is even: n = n/2
    - If n is odd: n = 3n+1
    - Continue until n becomes 1

---

## Tips for Practice:
- Always initialize pointers before using them
- Check for NULL pointers before dereferencing
- Use meaningful variable names
- Add comments to explain pointer operations
- Practice drawing memory diagrams for pointer problems
- Understand the difference between `&` (address-of) and `*` (dereference) operators
