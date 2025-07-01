// Create an array and add elements
const fruits = ['Apple', "Pear"];
fruits.unshift('Banana');
fruits.push('Orange');
console.log(fruits); // [ 'Banana', 'Apple', 'Pear', 'Orange' ]

// Delete element by index
let numbers = [10, 20, 30, 40, 50];
numbers.splice(2, 1);
console.log(numbers); // [10, 20, 40, 50]

// Double all numbers
let nums = [1, 2, 3, 4];
let doubled = nums.map((x) => x * 2);
console.log(doubled); // [2, 4, 6, 8]

// Filter out even numbers
let values = [5, 12, 8, 3, 7];
let evens = values.filter((x) => x % 2 === 0);
console.log(evens); // [12, 8]