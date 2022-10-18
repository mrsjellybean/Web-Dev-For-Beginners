# Fun with Functions

## Instructions

Create different functions, both functions that return something and functions that don't return anything.

function printAnimal(animal, name){
  console.log(`Hi ${name}, your fav animal is ${animal}`);
}
printAnimal('Panda', 'Yuliia');


function addNumbers(){
  let firstNumber = 12;
  let secondNumber = 10;
  let result = firstNumber+secondNumber;
}


See if you can create a function that has a mix of parameters and parameters with default values.


function printAnimal(animal, name, day='Monday'){
  console.log(`Hi ${name}, your fav animal is ${animal} on ${day}`);
}
printAnimal('Panda', 'Yuliia');
printAnimal('Frog', 'Anna');
printAnimal('Bear', 'Nick');

## Rubric

| Criteria | Exemplary                                                                              | Adequate                                                         | Needs Improvement |
| -------- | -------------------------------------------------------------------------------------- | ---------------------------------------------------------------- | ----------------- |
|          | Solution is offered with two or more well-performing functions with diverse parameters | Working solution is offered with one function and few parameters | Solution has bugs |
