# Week 8 Practice Questions
## Topics: Loops with 1D Arrays

---

## Part A: Basic 1D Array Operations

### Easy Level

1. **Array Input and Output**
   - Write a program to input N integers into an array and print them.
   - Use a `for` loop for both input and output.

2. **Sum of Array Elements**
   - Calculate the sum of all elements in an array.
   - Input: [5, 10, 15, 20, 25]
   - Output: Sum = 75

3. **Find Maximum Element**
   - Find and print the largest element in an array.
   - Input: [12, 45, 23, 67, 34]
   - Output: Maximum = 67

4. **Find Minimum Element**
   - Find and print the smallest element in an array.

5. **Count Even and Odd**
   - Count how many even and odd numbers are present in an array.
   - Input: [1, 2, 3, 4, 5, 6]
   - Output: Even = 3, Odd = 3

### Medium Level

6. **Reverse an Array**
   - Reverse the elements of an array in-place.
   - Input: [1, 2, 3, 4, 5]
   - Output: [5, 4, 3, 2, 1]

7. **Search Element (Linear Search)**
   - Search for an element in an array and print its position.
   - If not found, print "Element not found".

8. **Copy Array**
   - Copy all elements from one array to another using a loop.

9. **Count Occurrences**
   - Count how many times a specific element appears in an array.
   - Input: [1, 2, 3, 2, 4, 2, 5], Search: 2
   - Output: 2 appears 3 times

10. **Average of Array**
    - Calculate and print the average of all elements in an array.

### Hard Level

11. **Second Largest Element**
    - Find the second largest element in an array without sorting.
    - Input: [12, 35, 1, 10, 34, 1]
    - Output: Second Largest = 34

12. **Remove Duplicates**
    - Remove duplicate elements from an array and print the unique elements.
    - Input: [1, 2, 2, 3, 4, 4, 5]
    - Output: [1, 2, 3, 4, 5]

13. **Rotate Array**
    - Rotate an array to the right by K positions.
    - Input: [1, 2, 3, 4, 5], K = 2
    - Output: [4, 5, 1, 2, 3]

14. **Merge Two Arrays**
    - Merge two sorted arrays into a third array (not necessarily sorted).

15. **Frequency of Each Element**
    - Print the frequency of each unique element in an array.
    - Input: [1, 2, 2, 3, 3, 3, 4]
    - Output: 1→1 time, 2→2 times, 3→3 times, 4→1 time

---

## Part B: Array Manipulation with Loops

### Easy Level

16. **Initialize Array**
    - Initialize an array with values 1 to N using a loop.

17. **Print Array in Reverse**
    - Print array elements in reverse order (without modifying the array).

18. **Check if Array is Sorted**
    - Check if an array is sorted in ascending order.

19. **Sum of Even Indexed Elements**
    - Calculate sum of elements at even indices (0, 2, 4, ...).

20. **Multiply Each Element**
    - Multiply each element of an array by a given number.

### Medium Level

21. **Left Rotate by One**
    - Rotate array elements to the left by one position.
    - Input: [1, 2, 3, 4, 5]
    - Output: [2, 3, 4, 5, 1]

22. **Separate Even and Odd**
    - Separate even and odd numbers into two different arrays.

23. **Find Missing Number**
    - Given an array of N-1 integers from 1 to N with one missing, find the missing number.
    - Input: [1, 2, 4, 5, 6] (N=6)
    - Output: Missing = 3

24. **Palindrome Array**
    - Check if an array is a palindrome (reads same forwards and backwards).
    - Input: [1, 2, 3, 2, 1]
    - Output: Yes, it's a palindrome

25. **Insert Element at Position**
    - Insert an element at a specific position in an array and shift other elements.

### Hard Level

26. **Leaders in Array**
    - Find all leaders in an array. An element is a leader if it's greater than all elements to its right.
    - Input: [16, 17, 4, 3, 5, 2]
    - Output: Leaders = [17, 5, 2]

27. **Maximum Difference**
    - Find maximum difference between two elements where larger element appears after smaller.
    - Input: [2, 3, 10, 6, 4, 8, 1]
    - Output: Max Difference = 8 (10-2)

28. **Rearrange Positive and Negative**
    - Rearrange array so that positive and negative numbers appear alternately.

29. **Find Pair with Given Sum**
    - Find if there exists a pair of elements whose sum equals a given value.
    - Input: [1, 4, 45, 6, 10, -8], Sum = 16
    - Output: Pair found: (6, 10)

30. **Stock Buy-Sell Problem**
    - Find the maximum profit from buying and selling stock once.
    - Input: [7, 1, 5, 3, 6, 4]
    - Output: Max Profit = 5 (buy at 1, sell at 6)

---

## Part C: Array with Pointers

### Easy Level

31. **Access Array Using Pointer**
    - Access and print array elements using pointer notation.
    ```c
    int arr[5] = {1, 2, 3, 4, 5};
    int *ptr = arr;
    // Print using *(ptr+i)
    ```

32. **Sum Using Pointer**
    - Calculate sum of array elements using pointer arithmetic.

33. **Pointer Increment**
    - Demonstrate pointer increment through an array.

34. **Array Address**
    - Print the address of each array element using pointers.

35. **Modify Array Using Pointer**
    - Modify array elements using pointer dereferencing.

### Medium Level

36. **Reverse Using Pointers**
    - Reverse an array using two pointers (one at start, one at end).

37. **Find Max Using Pointer**
    - Find maximum element using pointer traversal.

38. **Compare Two Arrays**
    - Compare two arrays element by element using pointers.

39. **Copy Array Using Pointers**
    - Copy one array to another using only pointer operations.

40. **Count Positive Numbers**
    - Count positive numbers in an array using pointer traversal.

---

## Bonus Challenge Questions

41. **Wave Array**
    - Rearrange array in wave form: arr[0] >= arr[1] <= arr[2] >= arr[3] <= arr[4]...

42. **Majority Element**
    - Find the element that appears more than N/2 times in an array.

43. **Trapping Rain Water**
    - Calculate how much water can be trapped between bars.
    - Input: [0, 1, 0, 2, 1, 0, 1, 3, 2, 1, 2, 1]
    - Output: 6 units

44. **Kadane's Algorithm**
    - Find the maximum sum of a contiguous subarray.
    - Input: [-2, 1, -3, 4, -1, 2, 1, -5, 4]
    - Output: Maximum Sum = 6 (subarray: [4, -1, 2, 1])

45. **Dutch National Flag Problem**
    - Sort an array of 0s, 1s, and 2s without using sorting algorithms.
    - Input: [0, 1, 2, 0, 1, 2, 1, 0]
    - Output: [0, 0, 0, 1, 1, 1, 2, 2]

---

## Tips for Practice:
- Always check array bounds to avoid out-of-bounds access
- Initialize arrays properly before use
- Use meaningful array sizes (avoid magic numbers)
- Practice both index-based and pointer-based array access
- Draw diagrams to visualize array operations
- Test with edge cases: empty arrays, single element, all same elements
- Remember: array name is a constant pointer to the first element
