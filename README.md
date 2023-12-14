Summary of https://www.w3schools.com/js/js_array_methods.asp
An array is a special variable, which can hold more than one value. 
JavaScript Array length
The length property returns the length (size) of an array
JavaScript Array toString()
The JavaScript method toString() converts an array to a string of (comma separated) array values.


Summary of https://www.w3schools.com/js/js_functions.asp
A JavaScript function is a block of code designed to perform a particular task.
Why Functions?
With functions you can reuse code
You can write code that can be used many times.
You can use the same code with different arguments, to produce different results.
JavaScript Function Syntax
A JavaScript function is defined with the function keyword, followed by a name, followed by parentheses (). 
function name(parameter1, parameter2, parameter3) {
  // code to be executed
}

(Summary of https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Functions)
A function is a "subprogram" that can be called by code external (or internal, in the case of recursion) to the function. Like the program itself, a function is composed of a sequence of statements called the function body. Values can be passed to a function as parameters, and the function will return a value.
Function Syntax
function formatNumber(num) {
  return num.toFixed(2);
}

formatNumber(2);

where num is the function’s parameter, 

Summary of https://www.javascripthelp.org/learn/basics/control-flow-statements/
In JavaScript, there are three main types of control flow statements:

if/else statements
If/else statements are used to execute a block of code if a certain condition is true, and a different block of code if the condition is false.
Syntax: if (condition){
//block of codes to be executed if condition is true
} else{
// block of codes to be executed if condition is false
}

switch statements: Switch statements are used to execute a block of code based on the value of a variable or expression.
Syntax:
switch(expression) {
  case x:
    // code block
    break;
  case y:
    // code block
    break;
  default:
    // code block
}
The switch expression is evaluated once.
The value of the expression is compared with the values of each case.
If there is a match, the associated block of code is executed.
If there is no match, the default code block is executed.
3. Loops.
Loops are used to execute a block of code multiple times, based on a certain condition. There are two main types of loops in JavaScript: for loops and while loops.
For Loops: 
Syntax:
for (initialization; condition; finalExpression) {
  // code
}
The for loop consists of three optional expressions, followed by a code block:

initialization - This expression runs before the execution of the first loop, and is usually used to create a counter.
condition - This expression is checked each time before the loop runs. If it evaluates to true, the statement or code in the loop is executed. If it evaluates to false, the loop stops. And if this expression is omitted, it automatically evaluates to true.
finalExpression - This expression is executed after each iteration of the loop. This is usually used to increment a counter, but can be used to decrement a counter instead.


While loop
Syntax: 
while (condition) {
  // statement
}
The while loop starts by evaluating condition. If condition evaluates to true, the code in the code block gets executed. If condition evaluates to false, the code in the code block is not executed and the loop ends.



Summary of https://javascript.info/function-basics
Functions are the main “building blocks” of the program. They allow the code to be called many times without repetition.
