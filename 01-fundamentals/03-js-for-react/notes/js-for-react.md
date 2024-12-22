# Reading / Resources

- [Template literals (Template strings)](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Template_literals) (MDN)
- [Object initializer](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Operators/Object_initializer) (MDN)
- [Arrow function expressions](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Functions/Arrow_functions) (MDN)
- [Destructuring assignment](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Operators/Destructuring_assignment) (MDN)
- [Default parameters](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Functions/Default_parameters) (MDN)
- [Spread syntax (...)](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Operators/Spread_syntax) (MDN)
- [Rest parameters](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Functions/rest_parameters) (MDN)
- [JavaScript modules](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Guide/Modules) (MDN)
- [Array](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Array) (MDN)
- [Conditional (ternary) operator](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Operators/Conditional_operator) (MDN)
- [Optional chaining (?.)](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Operators/Optional_chaining) (MDN)
- [Logical AND (&&)](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Operators/Logical_AND) (MDN)
- [Logical OR (||)](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Operators/Logical_OR) (MDN)
- [Nullish coalescing operator (??)](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Operators/Nullish_coalescing) (MDN)

# Homework

### 1. Write a function called `introducePerson` that takes an object representing a person and returns a string introducing them. The object has properties: `firstName`, `lastName`, and `country`. If the country is missing, it should default to "Unknown".

```js
// code sample
const person = { firstName: "John", lastName: "Doe", country: "Greece" };
console.log(introducePerson(person)); // "Hello, I am John Doe from Greece."

const person2 = { firstName: "Jane", lastName: "Smith" };
console.log(introducePerson(person2)); // "Hello, I am Jane Smith from Unknown."
```

### 2. Given the below array of (user) objects, complete the below exercises

```js
const users = [
  { name: "Alice", age: 25, isAdmin: true, gender: "female" },
  { name: "Bob", age: 30, isAdmin: false, gender: "male" },
  { name: "Charlie", age: 35, isAdmin: true, gender: "male" },
  { name: "Daisy", age: 28, isAdmin: false, gender: "female" },
  { name: "Edward", age: 40, isAdmin: true, gender: "male" },
];
```

### Write the following functions:

1. **filterAdmins**: Returns an array of all users who are admins (`isAdmin: true`).
2. **filterByGender**: Accepts a gender string ("male" or "female") and returns an array of user objects
3. **getUserNames**: Returns an array of names of all users in the original array.
4. **findUserByName**: Accepts a name string and returns the user object with that name (or undefined if not found).
5. **getAverageAge**: Returns the average age of all users.
