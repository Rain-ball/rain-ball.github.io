# JavaScript Tutorial  
## Basics  
### What is JavaScript?  
JavaScript is a programming language used almost everywhere when it comes to web development.
### Why learn JavaScript?  
Javascript is worth learning because
1. It can be effortlessly embedded into HTML files and can manipulate DOM elements.
2. Node JavaScript servers are extremely fast and efficient.
3. JavaScript with the help of frameworks can be useful to make a variety of things such as portfolio pages, video games, discord bots etc.
4. JavaScript is very easy, especially because of its huge library of inbuilt functions, no type checking, enormous community and curly bracket syntax.  
### Logic  
Before learning JavaScript we have to learn the logic and learn it theoretically.

Processes

JavaScript processes end with a semicolon, though the semicolon is not compulsory, but as a good practice it is recommended to add semicolons.
Comments have the same syntax as they have in C++ or Java.  
```js
console.log("Hello World"); // will display Hello World
// variables are declared with either var or let
// if you want the variable to be a parameter of window object, use var
// if you want block scope, use let
// constant variables are declared using const keyword which can have block scope
// operators are similar to those in other popular programming languages
// for boolean, false and 0 are the false values, all other values are true
// to initialise an object of a predefined class just call its constructor e.g. const objectName = new className(arguments);
// array is initialised as e.g. let array = [12, 13, 14, 11];
```  

Conditions  

Type 1: if..else  
```js
if (/*condition*/) {
  // code to be executed if condition == true
}
else if (/*condition2*/) {
  // code to be executed if condition2 == true
}
// you can add any number of conditions just there should be at least one
// you can skip the else statement if you don't think it necessary
else {
  // code to be executed if both condition == false and condition2 == false
}
```  

Type 2: switch  
```js
switch(/*variable*/) {
  case /*value1*/:
    // code to be executed when variable == value1
    break; // don't forget to add this
  case /*value2*/:
    // code to be executed when variable == value2
    break;
  // you can add any number of cases here
  default:
    // this block of code can be skipped if you don't want
    // code to be executed when both variable != value1 and variable!= value2
}
```  

Type 3: ternary operator  
```js
/* variable to which value is to be assigned*/ = (/*condition*/) ? /*true*/ : /*false*/;
```  

Loops  

Type 1: for loop  
```js
for(let i = 1/*initialise counter variable*/;i <= 10/*enter the condition which will keep the loop running until the condition becomes false*/;i++/*increase or decrease value of counter*/) {
  // write code to be executed
}
```  
Type 2: while loop
```js
while(/*condition to be true until the loop is running*/) {
  // code to be executed
}
```  

Type 3: do while loop  
Do while loop is very similar to while loop with the only difference that the condition is checked at the end instead of start.  
```js
do {
  // code to be executed
} while (/*condition to be true until the loop is running*/)
```  

Type 4: foreach loop  
Foreach loop is nothing but a for loop with an array as input instead of a condition.  
```js
// (arguments) => {code} or function(arguments) {code} is an anonymous function in JavaScript
// function name(arguments) {code} or name = function(arguments) {code} is a function in JavaScript
/*JavaScript array*/.forEach((/*parameters, you can add any number of them or only add the 1st one, but remeber if you add, the 1st parameter is element of the array, 2nd is the index of the element and 3rd is the array itself) -> {
  // code to be executed with each element, index and/or the whole array
})
```
