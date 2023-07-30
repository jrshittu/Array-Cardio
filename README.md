# Array-Cardio
Certainly! Let's use different examples for each exercise:

## Exercise 1: Array.prototype.filter()

### Objective:
Filter an array of numbers to find all even numbers.

### Code:
```javascript
const numbers = [1, 2, 3, 4, 5, 6, 7, 8, 9, 10];

const evenNumbers = numbers.filter(number => number % 2 === 0);
console.log(evenNumbers);
```

### Solution:
```javascript
// Output will show an array of even numbers: [2, 4, 6, 8, 10].
```

## Exercise 2: Array.prototype.map()

### Objective:
Create an array of squared numbers from the given array.

### Code:
```javascript
const numbers = [1, 2, 3, 4, 5];

const squaredNumbers = numbers.map(number => number ** 2);
console.log(squaredNumbers);
```

### Solution:
```javascript
// Output will show an array of squared numbers: [1, 4, 9, 16, 25].
```

## Exercise 3: Array.prototype.sort()

### Objective:
Sort an array of strings in ascending order.

### Code:
```javascript
const fruits = ['banana', 'apple', 'orange', 'grape', 'kiwi'];

const sortedFruits = fruits.sort((a, b) => a.localeCompare(b));
console.log(sortedFruits);
```

### Solution:
```javascript
// Output will show the sorted array of fruits: ['apple', 'banana', 'grape', 'kiwi', 'orange'].
```

## Exercise 4: Array.prototype.reduce()

### Objective:
Calculate the sum of numbers in an array.

### Code:
```javascript
const numbers = [5, 10, 15, 20, 25];

const sum = numbers.reduce((total, number) => total + number, 0);
console.log(sum);
```

### Solution:
```javascript
// Output will show the sum of numbers: 75.
```

## Exercise 5: Additional Sorting

### Objective:
Sort an array of objects based on a property value.

### Code:
```javascript
const products = [
  { name: 'Laptop', price: 1200 },
  { name: 'Phone', price: 800 },
  { name: 'Tablet', price: 500 },
  { name: 'Camera', price: 1000 },
];

const sortedProducts = products.sort((a, b) => a.price - b.price);
console.log(sortedProducts);
```

### Solution:
```javascript
// Output will show the products sorted by price in ascending order.
```

## Exercise 6: Challenge (commented out)

### Objective:
Create a list of names that contain 'John' anywhere in the name.

### Code (commented out):
```javascript
// Challenge: Create a list of names that contain 'John' anywhere in the name.
const names = ['John Smith', 'David Johnson', 'Mary Johnson', 'Andrew Johnston', 'Steven Thompson'];

const filteredNames = names.filter(name => name.includes('John'));
console.log(filteredNames);
```

### Solution:
```javascript
// This code snippet will not run directly as it is commented out. You can uncomment and run it in your JavaScript environment.
```

## Exercise 7: Sorting People

### Objective:
Sort an array of people objects based on their ages.

### Code:
```javascript
const people = [
  { name: 'John', age: 30 },
  { name: 'Alice', age: 25 },
  { name: 'Bob', age: 40 },
  { name: 'Eve', age: 22 },
];

const sortedPeople = people.sort((a, b) => a.age - b.age);
console.log(sortedPeople);
```

### Solution:
```javascript
// Output will show the people objects sorted by age in ascending order.
```

## Exercise 8: Reducing Data

### Objective:
Count the occurrences of characters in a given string.

### Code:
```javascript
const sentence = 'hello world';

const charCount = sentence.split('').reduce((obj, char) => {
  if (!obj[char]) {
    obj[char] = 0;
  }
  obj[char]++;
  return obj;
}, {});

console.log(charCount);
```

### Solution:
```javascript
// Output will show an object with the count of occurrences of each character in the sentence.
```

Feel free to try out these exercises in your JavaScript environment to enhance your array manipulation skills! Happy coding! 😊
