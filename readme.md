README!!

Hello, and welcome to testing the productOfFive code as a team.

You will need to run "npm install mocha chai" (tho maybe we don't need chai? Whatever) in your terminal.

//TESTING
Tests for the functionality will be written in the test.js file.

You must require assert, and both functions from the index.js file(productOfFive and multiply).

Describe productOfFive.
  Test should return error message "Number must be at least 5 digits" when input is less than 5 characters.

  It should work with a number that has a length of 5 digits.

  It should work with numbers larger than 5 digits.
    Use three separate test cases.

  It should check for large numbers and let user know to pass a string ("large numbers must be passed a string").
    Use number larger than 16 characters.

  It should work with large numbers.

//INDEX.JS
Need a function called 'multiply' that multiplies 2 numbers together.

Need a function called 'productOfFive' that:
  1) turns input to a string
  2) checks if input is 5 characters and returns error if not
  3) checks if the input is greater than 16 characters and alerts user "large numbers must be passed as a string"
  4) 3 variables:
    a) productList set to empty array
    b) inputArr set to input as a string and then split
    c) numToMultiply set to 5

  Ok, I think that's it. Let's build and burn Teddi's code:)
