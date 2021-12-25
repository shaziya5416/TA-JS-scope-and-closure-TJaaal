1. What does thread of execution means in JavaScript?
//it means how does a code gets executed
2. Where the JavaScript code gets executed?
//happens in an execution context
3. What does context means in Global Execution Context?
it creates a context onvcle globally 
4. When do you create a global execution context.
everytime we load a js file we create gec
5. Execution context consists of what all things?
it is the environmnt in which js executes.It consists variables,memory,objects,code ,function
6. What are the different types of execution context?
global and function
7. When global and function execution context gets created?
whenever there is a function it gets executed
8. Function execution gets created during function execution or while declaring a function.
declaring

9. Create a execution context diagram of the following code on your notebook. Take a screenshot/photo and store it in the folder named `img`. Use `![](./img/image-name.png)` to display it here.



```js
var user = "Arya";

function sayHello(){
  return `Hello ${user}`;
}

var userMsg = sayHello(user);
```

<!-- Put your image here -->

![](./img/image-name.jpg)



```js
var marks = 400;
var total = 500;

function getPercentage(amount, totalAmount){
  return (amount * 100) / totalAmount;
}

var percentageMarks = getPercentage(marks, total);
var percentageProfit = getPercentage(400, 200);
```

<!-- Put your image here -->

![](./img/image-name.jpg)



```js
var age = 21;

function customeMessage(userAge){
  if(userAge > 18){
    return `You are an adult`;
  }else {
    return `You are a kid`;
  }
}

var whoAmI = customeMessage(age);
var whoAmIAgain = customeMessage(12);
```

<!-- Put your image here -->

![](./img/image-name.jpg)