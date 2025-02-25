# C# Beginner Challenges

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
- Declare three variables: one for your name, one for your age, and one for your favorite color.
- Assign appropriate values to them.
- Declare a constant with any value.
- Print all values to the console.

**Knowledge:** `string`, `int`, `const`, `Console.WriteLine()`

---

## 2. Using `var`
- Declare three variables using `var` instead of explicit types.
- Assign a name, an age, and a favorite color to them.
- Print all values to the console.

**Knowledge:** `var`, `type inference`, `Console.WriteLine()`

---

## 3. If Statements and Comparisons
- Declare two integer variables.
- Use an `if` statement to check if the first number is greater than the second. Print a message if true.
- Check if two strings are equal (case-sensitive). Print a message if they match.
- Compare an integer to 100 and print whether it's greater, less than, or equal.

**Knowledge:** `if`, `bool`, `==`, `>`, `<`, `string.Equals()`

---

## 4. String Operations
- Given `const string input = "Hello, Beginner!"`, modify it to get `"BEGINNER"` using string methods.
- Store the result in `const string answer`.
- Ensure `Console.WriteLine(answer == "BEGINNER");` prints `true`.

**Knowledge:** `ToUpper()`, `Substring()`, `Length`

---

## 5. Loops
- Print numbers 1 to 10 using a `for` loop.
- Print even numbers from 2 to 20 using a `while` loop.
- Print "Hello" 5 times using a `do-while` loop. Also print the iteration you are currently on.

**Knowledge:** `for`, `while`, `do-while`

---

## 6. Using `foreach`
- Create an array of numbers `{2, 4, 6, 8, 10}`.
- Use a `foreach` loop to print each number.

**Knowledge:** `foreach`, `arrays`

---

## 7. Methods and DRY Principle
- Create a method `PrintMessage(string message, int count)` that prints a message multiple times.
- Call it with `"Hello"` and `3`.
- Ensure the code is DRY (Don't Repeat Yourself).

**Knowledge:** `methods`, `parameters`, `DRY principle`

---

## 8. Classes and Objects
- Create a `Person` class with properties `Name` and `Age`.
- Instantiate a `Person` object and assign values to its properties.
- Print the `Name` and `Age`.

**Knowledge:** `class`, `object`, `properties`

---

## 9. Using `record`
- Rewrite the `Person` class as a `record` type.
- Instantiate it and print the `Name` and `Age`.

**Knowledge:** `record`, `immutable types`

---

## 10. Getters, Setters, and Fields
- Create a `BankAccount` class with a private field `_balance`.
- Add a `Deposit` method to increase the balance.
- Add a `Withdraw` method that only allows withdrawal if enough funds exist.
- Ensure `balance` can't be directly modified.

**Knowledge:** `private`, `getter`, `setter`, `encapsulation`

---

## 11. Finding Data in Collections
- Create an array of numbers `{1, 3, 5, 7, 9}`.
- Write a method that checks if a given number exists in the array.
- Return `true` if found, `false` otherwise.
- Use a loop.

**Knowledge:** `arrays`, `loops`, `methods`

---

## 12. Using `Contains()`
- Rewrite the previous task using `Contains()` instead of a loop.

**Knowledge:** `Contains()`, `LINQ
