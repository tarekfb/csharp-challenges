# C# Beginner Challenges

## 1. Variables and Console Output
- Declare three variables: one for your name, one for your age, and one for your favorite color.
- Assign appropriate values to them.
- Declare a constant with any value.
- Print all values to the console.
- Don't use `var` for the constant.

**Knowledge:** `string`, `int`, `const`, `Console.WriteLine()`

---

## 2. If Statements and Comparisons
- Declare two integer variables.
- Use an `if` statement to check if the first number is greater than the second. Print a message if true.
- Check if two strings are equal (case-sensitive). Print a message if they match.
- Compare an integer to 100 and print whether it's greater, less than, or equal.
- Don't use `switch` statements.

**Knowledge:** `if`, `bool`, `==`, `>`, `<`, `string.Equals()`

---

## 3. String Operations
- Given `const string input = "Hello, Beginner!"`, modify it to get `"BEGINNER"` using string methods.
- Store the result in `const string answer`.
- Ensure `Console.WriteLine(answer == "BEGINNER");` prints `true`.
- Don't manually type `"BEGINNER"` as the answer.

**Knowledge:** `ToUpper()`, `Substring()`, `Length`

---

## 4. Loops
- Print numbers 1 to 10 using a `for` loop.
- Print even numbers from 2 to 20 using a `while` loop.
- Print "Hello" 5 times using a `do-while` loop.
- Don't use `foreach` for this task.

**Knowledge:** `for`, `while`, `do-while`

---

## 5. Methods and DRY Principle
- Create a method `PrintMessage(string message, int count)` that prints a message multiple times.
- Call it with `"Hello"` and `3`.
- Ensure calling the method reduces repeated code.
- Don't use recursion.

**Knowledge:** `methods`, `parameters`, `DRY principle`

---

## 6. Classes and Objects
- Create a `Person` class with properties `Name` and `Age`.
- Instantiate a `Person` object and assign values to its properties.
- Print the `Name` and `Age`.
- Don't use `record`.

**Knowledge:** `class`, `object`, `properties`

---

## 7. Getters, Setters, and Fields
- Create a `BankAccount` class with a private field `_balance`.
- Add a `Deposit` method to increase the balance.
- Add a `Withdraw` method that only allows withdrawal if enough funds exist.
- Ensure `balance` can't be directly modified.
- Don't make `_balance` public.

**Knowledge:** `private`, `getter`, `setter`, `encapsulation`

---

## 8. Finding Data in Collections
- Create an array of numbers `{1, 3, 5, 7, 9}`.
- Write a method that checks if a given number exists in the array.
- Return `true` if found, `false` otherwise.
- Use a loop, not `Contains()`.

**Knowledge:** `arrays`, `loops`, `methods`
