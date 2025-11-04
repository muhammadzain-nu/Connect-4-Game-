# C Programming Practice Guide
## Weeks 7-10: Comprehensive Practice Questions

---

## 📚 Overview

This practice guide contains **105+ carefully curated questions** covering fundamental C programming concepts from Weeks 7-10. Each week builds upon the previous, creating a solid foundation in C programming.

---

## 📋 Table of Contents

### Week 7: Loops and Pointers Basics
- **File:** `Week7_Practice_Questions.md`
- **Topics:**
  - Basic loops: `for`, `while`, `do-while`
  - Referencing and dereferencing
  - Introduction to pointers
- **Questions:** 35 problems (Easy, Medium, Hard)

### Week 8: Loops with 1D Arrays
- **File:** `Week8_Practice_Questions.md`
- **Topics:**
  - 1D array operations
  - Array manipulation with loops
  - Arrays with pointers
- **Questions:** 45 problems (Easy, Medium, Hard)

### Week 9: Nested Loops and Multi-Dimensional Arrays
- **File:** `Week9_Practice_Questions.md`
- **Topics:**
  - 2D arrays (matrices)
  - 3D, 4D, 5D arrays
  - Pattern printing with nested loops
- **Questions:** 75 problems (Easy, Medium, Hard)

### Week 10: Functions and Advanced Pointers
- **File:** `Week10_Practice_Questions.md`
- **Topics:**
  - Function declaration, definition, and calling
  - Pass by value vs pass by reference
  - Passing arrays to functions
  - Recursive functions
  - Function pointers
- **Questions:** 105 problems (Easy, Medium, Hard)

---

## 🎯 How to Use This Guide

### 1. **Progressive Learning**
   - Start with Week 7 and progress sequentially
   - Don't skip weeks - each builds on previous concepts
   - Master easy problems before moving to medium/hard

### 2. **Difficulty Levels**
   - **Easy:** Fundamental concepts, direct application
   - **Medium:** Requires combining multiple concepts
   - **Hard:** Complex logic, optimization, edge cases

### 3. **Practice Strategy**
   ```
   Day 1-2: Easy problems (build confidence)
   Day 3-4: Medium problems (develop skills)
   Day 5-6: Hard problems (challenge yourself)
   Day 7: Review and bonus challenges
   ```

### 4. **Coding Best Practices**
   - Write clean, readable code
   - Add meaningful comments
   - Test with multiple inputs
   - Handle edge cases
   - Use proper variable names

---

## 💡 Study Tips

### For Loops (Week 7)
- Draw flowcharts before coding
- Understand loop initialization, condition, and increment
- Practice converting between `for`, `while`, and `do-while`
- Trace loop execution with small values

### For Pointers (Week 7)
- Draw memory diagrams
- Understand the difference between `&` and `*`
- Practice pointer arithmetic
- Always initialize pointers before use

### For Arrays (Week 8-9)
- Visualize array memory layout
- Remember: array name is a pointer to first element
- Practice both index-based and pointer-based access
- Always check array bounds

### For Functions (Week 10)
- Understand function signature (return type, parameters)
- Know when to use pass by value vs reference
- Practice writing function prototypes
- Test functions independently

---

## 🔍 Common Mistakes to Avoid

1. **Uninitialized Variables**
   ```c
   int x;  // Uninitialized - contains garbage
   printf("%d", x);  // ❌ Wrong
   
   int x = 0;  // ✅ Correct
   ```

2. **Array Index Out of Bounds**
   ```c
   int arr[5];
   arr[5] = 10;  // ❌ Wrong (valid indices: 0-4)
   arr[4] = 10;  // ✅ Correct
   ```

3. **Uninitialized Pointers**
   ```c
   int *ptr;
   *ptr = 10;  // ❌ Wrong (dangling pointer)
   
   int x;
   int *ptr = &x;
   *ptr = 10;  // ✅ Correct
   ```

4. **Forgetting to Pass Array Size**
   ```c
   void func(int arr[]) {
       // How many elements? ❌
   }
   
   void func(int arr[], int size) {
       // Now we know! ✅
   }
   ```

5. **Modifying Array in Pass by Value**
   ```c
   void swap(int a, int b) {
       int temp = a;
       a = b;
       b = temp;  // ❌ Doesn't affect original
   }
   
   void swap(int *a, int *b) {
       int temp = *a;
       *a = *b;
       *b = temp;  // ✅ Modifies original
   }
   ```

---

## 📊 Progress Tracking

