### **Lesson #5: The Power of Constants**

---

#### **Objective:**
To introduce students to the concept of constants in C++, explaining why and when they are used.

---

#### **Duration:**
30 minutes

---

#### **Activity Breakdown:**

---

1. **Review of Last Lesson (3 minutes)**
   - Quick recap of variables: “Remember our labeled boxes? They can hold different values, and we can change those values. But what if we had a special box that, once we put something inside, we can never change it?”

---

2. **Introduction to Constants (5 minutes)**
   - Definition: “A constant is like a variable in many ways, but once you give it a value, you can’t change it later. It remains the same.”
   - Whiteboard Examples:
     ```cpp
     const int numberOfPlanets = 8;
     const char schoolGrade = 'A';
     const double pi = 3.14159265;
     ```
   - Highlight: 
     - `const` is a keyword that makes the variable unchangeable.
     - Importance: Constants are used when you have a value that shouldn't be changed by mistake in the program, like the value of pi.

---

3. **Constants vs Variables (7 minutes)**
   - Set up two columns on the whiteboard, one labeled "Variables" and the other "Constants."
   - Live demonstration: Show changing the value of a variable and the error that results when trying to change a constant.
     ```cpp
     int age = 10;
     age = 12; // This is okay

     const int birthYear = 2010;
     birthYear = 2008; // This will cause an error
     ```
   - Emphasize that the error is because we can't change constants after they are set.

---

4. **Interactive Activity: Constant Detective (7 minutes)**
   - Prepare handouts with a mix of variable and constant declarations and assignments. Some of these should contain errors related to constants.
   - Students circle any errors they find.
   - Discuss the answers together, asking students to explain why certain lines are incorrect.

---

5. **Explaining Use Cases (5 minutes)**
   - Discuss scenarios in which constants are beneficial:
     - Mathematical values: `pi`, `gravity`.
     - Configuration values: `maxPlayersInGame`.
     - Conversion values: `inchesInFoot`.
   - Ask students: "Why do you think we wouldn't want these values to change?"

---

6. **Group Activity: Build a Constants List (2 minutes)**
   - Divide students into small groups. Each group comes up with a list of things they believe should be represented as constants in a program. For example, in a game setting, `maxLives` could be a constant.

---

7. **Wrap-Up and Homework Assignment (1 minute)**
   - Summarize: “Today, we learned about constants, which are values that never change in our program. They help us keep some parts of our code safe from accidental changes.”
   - Homework: 
     - "Remember the story you created for the last lesson? Now, identify any detail in the story that should be constant, like `numberOfEyesInHumans`. Write them as constants in C++."

---

By the end of this lesson, students should understand the fundamental difference between variables and constants and recognize the importance of constants in specific scenarios.
