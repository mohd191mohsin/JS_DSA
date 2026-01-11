# 📦 JavaScript Array Methods – Complete Guide

This document contains **all JavaScript Array methods**, grouped logically with **simple explanations and examples**.

---

## 🔹 Add / Remove Elements

### `push()`
Adds element(s) at the end.
```js
arr.push(3);
```

### `pop()`
Removes the last element.
```js
arr.pop()
```

### `unshift()`
Adds element(s) at the beginning.
```js
arr.unshift(1);
```
### `shift()`
Removes the first element.
```js
arr.shift();
```

### `splice()`
Adds, removes, or replaces elements.
```js
arr.splice(1, 1, 99);
```


## 🔹 Search / Find Elements

### `includes()`

Checks if value exists.
```js
arr.includes(2);
```

## `indexOf()`

Returns first index of value.
```js
arr.indexOf(2);
```

## `lastIndexOf()`
Returns last index of value.
```js
arr.lastIndexOf(2);
```

## `find()`
Returns first element matching condition.
```js
arr.find(x => x > 2);
```

## `findIndex()`
Returns index of first match.
```js
arr.findIndex(x => x > 2);
```

## `findLast()`
Returns last matching element.
```js
arr.findLast(x => x > 2);
```

## `findLastIndex()`
Returns index of last match.
```js
arr.findLastIndex(x => x > 2);
```