Create a checklist to track your progress:

```
Week 7: Loops and Pointers
[ ] Easy Problems (1-20)
[ ] Medium Problems (21-30)
[ ] Hard Problems (31-35)

Week 8: 1D Arrays
[ ] Easy Problems (1-20)
[ ] Medium Problems (21-35)
[ ] Hard Problems (36-45)

Week 9: Multi-Dimensional Arrays
[ ] Easy Problems (1-25)
[ ] Medium Problems (26-50)
[ ] Hard Problems (51-75)

Week 10: Functions
[ ] Easy Problems (1-30)
[ ] Medium Problems (31-70)
[ ] Hard Problems (71-105)
```

---

## 🚀 Challenge Yourself

After completing all weeks:

1. **Time Yourself**
   - Solve problems under time constraints
   - Aim for: Easy (10 min), Medium (20 min), Hard (30 min)

2. **Code Review**
   - Review your old solutions
   - Optimize for better time/space complexity
   - Refactor for better readability

3. **Teach Others**
   - Explain solutions to peers
   - Write comments as if teaching
   - Create your own variations

4. **Build Projects**
   - Combine concepts to build small projects
   - Examples: Calculator, Tic-Tac-Toe, Matrix Calculator
   - Student Management System, Simple Database

---

## 📝 Sample Problem Walkthrough

### Problem: Swap two numbers using pointers

**Step 1: Understand the Problem**
- Need to swap values of two variables
- Must use pointers (pass by reference)

**Step 2: Plan the Solution**
```
1. Create a swap function that takes two pointers
2. Use a temporary variable
3. Dereference pointers to swap values
```

**Step 3: Write the Code**
```c
#include <stdio.h>

void swap(int *a, int *b) {
    int temp = *a;  // Store value at address a
    *a = *b;        // Copy value from b to a
    *b = temp;      // Copy temp to b
}

int main() {
    int x = 10, y = 20;
    
    printf("Before swap: x = %d, y = %d\n", x, y);
    swap(&x, &y);  // Pass addresses
    printf("After swap: x = %d, y = %d\n", x, y);
    
    return 0;
}
```

**Step 4: Test**
```
Input: x = 10, y = 20
Output: x = 20, y = 10 ✅
```

---

## 🛠️ Compilation and Testing

### Compile Your Code
```bash
gcc filename.c -o output
./output
```

### With Warnings (Recommended)
```bash
gcc -Wall -Wextra filename.c -o output
./output
```

### Debug Mode
```bash
gcc -g filename.c -o output
gdb ./output
```

---

## 📚 Additional Resources

### Online Compilers
- [OnlineGDB](https://www.onlinegdb.com/online_c_compiler)
- [Programiz C Compiler](https://www.programiz.com/c-programming/online-compiler/)
- [Replit](https://replit.com/)

### Practice Platforms
- HackerRank (C Programming)
- LeetCode (Easy problems)
- CodeChef (Beginner section)
- Codeforces (Div 3/4 problems)

### Reference Materials
- C Programming Documentation
- GeeksforGeeks C Tutorials
- TutorialsPoint C Programming

---

## 🎓 Learning Outcomes

By completing this practice guide, you will:

✅ Master loop constructs and their applications
✅ Understand pointers and memory management
✅ Work confidently with arrays (1D, 2D, 3D+)
✅ Write modular code using functions
✅ Implement pass by value and pass by reference
✅ Solve complex problems using nested loops
✅ Debug and optimize C programs
✅ Build a strong foundation for advanced C programming

---

## 📞 Need Help?

If you're stuck on a problem:

1. **Read the problem again** - Make sure you understand what's being asked
2. **Break it down** - Divide into smaller sub-problems
3. **Draw diagrams** - Visualize arrays, pointers, memory
4. **Trace execution** - Walk through your code line by line
5. **Test with simple inputs** - Start with small, easy cases
6. **Check edge cases** - Empty arrays, negative numbers, zero
7. **Review concepts** - Go back to theory if needed

---

## 🎯 Final Tips

1. **Consistency is Key** - Practice daily, even if just 30 minutes
2. **Quality over Quantity** - Understand deeply rather than solving many superficially
3. **Make Mistakes** - Errors are learning opportunities
4. **Write Clean Code** - Good habits form early
5. **Stay Curious** - Ask "why" and "what if"
6. **Have Fun** - Programming is creative and rewarding!

---

**Good luck with your practice! Happy Coding! 🚀**

---

*Last Updated: November 4, 2025*
