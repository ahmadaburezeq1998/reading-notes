# functions 
#### its a set of statments to perform or calculate a task so it has an iniput and return an output we also have to define it and call it 

### how we define it ? 
1. function 
2. function name 
3. (parameter1,parameter2,parameter3)
4. a javascript statment that define what the function will do inside two {}

### example
`function square(number)
{return number*number ;}`


### Function expressions
`var square = function(number) { return number * number }
var x = square(4)`


### Calling functions
#### after we define a function we must call it like this 
`square(23)`
and then it will return the value to us 


#### we can check our code for errors using the `console.log(function())`

#### example 
`console.log(square(20));`

### recursive function 

#### its a function that will call itself while ruining like the following 
`function loop(x) {
  if (x >= 10) // "x >= 10" is the exit condition (equivalent to "!(x < 10)")
    return;
  
  loop(x + 1); 
}
loop(22);`