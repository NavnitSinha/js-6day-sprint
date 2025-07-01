PART 1: Syntax & Variables

1. Basic Syntax
   
JavaScript runs line by line, top to bottom.
console.log("Hello, world!");
  - Statements end with ; (optional but good practice).
  - Case-sensitive: Name ≠ name

2. Declaring Variables

let name = "Navnit";   // can change later
const age = 25;        // cannot be reassigned
var mood = "chill";    // older way (avoid using)

✅ PART 2: Data Types

let city = "Delhi";         // String
let year = 2025;            // Number
let isCool = true;          // Boolean
let nothing = null;         // Null
let notAssigned;            // Undefined
let car = {brand: "BMW"};   // Object
let colors = ["red", "blue"]; // Array

Use typeof to check:

console.log(typeof city); // "string"

✅ PART 3: Loops (Power Moves)

For Loop

for (let i = 0; i < 5; i++) {
  console.log("Count: " + i);
}

While Loop

let i = 0;
while (i < 5) {
  console.log("While count: " + i);
  i++;
}

✅ PART 4: Arrays (Your Toolkit)

let fruits = ["apple", "banana", "cherry"];
console.log(fruits[1]); // banana
fruits.push("dragonfruit"); // add to end
fruits.pop();               // remove from end
for (let fruit of fruits) {
  console.log(fruit);
}

✅ PART 5: Functions (Your Superpower)

function greet(name) {
  console.log("Hi, " + name + "!");
}

greet("Navnit");
Arrow function version:

const greet = (name) => {
  console.log("Yo, " + name + "!");
};

1. let: Use this to create a variable that can change.
2. const : Use this to create a variable that won’t change.
3. var : Old-school way to create variables. Don't use it now unless you have a good reason. let is better and safer.
4. console.log() : It prints stuff to the console (your screen output).

