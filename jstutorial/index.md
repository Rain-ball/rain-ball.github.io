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
