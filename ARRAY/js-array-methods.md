# 📦 JavaScript Array Methods – Complete Guide

This document contains **all JavaScript Array methods**, grouped logically with **simple explanations and examples**.

---

## Initialize Array

```js
let arr = [1, 2,3];
```

## 🔹 Add / Remove Elements

### `push()`
Adds element(s) at the end.
```js
arr.push(4);
// Output: [1, 2, 3, 4]

```

### `pop()`
Removes the last element.
```js
arr.pop();
// Output: [1, 2]

```

### `unshift()`
Adds element(s) at the beginning.
```js
arr.unshift(0);
// Output: [0, 1, 2, 3]

```
### `shift()`
Removes the first element.
```js
arr.shift();
// Output: [2, 3]

```

### `splice()`
Adds, removes, or replaces elements.
```js
arr.splice(1, 1, 99);
// Output: [1, 99, 3]

```


## 🔹 Search / Find Elements

### `includes()`

Checks if value exists.
```js
arr.includes(2);
// Output: true

```

## `indexOf()`

Returns first index of value.
```js
arr.indexOf(2);
// Output: 1

```

## `lastIndexOf()`
Returns last index of value.
```js
arr.lastIndexOf(2);
// Output: 1


```

## `find()`
Returns first element matching condition.
```js
arr.find(x => x > 2);
// Output: 3

```

## `findIndex()`
Returns index of first match.
```js
arr.findIndex(x => x > 2);
// Output: 2

```

## `findLast()`
Returns last matching element.
```js
arr.findLast(x => x > 1);
// Output: 3

```

## `findLastIndex()`
Returns index of last match.
```js
arr.findLastIndex(x => x > 1);
// Output: 2

```