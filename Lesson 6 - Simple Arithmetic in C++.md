### **Lesson #6: Simple Arithmetic in C++**

---

#### **Objective:**
To introduce students to basic arithmetic operations in C++ and demonstrate how to perform calculations using variables and constants.

---

#### **Duration:**
30 minutes

---

#### **Activity Breakdown:**

---

1. **Introduction with Real-World Analogy (3 minutes)**
   - Begin with a relatable scenario: “Imagine you have 5 candies. You give 2 to your friend. How many do you have left?” (Expect answers.)
   - Transition: “In C++, we can do these kinds of calculations using arithmetic operations.”

---

2. **Explaining Basic Arithmetic Operators (6 minutes)**
   - Write down and explain each operator on the whiteboard:
     - `+` Addition
     - `-` Subtraction
     - `*` Multiplication
     - `/` Division
     - `%` Modulus (remainder of a division)
   - Demonstrate using basic examples:
     ```cpp
     int candies = 5;
     candies = candies - 2; // This equals 3
     ```

---

3. **Demonstrating Calculations (7 minutes)**
   - Live demonstration on the computer, typing out various calculations, including using variables and constants.
   - Show the difference between division results with `int` and `double` (to touch on the concept of type again and integer division).
     ```cpp
     int a = 10;
     int b = 3;
     int result = a / b;  // This will be 3

     double x = 10.0;
     double y = 3.0;
     double fraction = x / y;  // This will be approximately 3.33
     ```

---

4. **Interactive Activity: Math Quizzes (6 minutes)**
   - Hand out printed sheets with math problems written in plain English. For example: 
     - "You have 8 apples. You eat 3. How many are left?"
     - "There are 6 boxes, each with 4 toys. How many toys are there in total?"
   - Ask students to translate these into C++ code and find the answer.

---

5. **Discussing the Modulus Operator (4 minutes)**
   - Highlight the `%` operator and explain with examples:
     ```cpp
     int remainder = 11 % 4;  // This equals 3
     ```
   - Relate to real-world scenarios: "If you have 11 candies and want to share them equally among 4 friends, 3 candies will remain after giving an equal share to each."

---

6. **Group Exercise: Modulus Puzzles (2 minutes)**
   - Provide small groups with problems that involve finding remainders. For example, "14 students want to form teams of 5 for a game. How many students won't be in a full team?"
   - Have groups share their answers and C++ code.

---

7. **Wrap-Up and Homework Assignment (2 minutes)**
   - Summarize: “Today, we explored how to do math in C++ using various operators. We can add, subtract, multiply, divide, and even find remainders!”
   - Homework:
     - "Think of a fun activity or scenario, like baking cookies or planning a party. Write down at least five arithmetic problems related to your activity, translate them to C++, and solve them. For instance, 'If one batch of cookies needs 3 cups of flour and you want to make 4 batches, how much flour do you need in total?'"

---

With the end of this lesson, students should feel comfortable performing basic arithmetic operations in C++ and understand the significance of the modulus operator.
