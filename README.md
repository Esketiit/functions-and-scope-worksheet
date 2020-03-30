### Writing functions in JavaScript

1. Write a function named `hiWorld` that prints 'hello world' to the console

```javascript
```

2. Write the same function from above in 2 other ways using different syntax

```javascript
```

3. Write a function that accepts a 'name' parameter and prints "Hi, my name is `<name>`" to the console

```javascript
```

4. Write a funtion that accepts 2 numbers as parameters and returns their sum

```javascript
```

5. Write a function that accepts a number as a parameter returns the double of it

```javascript
```

6. Write a function called `logger` that accepts a string as a parameter and then passes that string to `console.log`. Use `logger` as a callback to console.log each element in the array below. 

```javascript
let stringArray = ["JavaScript", "is pretty", "cool", "I guess."]

// put answer here
```

7. Write a function that accepts a number as a parameter and prints "❌ You're too young to enter the clurb! ❌" if the parameter 
is less than 21 and "🤡 Welcome to the clurb! 🚀" if the parameter is 21 or over

```javascript
```

8. Modify the above function to allow an underage patron in if they have a fake id

```javascript
```

### Scope in JavaScript

1. What is lexical scope?

```
```

2. What would be printed to the console in the example below? Why?

```javascript
let carType = "Honda Civic"

function myCar(carType){
  console.log(`I drive a fancy ass ${carType}!`)
}

carType('Tesla X')
```

```
```

3. What would be printed to the console in the example below? Why?

```javascript
let carType = "Honda Civic"

function myCar(carType){
  console.log(`I drive a fancy ass ${carType}!`)
}

carType('Tesla X')
```

```
```

4. What would be printed in each of the console.log calls in the example below? Why?

```javascript

console.log(person) // write answer here

let person = "Lady Gaga"

function someFunction(){
  console.log(person) // write answer here

  function otherFunction(){
    let otherPerson = "Madonna"

    console.log(person) // write answer here
    console.log(otherPerson) // write answer here
  }

  otherFunction()

  console.log(person) // write answer here
  console.log(otherPerson) // write answer here  
}

someFunction()

console.log(otherPerson)
```

5. What would be printed to the console in the example below? Why?

```javascript
if(true){
  let dogName = "Neikko"
  console.log(`My dog's name is ${dogName}`)
}

console.log(`My dog's name is ${dogName}`)
```

```
```

#### Hoisting

1. In your own words, describe hoisting?


2. If I had a JavaScript file with the following code, what would happen in each of the function calls below? Why?

```javascript
bark()
meow()

function bark(){
  console.log("woof woof")
}

let meow = function(){
  console.log("meeeeooooowwr")
}
```

```
```

3. What will the console.log print in each of the examples below? Why?

```javascript
console.log(dogName)

var dogName = "Perky"
```

```javascript
console.log(catName)

const catName = "Houdini"
```

```
```

4. What will the console.log print in the example below? Why?

```javascript
horse = "Benny"
console.log(horse)
var horse
```

```
```

5. With regard to hoisting, what's the difference between `let`, `var`, and `const`

```
```

### Variable declaration

1. What are the differences between declaring variables using `let`, `var`, and `const`?

```
```

### First Class Functions

1. Write a function that accepts a number (e.g. *x*) as a parameter and returns an inner function that accepts a different number (e.g. *y*) as a parameter and returns the product of it and the number from the outer function.

```javascript
```

2. Using the function from above, create a function that accepts a number as a parameter and returns its double. 

```javascript
```

3. If you successfully got the question above working, explain how you utilized closures to do so?

```
```

4. What would get printed to the console in the example below?

```javascript
let steven = {
  name: "Steven",
  goForRun: function(distance){
    console.log(`Today I ran ${distance} km.`)
  }
}

steven.goForRun // what would happen here?

steven.goForRun()
```

```
```