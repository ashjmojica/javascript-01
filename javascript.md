All programming languages contain certain things in them. These things are variables, functions, loops, and other similar things. How they are written and used is usually different for each language but the underlying concepts are generally the same.

Syntax, these are the rules of the language you are using. If your code does not compile, it more than likely is a syntax error.

Never infer logic to a computer or a program. The more literal you are in programming, the easier it is for a computer to understand and compile the program.

## Variables

- To create a variable in javascript you have to start with 3 words, 2 of which you should use for now and one to avoid.

All variables have to start with either const, var, let and then a name. You then assign (using the = sign) it a value.

A variable name is up to you. It does not matter what you call it as long as you are not repeating another variable name. The best practice is to be explicit and literal with the name.

A good name is as follows:
`const studentName = "Ashley"`

A bad name is as follows: `const b = 123`

Always always try to be clear in your code. Clever code is not necessarily easy to understand.

1. `const` stands for constant. This means if you define something with `const`, it will not change.

`const ashley = "ashley"`
ashley is never going to be anything else than what I defined it as.

2. `let` stands for let. This is used if you want to make a variable that you might change the value of later on.

`let ta = "Jaye"`
reassignment
`ta = "Bill"`

You can change a `let` variable as many times as you want. The last time you change it will be what it is going forward.

let ta = "Jaye"
ta = "Randy"
ta = "Rayleigh"
ta = "Gill"

3. `var` is old. Don't use it.

`var` stands for variable.
`var teacher = "Joe"`

You can also reassign it.
`teacher = "Azan"`

You define a variable by using the words `const, let, var`, a name for the variable, and then the = sign (assignment operator).

`const nameOfVariable = whatevervalueyouwant`

## Data types

1. Strings
2. Integers
3. Floats
4. Booleans
5. Arrays
6. Objects

### Strings
Strings are anything in double quotations `""` or single quotations `''` or in javascript `` backticks.

Strings are iterable. It means, you can iterate or go over each individual character of a string. You can also access an individual letter in a string by it's number. Remember, numbers in programming start at 0.

const joe = "joe"
joe[0]
'j'
joe[1]
'o'
joe[2]
'e'
joe[9] = undefined, because there isn't anything at the 9th index or the 8th place in this word.
You can do units of math on a string. But you can only add strings.

Integers
This means a whole number. That means anything with the numbers of 0-9.

let age = 0123456789

Integers are not iterable. However, integers can have mathematical logic applied to them. You can add, subtract, multiply and divide.

const sum = 1 + 2

What is the value of sum? An integer of 3.
const p = 34 * 9

The units of operation are + / * - addition, division, multiplication and subtraction.

Float
Any number with a decimal is a float.

const pie = 3.14

Same math can be applied to floats however....but rounding up or down is generally something we need to add more logic to.

Boolean
Is a datatype that can be only one of two things. true or false.

Booleans will always equate to "Truthy" or "Falsey". Note that somtimes it's not as simple as the word 'true' or 'false'. You might need to do the logic to determine if the value is true or false or if the logic is truthy or falsey.

const raining = true

Arrays
Arrays are sometimes called list in other programming languages. What it means at the end of the day, is a variable that is assigned []

const students = [
    "Kimberly", "Ashley", "Cameron"
]

const groupOfNumbers = [1,2,3,4,65,9]
const user = ["Joe","Tomball", 77375]
You can access the individual elements of an array by it's index. In other words, like strings, you can use [] and a index, and get a single value from the array.

const DCStaff = ["Alyson","Jerry", "Joe"]
DCStaff[2] // "Joe"
DCStaff[1] // "Jerry"
DCStaff[0] // "Alyson"

What is the way to get to the crown?

const crown =[[[[[[[["crown"]]]]]]]] crown[0]

const crown = [8] // you are redifining and will get an error here since crown exist above

Object
An object is a datatype that is defined using the {} and they always consist of key: value pairs.

const student = {
    name: "Cameron",
    city: "Marrieta",
    state: "GA",
    zipcode: 30008,
    pets: ["Frenchie","Cane Corso"]
    }

student.pets[1] // "Cane Corso"
student.city // "Marrieta"
student.state // "GA"
student.job = "software dev" // this is how you add a new key to an object
