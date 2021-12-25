1. Convert the function below into different forms of function expression.

```js
function percentage(marks, total) {
  return (marks * 100) / total;
}


// Your code goes here
```
let rep= function percentage(marks, total) {
  return (marks * 100) / total;
}

let rep2=(marks, total)=> {
  return (marks * 100) / total;
}
2. Write Function Declaration or Function Expression next to the function.

```js
function percentage(marks, total) {
  return (marks * 100) / total;
}
// D
```

```js
let percentage = function percentage(marks, total) {
  return (marks * 100) / total;
};
```
// E
```js
let percentage = function (marks, total) {
  return (marks * 100) / total;
};
```
// E
```js
let percentage = (marks, total) => {
  return (marks * 100) / total;
};
```
E
```js
let percentage = (marks, total) => (marks * 100) / total;
```
E
3. Why is a function definition an expression in JavaScript? Give one example of function expression.
// because t can be writtten at the right side of equal to
4. Why is a function call an expression in JavaScript?
same as above
5. Write VALID and INVALID next to each example below with the reason.

```js
function add(a, b) {
  return a + b;
}
//valid
let five = add(2, 3); // valid
five = add; // Answer //invalid
five = five(10, 11); // valid
five = function () {//valid
  return 'Hello';
}; // Answer
```

6. What is the difference between function definition and function call? Explain with an example.
defination is where we define it and call is where we call it to run it
7. What is the similarities between function definition and function call?
   both have the function name in it.
8. Is the code below valid or invalid. Explain with reason.

```js
function hello() {
  console.log('Hello World!');
}

hello.user = 'Sam'; // valid because function is an object
```

9. What is higher order function explain with an example.
A function inside a function is called highe order function.All array methods are higher order functions.
10. Explain what is callback function. Why you can pass a function inside a function?
callback function is the function which is passes in the higher order function