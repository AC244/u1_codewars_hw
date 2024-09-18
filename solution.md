## Return Negative

```
function makeNegative(num) {
  if (num < 0) {
    return num * 1
  } else { return num * -1
    
  }
}

makeNegative()
```

## Sum of Positive

```
function positiveSum(arr) {
sum = 0;
  for (i = 0; i < arr.length; i++)
  if (arr[i] > 0) {
  sum += arr[i];
    }
  return sum
   }
  
```

## Function 2

```
function square(s) {
  return s ** 2
}
```

## Sum Arrays

```
// Sum Numbers
function sum (numbers) {
    "use strict";
 if (numbers.length === 0) return 0; 
  return numbers.reduce((total, currentValue) => total + currentValue);
    
};
```

## Reversed Strings

```
function solution(str){
  return str.split('').reverse().join('')
}
```
