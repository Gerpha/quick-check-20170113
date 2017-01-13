# Quick Check

- For this pop quiz, feel free to use your editor/repl.it to write and VERIFY your answer.
- Paste your answer into the appropriate place below when you are done.
- Your answer MUST work in the examples provided

## Standard: Solve problems that require swapping

### Write a function that swaps two elements in an array

- The function will swap the elements at the two given indexes
- The array outside of the function must be affected by any changes
- You cannot use scope outside of the function

e.g.
```js
var numbers = [2, 1]
swap(numbers, 1, 0)
console.log(numbers) // [1, 2]

var objects = [{name: "Busta"}, {name: "Carey"}, {name: "Mariah"}, {name: "Rhymes"}]
swap(objects, 1, 3)
console.log(objects) // [{name: "Busta"}, {name: "Rhymes"}, {name: "Mariah"}, {name: "Carey"}]

var empty = []
swap(empty, 1, 3)
console.log(empty) // []

var one = [1]
swap(one, 0, -1)
console.log(one) // [1]
swap(one, -1, 0)
console.log(one) // [1]

function swap(array, first_index, second_index) {
  // -- YOUR ANSWER HERE --
}
```

### Write a function that reverses an array in place, using the above `swap()` function

- Implement the function using only (but not necessarily all)
  - basic operations (`[]`, `+`, `-`, `++`, `let`, etc.)
  - loops
  - `Array.length`
  - the `swap()` function that you wrote above
  - the `Math` library
- The function must be as efficient as possible

e.g.
```js
var odds = [3, 9, 7, 5]
console.log(odds) // [3, 9, 7, 5]
reverse(odds)
console.log(odds) // [5, 7, 9, 3]

var evens = [2, 8, 6, 4, 10]
console.log(evens) // [2, 8, 6, 4, 10]
reverse(evens)
console.log(evens) // [10, 4, 6, 8, 2]

function reverse(array) {
  // -- YOUR ANSWER HERE --
}
```
