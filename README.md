# Writing a Function in JavaScript

In JavaScript, functions are blocks of reusable code. They allow you to bundle functionality, make it more readable, and avoid repetition. Here's a brief tutorial on writing an arrow function in JavaScript.

## 1. Basic syntax
```
 **const** **functionName** = (**params**) => {
  **// code to be executed**
}
```
+ **const**: const should be used whenever a function expression is assigned to a variable.
The function name: The name you choose for the function.
+ **Parameters**: Optional comma separated parameters. This is the data passed into the function. If there are no parameters, the () is still required.
+ **The arrow syntax:** Indicates that this will be a function.
+ **The body:** The statements that make up the function itself. Surrounded by curly braces.

### ___Example___:

```

 const greet = (name) => {
  console.log("Hello, " + name + "!");
}
```
>Tip: Functions often perform actions, so naming with a verb can make it clear what the function does. Examples include **fetchData**( ), **calculateArea**( ), or **printReport**( ). 

## 2. Calling a function

To execute the function, you ___call___ or ___invoke___ it by using its name followed by parentheses.

### ___Example___:
```
greet ('Alice'); // Outputs: Hello, Alice!
```
## 3. Return values

Functions can process data input and output a value using the ___return___ keyword.

### ___Example___: 

```
const addNums = (numA, numB) => {
  return numA + numB
}

const total = addNums(2, 4);

console.log(total) // Expected value: 6 ;
```

### For more information on functions and how they are used in JS, check out the [MDN](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Guide/Functions) docs. 



![Computer with Code](https://plus.unsplash.com/premium_photo-1678566154673-a728037f3f00?w=800&auto=format&fit=crop&q=60&ixlib=rb-4.0.3&ixid=M3wxMjA3fDB8MHxzZWFyY2h8MXx8cHJvZ3JhbW1lcnxlbnwwfHwwfHx8MA%3D%3D/image)
# markdown-lab
