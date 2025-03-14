# Java Beginner Challenges
### Note: Only challenges 1 - 8 and 10 are valid for worth doing at the moment. The others might be invalid for Java.

## How to Fork This Repository
If you are new to Git and GitHub, follow these simple steps to get started:

1. Go to the GitHub page of this repository.
2. Click the `Fork` button in the top right corner. This will create a copy of the repository under your own GitHub account.
3. Clone the repository to your local machine:
   ```sh
   git clone https://github.com/YOUR_USERNAME/REPO_NAME.git
   ```
4. Navigate into the project folder:
   ```sh
   cd REPO_NAME
   ```
5. Open the project in your favorite code editor and start working on the challenges!

---
## 1. Variables and Console Output
- Declare three variables: one for your name (String), one for your age (int), and one for your favorite color (String).  
- Assign appropriate values to them.  
- Print all values to the console.  

---

## 2. Variable Declarations, Assignments, and Type Conversion
- Declare and assign values to variables of different data types:  
  - `int` for age  
  - `double` for height  
  - `char` for the first letter of your name  
  - `boolean` for whether you like Java  
  - `String` for your favorite programming language  

---

## 3. If Statements

### 3.1. Grade Evaluator
- Declare an `int` variable for a score between 0 and 100.  
- Use `if`, `else if`, and `else` to print the grade: A, B, C, D, or F.  

### 3.2. Even or Odd
- Declare an `int` variable.  
- Use an `if` statement to check if the number is even or odd. Print the result. (hint: modulus operator)

### 3.3. Leap Year Checker
- Declare an `int` variable for a year.  
- Use `if` conditions to check whether the year is a leap year. A leap year is divisible by 4 but not by 100, unless it's also divisible by 400.  

### 3.4. Static: who is older?
- Declare two int variables, one for your age, one for a friend of yours.
- Use `if` and `else` statements to print the age of the oldest person

### 3.5. Dynamic: who is most experienced?
- Ask the user how many years of experiences 2 candidates have, for a developer job.
- Use `if` and `else` statements to print who has the most experience.
---

## 4. String Operations
- Given `final String input = "Hello, Beginner!";`, modify it to get `"BEGINNER"` using string methods.  
- Store the result in `final String answer`.  
- Ensure `System.out.println(answer.equals("BEGINNER"));` prints `true`.  

---

## 5. Loops
- Print numbers 1 to 10 using a `for` loop.  
- Print even numbers from 2 to 20 using a `while` loop.  
- Print "Hello" 5 times using a `do-while` loop. Also print the iteration you are currently on.  

---

## 6. Using `for-each`
- Create an array of numbers `{2, 4, 6, 8, 10}`.  
- Use a `for-each` loop to print each number.  

---

## 7. Methods and DRY Principle
- Create a method `printMessage(String message, int count)` that prints a message multiple times.  
- Call it with `"Hello"` and `3`.  
- Ensure the code is DRY (Don't Repeat Yourself).  

---

## 8. Classes and Objects
- Create a `Person` class with fields `name` (String) and `age` (int).  
- Instantiate a `Person` object and assign values to its fields.  
- Print the `name` and `age`.  

---

## 9. Using `record`
- Rewrite the `Person` class as a `record` type.  
- Instantiate it and print the `name` and `age`.  

---

## 10. Getters, Setters, and Fields
- Create a `BankAccount` class with a private field `balance` (double).  
- Add a `deposit` method to increase the balance.  
- Add a `withdraw` method that only allows withdrawal if enough funds exist.  
- Ensure `balance` can't be directly modified.  

---

## 11. Finding Data in Collections
- Create an array of numbers `{1, 3, 5, 7, 9}`.  
- Write a method that checks if a given number exists in the array.  
- Return `true` if found, `false` otherwise.  
- Use a loop.  

---

## 12. Using `contains()`
- Rewrite the previous task using a `List` and the `contains()` method instead of a loop.  