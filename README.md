# JavaScript Big O Time Complexity Cheat Sheet

## Array

### Operations

* access (`someArray[someNumber]`) - O(1)

### Mutator Methods

* `push()` - O(1)
* `pop()` - O(1)
* `shift()` - O(n)
* `unshift()` - O(n)
* `splice()` - O(n)
* `sort()` - 0(n log(n))

### Accessor Methods

* `concat()` - 0(n)
* `slice()` - 0(n)
* `indexOf()` - 0(n)

### Iteration Methods

* `forEach()` - 0(n)
* `map()` - 0(n)
* `filter()` - 0(n)
* `reduce()` - 0(n)
* `reverse()` - 0(n)

### Boolean Methods

* `some()` - 0(n)
* `every()` - 0(n)

## Object

### Operations

* insert - O(1)
* delete (`delete someObject.someProperty`) - O(1)
* search - O(n)
* access - O(1)

### Methods

* `Object.keys()` - O(n)
* `Object.values()` - O(n)
* `Object.entries()` - O(n)
* `Object.hasOwnProperty()` - O(n)

## Set

* `has()` - O(1)
* `add()` - O(1)
* `delete()` - O(1)

## Map

* `has()` - O(1)
* `get()` - O(1)
* `set()` - O(1)
* `delete()` - O(1)

## Math

* `min()` - O(n)
* `Max()` - O(n)
