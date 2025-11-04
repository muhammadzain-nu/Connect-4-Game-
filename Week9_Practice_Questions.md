# Week 9 Practice Questions
## Topics: Nested Loops with N-D Arrays (2D, 3D, 4D, 5D Arrays)

---

## Part A: 2D Arrays (Matrices)

### Easy Level

1. **Matrix Input and Output**
   - Write a program to input a 3×3 matrix and print it in matrix format.

2. **Sum of All Elements**
   - Calculate the sum of all elements in a 2D array.
   - Input: 
     ```
     1 2 3
     4 5 6
     7 8 9
     ```
   - Output: Sum = 45

3. **Row-wise Sum**
   - Calculate and print the sum of each row in a matrix.

4. **Column-wise Sum**
   - Calculate and print the sum of each column in a matrix.

5. **Diagonal Sum (Primary)**
   - Calculate the sum of the primary diagonal (top-left to bottom-right).
   - Input: 
     ```
     1 2 3
     4 5 6
     7 8 9
     ```
   - Output: Diagonal Sum = 15 (1+5+9)

### Medium Level

6. **Matrix Addition**
   - Add two matrices of the same size and store the result in a third matrix.

7. **Matrix Subtraction**
   - Subtract one matrix from another.

8. **Matrix Transpose**
   - Find the transpose of a matrix (swap rows and columns).
   - Input:
     ```
     1 2 3
     4 5 6
     ```
   - Output:
     ```
     1 4
     2 5
     3 6
     ```

9. **Search in 2D Array**
   - Search for an element in a 2D array and print its position (row, column).

10. **Find Maximum in Matrix**
    - Find the largest element in a 2D array and its position.

### Hard Level

11. **Matrix Multiplication**
    - Multiply two matrices (ensure dimensions are compatible).
    - For 2×3 and 3×2 matrices, result will be 2×2.

12. **Spiral Matrix Traversal**
    - Print a matrix in spiral order (clockwise from outside to inside).
    - Input:
      ```
      1  2  3  4
      5  6  7  8
      9  10 11 12
      ```
    - Output: 1 2 3 4 8 12 11 10 9 5 6 7

13. **Rotate Matrix 90° Clockwise**
    - Rotate a square matrix by 90 degrees clockwise.

14. **Saddle Point**
    - Find saddle point(s) in a matrix (minimum in row, maximum in column).

15. **Boundary Elements Sum**
    - Calculate the sum of all boundary elements of a matrix.

---

## Part B: Advanced 2D Array Problems

### Easy Level

16. **Identity Matrix Check**
    - Check if a given matrix is an identity matrix.

17. **Symmetric Matrix Check**
    - Check if a matrix is symmetric (A = A^T).

18. **Upper Triangular Matrix**
    - Print only the upper triangular part of a matrix.

19. **Lower Triangular Matrix**
    - Print only the lower triangular part of a matrix.

20. **Secondary Diagonal Sum**
    - Calculate the sum of the secondary diagonal (top-right to bottom-left).

### Medium Level

21. **Sparse Matrix Check**
    - Check if a matrix is sparse (more than half elements are zero).

22. **Row with Maximum Sum**
    - Find which row has the maximum sum.

23. **Column with Minimum Sum**
    - Find which column has the minimum sum.

24. **Exchange Rows**
    - Swap two specified rows in a matrix.

25. **Exchange Columns**
    - Swap two specified columns in a matrix.

### Hard Level

26. **Magic Square Check**
    - Check if a matrix is a magic square (all rows, columns, and diagonals have same sum).

27. **Wave Print**
    - Print matrix in wave form (column-wise alternating up and down).
    - Input:
      ```
      1 2 3
      4 5 6
      7 8 9
      ```
    - Output: 1 4 7 8 5 2 3 6 9

28. **Set Matrix Zeros**
    - If an element is 0, set its entire row and column to 0.

29. **Search in Row-Column Sorted Matrix**
    - Search in a matrix where each row and column is sorted.

30. **Largest Rectangle of 1s**
    - Find the largest rectangle containing only 1s in a binary matrix.

---

## Part C: 3D Arrays

### Easy Level

31. **3D Array Input and Output**
    - Input and display a 3D array (e.g., 2×3×4).
    - Think of it as 2 matrices, each of size 3×4.

32. **Sum of All Elements in 3D Array**
    - Calculate the sum of all elements in a 3D array.

33. **Find Maximum in 3D Array**
    - Find the largest element in a 3D array.

34. **Count Positive Numbers**
    - Count how many positive numbers exist in a 3D array.

35. **Initialize 3D Array**
    - Initialize a 3D array with sequential numbers (1, 2, 3, ...).

### Medium Level

36. **Sum of Each 2D Slice**
    - For a 3D array, calculate the sum of each 2D slice.
    - If array is [2][3][4], calculate sum of each 3×4 matrix.

37. **Search in 3D Array**
    - Search for an element and print its 3D coordinates (i, j, k).

38. **Copy 3D Array**
    - Copy one 3D array to another.

39. **Average of Each Layer**
    - Calculate the average of elements in each layer (2D slice) of a 3D array.

