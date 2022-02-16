# Javascript Reference




## Types

To check the type of any variable use the typeof operator

```
const variable = 5;
console.log(typeof variable);
```

- Number (1)
- String('cheese')
- Boolean (true)
- Array ([])
- Object({})

## Operators

### Math
- \+ = Addition
- \- = Subtraction
- \/ = Division
- \* = Multiplication
- % = Modulus\/Modulo
- ++ = increment
- \-\- = decrement

### Assignment
- = Assign
- += Add then assign
- -= Subtract then assign
- *= Multiply then assign
- /= Divide then assign
- %= Modulus then Assign

### Boolean

- \> Greater Than
- < Less Than
- == Equality
- === Strict Equality
- <= Less Than or Equal
- \>= Greater than or Equal
- != Not Equal
- && and
- || or

### Other Operators
- expression ? true : false = Ternary Operator
- typeof variable = typeof Operator
- delete object.property = Delete Operator to delete properties from an object
- value in array = in operator for arrays returns true if value is in the array
- key in object = in operator for objects returns true if property is in object
- variable instanceof Array = instanceof operator returns true if variable is of the specified type
- [one, ...theRemainder] = [1,2,3] = The rest operators, store the remainder of the collection in a variable, in this case theRemainder
- newObject = {...oldObject} = the spread operators assigns each property and value of an object to a new object at the top level

### Conditionals

#### If Statement
The code executes if the expression is true, if not code in an optional else statement will run.

```
if(expression){
    this code runs if true
} else {
    this code runs if false
}
```

#### Switch Statement
Will test the value against several cases, and run code for the cases that match. Break statements are typically used at the end of each case to prevent multiple matches and a default case may run if not cases match.

```
const myVariable = 'cheese';

switch(myVariable){
    case 'bread':
    code will run if variable equals 'bread'
    break

    case 'cheese:
    code will run if variable equals 'cheese'
    break

    default:
    code will run if no case matches
    break
}
```

### Functions

##### ES5 Functions
This is the older function syntax. This syntax has access to the arguments object which takes all arguments passed into the function into an object called arguments. This function syntax also doesn't bind the this keyword so "this" becomes the object that invokes the function not where is housed.

```
const oldFunction = function(parameters){
    code that runs when function is invokes
    return value
}

oldFunction()
```

##### ES6 Arrow Functions
This is the new function syntax that binds the this keyword but doesn't have access to the arguments object.

```
const newFunction = (parameters) => {
    code that runs when function is invokes
    return value
}
```

### Classes
Classes allow you define a blueprint for creating objects. Classes have a constructor and destructor function that run when an instance of the object is created or destroyed. Functions can be defined in the class, these are called as methods which an instance can invoke.

```
class Dog {
    constructor(parameters){
        this.property = parameter
    }

    myMethod (parameters){
        function code
    }
}

const newDog = new Dog(parameters);
newDog.myMethod();

```

## Videos

- [Javascript in 60 Minutes](https://www.youtube.com/watch?v=yN9-eBh3dSw&list=PLY6oTPmKnKbZDZ9cRrRby4Wnr4GIJj5O3&index=1&t=355s)
- [Javascript in 30 Minutes - Part 1](https://www.youtube.com/watch?v=VEnrgqenumY&t=1s)
- [Javascript in 30 Minutes - Part 2](https://www.youtube.com/watch?v=ZO10BXnUufk)
- [Scope Masterclass: var, let, const](https://www.youtube.com/watch?v=trez5PLZm7I)
- [Conditionals & Booleans Masterclass](https://www.youtube.com/watch?v=Qw9SEos9Ugk)
- [Loops Masterclass](https://www.youtube.com/watch?v=Yf6whlVj5qA)
- [Strings Masterclass](https://www.youtube.com/watch?v=EJy7f0YPgi8)
- [Array Methods](https://www.youtube.com/watch?v=CIWHuP8n_KA&t=4s)
- [Array Masterclass](https://www.youtube.com/watch?v=0rd-WuGtLgI)
- [Destructuring Masterclass](https://www.youtube.com/watch?v=T03vCdNz6h4&t=2s)
- [Everything on Functions](https://www.youtube.com/watch?v=fhLFpVeGdoU)
- [Iterating Masterclass](https://www.youtube.com/watch?v=JFf6ogtBUdo)
- [Objects Masterclass](https://www.youtube.com/watch?v=6Ytou94vP9g)
- [Prototypes Masterclass](https://www.youtube.com/watch?v=O_lyavc0lJc)
- [Web Components Masterclass](https://www.youtube.com/watch?v=qV7jh7ctALg)
- [Web Component Styling Masterclass](https://www.youtube.com/watch?v=9flT7pFyaXM)
- [OOP Masterclass](https://www.youtube.com/watch?v=IxbDwmNwnFQ)
- [Classes Masterclass](https://www.youtube.com/watch?v=O93r_ZB1NfQ)
- [Javascript DOM Manipulation](https://www.youtube.com/watch?v=CBzc-o6G9wg&list=PLY6oTPmKnKbbZvUyySSQYfnaClxfo4_iE)

## Resources and Attributions
- Thanks to [Alex Merced](https://meet.alexmercedcoder.com/) (GA SEI Lead Instructor) for developing this JavaScript reference guide. 