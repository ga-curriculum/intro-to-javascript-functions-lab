# ![Intro to JavaScript Functions Lab - Exercise](./assets/hero.png)

## Introduction

This lab provides an opportunity to practice defining and calling functions in JavaScript.

### A quick note before you dive in

If you find yourself stuck during the lab, we encourage you to first revisit the lesson materials. They're designed to provide you with the information and examples that will help you complete the exercises. 

If you've revisited the materials and are still facing challenges, don't hesitate to collaborate with your classmates.

Lastly, the internet is filled with resources specific to JavaScript arrays. Websites like [Google](https://www.google.com/), [MDN Web Docs on Arrays](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Array), and [Stack Overflow](https://stackoverflow.com/questions/tagged/javascript+arrays) are just a few clicks away. Use these as a last resort, before reaching out for help.

Happy coding!

## Lab Exercises

Copy and paste each of the following exercises into your JavaScript file. To check your work, open the `index.html` file in a web browser and inspect the browser console, or run the javascript file directly in your terminal using `node script.js`. 

### Exercise 1: `maxOfTwoNumbers`

```js
/*
Exercise 1: maxOfTwoNumbers

In this exercise, create a function named maxOfTwoNumbers. It should take two numbers as inputs and return the larger number. If they're equal, return either one.

Exercise 1 has been completed for you:
*/

const maxOfTwoNumbers = (x, y) => {
  if (x >= y) {
    return x;
  } else {
    return y;
  }
}

console.log('Exercise 1 Result:', maxOfTwoNumbers(3, 9));
```

### Exercise 2: `isAdult`
```js
/*
Exercise: isAdult

Write a function named isAdult. It should take an age (number) and return 'Adult' if the age is 18 or over, and 'Minor' otherwise.

Example: isAdult(21) should return 'Adult'.

Complete exercise in the space below:
*/


console.log('Exercise 2 Result:', isAdult(21));
```

### Exercise 3: `isCharAVowel`
```js
/*
Exercise: isCharAVowel

Write a function named isCharAVowel that takes a single character as an argument. It should return true if the character is a vowel, and false otherwise.

Complete exercise in the space below:
*/



console.log('Exercise 3 Result:', isCharAVowel("a"));
```

### Exercise 4: `generateEmail`
```js
/*
Exercise: generateEmail

Create a function named generateEmail. It should take two strings: a name and a domain, and return a simple email address.

Example: generateEmail('johnsmith', 'example.com') should return 'johnsmith@example.com'.

Complete exercise in the space below:
*/

console.log('Exercise 4 Result:', generateEmail("johnsmith", "example.com"));
```

### Exercise 5: `greetUser`
```js
/*
Exercise: greetUser

Define a function called greetUser. It should take a name and a time of day (morning, afternoon, evening) and return a personalized greeting.

Example: greetUser('Sam', 'morning') should return "Good morning, Sam!"

Complete exercise in the space below:
*/



console.log('Exercise 5 Result:', greetUser("Sam", "morning"));
```

### Exercise 6: `reverseString`
```js
/*
Exercise: reverseString

Define a function called reverseString. It should take a string and return it with its characters in reverse order. For example, reverseString('rockstar'); would return the string "ratskcor".

Complete exercise in the space below:
*/



console.log('Exercise 6 Result:', reverseString("rockstar"));
```

### Exercise 7: `checkPalindrome`
```js
/*
Exercise: checkPalindrome

Define a function called checkPalindrome. It should take a string and return true if the string is a palindrome (reads the same forwards and backwards) and false otherwise.

Example: checkPalindrome('radar') should return true.

Complete exercise in the space below:
*/



console.log('Exercise 7 Result:', checkPalindrome("radar"));
```

### Exercise 8: `maxOfThree`
```js
/*
Exercise: maxOfThree

Define a function, maxOfThree, it should accept three numbers and return the largest among them.

Complete exercise in the space below:
*/



console.log('Exercise 8 Result:', maxOfThree(5, 10, 8));
```

### Exercise 9: `calculateTip`
```js
/*
Exercise: calculateTip

Create a function called calculateTip. It should take two arguments: the bill amount and the tip percentage (as a whole number). Return the amount of tip.

Example: calculateTip(50, 20) should return 10.

Complete exercise in the space below:
*/



console.log('Exercise 9 Result:', calculateTip(50, 20));
```

### Exercise 10: `convertTemperature`
```js
/*
Exercise: convertTemperature

Write a function named convertTemperature. It takes two arguments: a temperature and a string representing the scale ('C' for Celsius, 'F' for Fahrenheit). Convert the temperature to the other scale.

Example: convertTemperature(32, 'C') should return 89.6 (Fahrenheit).

Complete exercise in the space below:
*/



console.log('Exercise 10 Result:', convertTemperature(32, "C"));
```

## Level Up

### Exercise 11: `basicCalculator`
```js
/*
Exercise: basicCalculator

Create a function named basicCalculator. It should take three arguments: two numbers and a string representing an operation ('add', 'subtract', 'multiply', 'divide'). Perform the operation on the numbers.

Example: basicCalculator(10, 5, 'subtract') should return 5.

Complete exercise in the space below:
*/



console.log('Exercise 11 Result:', basicCalculator(10, 5, "subtract"));
```

### Exercise 12: `calculateGrade`
```js
/*
Exercise: calculateGrade

Define a function called calculateGrade. It should take a numerical score and return the corresponding letter grade (A, B, C, D, F). For example, 90 and above yields an 'A', 80-89 is a 'B', and so on.

Complete exercise in the space below:
*/



console.log('Exercise 12 Result:', calculateGrade(85));
```

### Ecercise 13: `createUsername`
```js
/*
Exercise: createUsername

Define a function called createUsername. It should take a first name and a last name and return a username. The username should be a combination of the following:
- The first three letters of the first name.
- The first three letters of the last name.
- The total character count of the first and last name combined.

Example: createUsername('Samantha', 'Green') should return 'SamGre12'.

Complete exercise in the space below:
*/



console.log('Exercise 13 Result:', createUsername("Samantha", "Green"));
```

### Exercise 14: `numArgs`
```js
/*
Exercise: numArgs

Challenge yourself with numArgs. This function should return the count of arguments passed to it when called.

Complete exercise in the space below:
*/


console.log('Exercise 14 Result:', numArgs(1, 2, 3, 4));
```

<br>

**🎉  The End. You did it!  🎉**