40. **Transpose Each 2D Slice**
    - Transpose each 2D matrix within a 3D array.

### Hard Level

41. **3D Matrix Addition**
    - Add two 3D arrays element by element.

42. **Find Minimum in Each Plane**
    - Find the minimum element in each 2D plane of a 3D array.

43. **3D Diagonal Sum**
    - Calculate the sum of the main 3D diagonal (where i=j=k).

44. **Flatten 3D to 1D**
    - Convert a 3D array into a 1D array.

45. **Reshape 1D to 3D**
    - Convert a 1D array into a 3D array of given dimensions.

---

## Part D: 4D and 5D Arrays (Advanced Concepts)

### 4D Array Problems

46. **4D Array Declaration and Initialization**
    - Declare and initialize a 4D array (e.g., 2×2×3×4).
    - Print all elements using 4 nested loops.

47. **Sum of 4D Array**
    - Calculate the sum of all elements in a 4D array.

48. **Find Maximum in 4D Array**
    - Find the largest element and its 4D coordinates.

49. **Count Negative Numbers**
    - Count how many negative numbers exist in a 4D array.

50. **Average of 4D Array**
    - Calculate the average of all elements in a 4D array.

### 5D Array Problems

51. **5D Array Declaration**
    - Declare and initialize a 5D array (e.g., 2×2×2×3×3).
    - Print all elements using 5 nested loops.

52. **Sum of 5D Array**
    - Calculate the sum of all elements in a 5D array.

53. **Search in 5D Array**
    - Search for an element and print its 5D coordinates.

54. **Count Even Numbers in 5D Array**
    - Count how many even numbers exist in a 5D array.

55. **Memory Size Calculation**
    - Calculate and print the total memory occupied by a 5D array.

---

## Part E: Pattern Printing with Nested Loops

### Easy Patterns

56. **Rectangle Pattern**
    ```
    * * * * *
    * * * * *
    * * * * *
    * * * * *
    ```

57. **Right Triangle**
    ```
    *
    * *
    * * *
    * * * *
    * * * * *
    ```

58. **Inverted Right Triangle**
    ```
    * * * * *
    * * * *
    * * *
    * *
    *
    ```

59. **Number Triangle**
    ```
    1
    1 2
    1 2 3
    1 2 3 4
    1 2 3 4 5
    ```

60. **Square Number Pattern**
    ```
    1 2 3 4 5
    1 2 3 4 5
    1 2 3 4 5
    1 2 3 4 5
    1 2 3 4 5
    ```

### Medium Patterns

61. **Pyramid Pattern**
    ```
        *
       * *
      * * *
     * * * *
    * * * * *
    ```

62. **Diamond Pattern**
    ```
        *
       * *
      * * *
     * * * *
    * * * * *
     * * * *
      * * *
       * *
        *
    ```

63. **Floyd's Triangle**
    ```
    1
    2 3
    4 5 6
    7 8 9 10
    11 12 13 14 15
    ```

64. **Pascal's Triangle**
    ```
    1
    1 1
    1 2 1
    1 3 3 1
    1 4 6 4 1
    ```

65. **Hollow Rectangle**
    ```
    * * * * *
    *       *
    *       *
    * * * * *
    ```

### Hard Patterns

66. **Butterfly Pattern**
    ```
    *        *
    **      **
    ***    ***
    ****  ****
    **********
    ****  ****
    ***    ***
    **      **
    *        *
    ```

67. **Hourglass Pattern**
    ```
    * * * * *
     * * * *
      * * *
       * *
        *
       * *
      * * *
     * * * *
    * * * * *
    ```

68. **Zigzag Pattern**
    ```
      *   *
     * * * *
    *   *   *
    ```

69. **Spiral Number Pattern**
    ```
    1  2  3  4  5
    16 17 18 19 6
    15 24 25 20 7
    14 23 22 21 8
    13 12 11 10 9
    ```

70. **Alphabet Diamond**
    ```
        A
       ABA
      ABCBA
     ABCDCBA
    ABCDEDCBA
     ABCDCBA
      ABCBA
       ABA
        A
    ```

---

## Bonus Challenge Questions

71. **Tic-Tac-Toe Board**
    - Create a 3×3 tic-tac-toe board and check for winner.

72. **Sudoku Validator**
    - Validate if a 9×9 Sudoku board is valid.

73. **Conway's Game of Life**
    - Implement one generation of Conway's Game of Life on a 2D grid.

74. **Matrix Determinant**
    - Calculate the determinant of a 3×3 matrix.

75. **Image Rotation Simulation**
    - Simulate rotating a 2D image array by 180 degrees.

---

## Tips for Practice:
- Always use proper indentation for nested loops
- Draw the loop structure before coding complex patterns
- For N-D arrays: outer loop → inner loop → innermost loop
- Use meaningful loop variable names (i, j, k, l, m for dimensions)
- Test with small array sizes first (2×2, 2×3) before scaling up
- Visualize 3D+ arrays as collections of lower-dimensional arrays
- Remember: 3D array[x][y][z] means x matrices of size y×z
- For 4D and 5D arrays, think in terms of nested structures
- Practice drawing memory layout diagrams
- Use proper boundary checks to avoid segmentation faults
