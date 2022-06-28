## Return Negative

```js
function makeNegative(num) {
  return num > 0 ? -num : num
}
```

## Sum of Positive

```js
function positiveSum(arr) {
  let sum = 0
  arr.forEach((num) => num > 0 && (sum += num))
  return sum
}
```

## Function 2

```js
function square(num) {
  return num * num
}
```

## Sum Arrays

```js
function sum (numbers) {
    "use strict";
    let sumNum = 0
    if (numbers.length > 0) {
      for(let i = 0; i < numbers.length; i++) {
        (sumNum += numbers[i])
      }
      return sumNum
    } else (numbers.length === 0) {
  return 0
    }
};
```

## Reversed Strings

```js
function solution(str) {
  return str.split('').reverse().join('')
}
solution('')
```
