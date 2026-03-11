# JavaScript Beginner Challenges

This project contains a collection of beginner-friendly JavaScript functions designed to practice core programming fundamentals.

The challenges focus on learning how to use:

* Functions
* Parameters
* Return values
* Arithmetic operations
* Boolean logic
* Conditional statements
* The modulus operator

Each function solves a small coding challenge and prints the result using `console.log()`.

---

# Project Structure

```
javascript-beginner-challenges/
│
├── index.html
├── app.js
└── README.md
```

* **index.html** – Loads the JavaScript file
* **script.js** – Contains all challenge solutions
* **README.md** – Documentation for the project

---

# How to Run the Project

## Option 1 – Run in the Browser

1. Open `index.html`
2. Right click the page
3. Click **Inspect**
4. Go to the **Console tab**

You will see the results printed from the JavaScript functions.

---

## Option 2 – Run with Node.js

If you have Node installed:

```
node script.js
```

---

# Challenges Included

## 1. Addition

Adds two numbers together.

```
addition(num1, num2)
```

Example:

```
addition(3,5)
```

Output:

```
8
```

---

## 2. Hours Into Seconds

Converts hours into seconds.

Formula:

```
hours * 60 * 60
```

Example:

```
hoursIntoSeconds(2)
```

Output:

```
7200
```

---

## 3. Rectangle Perimeter

Calculates the perimeter of a rectangle.

Formula:

```
2 * (length + width)
```

Example:

```
calcPerimeter(10,20)
```

Output:

```
60
```

---

## 4. Triangle Area

Calculates the area of a triangle.

Formula:

```
0.5 * base * height
```

Example:

```
calcAreaofTriangle(20,20)
```

Output:

```
200
```

---

## 5. Append Frontend

Adds 4 to the provided number.

Example:

```
appendFrontend(1)
```

Output:

```
5
```

---

## 6. Greater Than 100

Returns `true` if the sum of two numbers is greater than or equal to 100.

Example:

```
GreaterThan100(50,50)
```

Output:

```
true
```

---

## 7. Less Than or Equal to Zero

Checks if a number is less than or equal to zero.

Example:

```
lessThanOrEqualToZero(-5)
```

Output:

```
true
```

---

## 8. Opposite Boolean

Returns the opposite boolean value.

Example:

```
oppositeBoolean(false)
```

Output:

```
true
```

---

## 9. Is Not Zero

Checks if a number is not equal to zero.

Example:

```
isNotZero(5)
```

Output:

```
true
```

---

## 10. Remainder

Returns the remainder when dividing two numbers.

Example:

```
calcRemainder(10,3)
```

Output:

```
1
```

---

## 11. Even Number

Checks if a number is even.

Example:

```
isEven(4)
```

Output:

```
true
```

---

## 12. Odd Number

Checks if a number is odd.

Example:

```
isOdd(5)
```

Output:

```
true
```

---

## 13. Boolean Integer

Returns:

```
1  if the number is positive
-1 if the number is negative
```

Example:

```
booleaninterger(15)
```

Output:

```
1
```

---

## 14. Logged In AND Subscribed

Checks if a user is logged in **and** subscribed.

Example:

```
isLoggedInAndSubscribed(true, true)
```

Output:

```
true
```

---

## 15. Logged In OR Subscribed

Checks if a user is logged in **or** subscribed.

Example:

```
isLoggedInOrSubscribed(true, false)
```

Output:

```
true
```

---

## 16. Logged In AND Unsubscribed

Checks if a user is logged in but not subscribed.

Example:

```
isLoggedInAndUnsubscribed(true, false)
```

Output:

```
false
```

---

# Skills Practiced

This project helps build foundational JavaScript knowledge including:

* Writing reusable functions
* Using `return`
* Boolean logic (`&&`, `||`, `!`)
* Conditional statements
* Arithmetic operations
* Using the modulus operator `%`
* Using the ternary operator

---

# Future Improvements

Possible extensions for this project:

* Add user input
* Create additional coding challenges
* Convert challenges into automated tests
* Build a simple UI for the challenges
* Organize challenges into difficulty levels

---

# Author

Created as part of JavaScript practice and learning exercises.
