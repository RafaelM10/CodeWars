## Problem
Create a function that takes an integer as an argument and returns "Even" for even numbers or "Odd" for odd numbers.

**First Solution:**
```javaScript


function evenOrOdd(number) {
  const isEvenOrOdd = number % 2 == 0 ? "Even" : "Odd"
  return isEvenOrOdd;
}

```