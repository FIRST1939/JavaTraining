## Section 1: Java Basics

### Objectives
- Understand Java syntax and program structure.
- Learn how to work with variables, data types, and operators.
- Implement basic control structures such as if-else statements and loops.
- Create and use methods (functions).
- Compile and run Java programs from the command line.

### 1.1: Introduction to Java (30 Minutes)
- **Topics:** Java syntax, structure, and the `main` method.
- **Resources:**
  - [Introduction - W3Schools](https://www.w3schools.com/java/java_intro.asp)
  - [Getting Started - W3Schools](https://www.w3schools.com/java/java_getstarted.asp)
  - [Syntax - W3Schools](https://www.w3schools.com/java/java_syntax.asp)
  - [Comments - W3Schools](https://www.w3schools.com/java/java_comments.asp)
- **Activity:** Write a simple "Hello, World!" program to get familiar with the syntax and structure.

### 1.2: Variables and Data Types (45 Minutes)
- **Topics:** Variables and primitive data types, such as `int`, `double`, `char`, and `boolean`.
- **Resources:**
  - [Variables - W3Schools](https://www.w3schools.com/java/java_variables.asp) (Explore Entire Section)
  - [Data Types - W3Schools](https://www.w3schools.com/java/java_data_types.asp) (Explore Entire Section)
  - [Strings - W3Schools](https://www.w3schools.com/java/java_strings.asp) (Explore Entire Section)
- **Activity:** Create variables to store different kinds of sensor data and display the values.

### 1.3: Operators (45 Minutes)
- **Topics:** Arithmetic, assignment, comparison, and logical operators.
- **Resources:**
  - [Operators - W3Schools](https://www.w3schools.com/java/java_operators.asp)
  - [Math - W3Schools](https://www.w3schools.com/java/java_math.asp)
  - [Booleans - W3Schools](https://www.w3schools.com/java/java_booleans.asp)
- **Activity:** Write a program to calculate a robot's speed based on the distance traveled and time taken, then determine whether the robot is moving faster than 3.5 m/s.

### 1.4: Control Structures - If Statements (45 Minutes)
- **Topics:** `if`, `else`, and `else if` statements.
- **Resources:**
    - [If ... Else - W3Schools](https://www.w3schools.com/java/java_conditions.asp) (Explore Entire Section)
- **Activity:** Write a program that prints different messages based on the robot's battery level. For example, if the battery is between 0-50%, print "Low Battery", if it's between 51-80%, print "Medium Battery", and if it's above 80%, print "Full Battery".

### 1.5: Control Structures - Loops (60 Minutes)
- **Topics:** `for` and `while` loops.
-  **Resources:**
   -  [For Loop - W3Schools](https://www.w3schools.com/java/java_for_loop.asp) (Explore Entire Section)
   -  [While Loop - W3Schools](https://www.w3schools.com/java/java_while_loop.asp) (Also Explore Real-Life Examples)
   -  [Break and Continue - W3Schools](https://www.w3schools.com/java/java_break.asp)
- **Activity:** Write a countdown timer that simulates the start of a match and allow the user to abort the countdown by specifying when to abort as a variable.

### 1.6: Methods (Functions) (60 Minutes)
- **Topics:** Defining and calling methods, method parameters, and return values.
- **Resources:**
  -  [Methods - W3Schools](https://www.w3schools.com/java/java_methods.asp)
  -  [Method Parameters - W3Schools](https://www.w3schools.com/java/java_methods_parameters.asp) (Explore Entire Section)
  -  [Method Overloading - W3Schools](https://www.w3schools.com/java/java_methods_overloading.asp)
  -  [Scope - W3Schools](https://www.w3schools.com/java/java_scope.asp)
- **Activity:** Write a method that calculates the distance the robot must travel based on its current (x,y) coordinates and a target location. Use parameters to pass in the target coordinates and return the distance.

### 1.7: Brining It All Together (90 Minutes)
- **Activity:** Create a simple robot simulation that...
  - Tracks the robot's battery level and current position.
  - Uses methods to move the robot specified x and y distances, and drains the battery proportional to the distance traveled.
  - Checks the battery level before moving and prints appropriate messages depending on the battery level.