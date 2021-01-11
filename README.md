# Js-assessment
Just some JavaScript questions I was given in an internship assessment test.


Question 3) Write a simple function in JavaScript to loop through the first 200 numbers. If the number is divisible by 3, store it in a Fizz array. If the number is divisible by 5, store it in Buzz  array, If the number is divisible by 3 and 5, store it in FizzBuzz array, otherwise store the number in Others.

Use the structure below as a guide:

This is an empty array =>  [ ]

let Fizz = [ ];
let Buzz = [ ];
let FizzBuzz = [ ];
let Other  = [ ];

for (let i = 1; i <= 200; i++) {
    if (i % 3 === 0 && i % 5 === 0) {
        // do something
     } else if (???) {
         // do something
     } else if (???) {
        // do something
     } else {
         // do something
    }
}

console.log("Total Number of Fizz = "      + Fizz.length);
console.log("Total Number of Buzz = "      + ???.length);
console.log("Total Number of FizzBuzz = "  + FizzBuzz.length);
console.log("Total Number of Other = "    + ???.length);


