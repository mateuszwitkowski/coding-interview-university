## Algorithmic complexity / Big-O / Asymptotic analysis

- describing how algorithm performance scales as the input amount increases (without regard to runtime environment specifics)
-  &Omega; - best-case scenario
- O - worst-case scenario
- &theta; - when best-case scenario is the same as the worst-case scenario

O(1)

```JavaScript
const arr = [];
function addToArray(val) {
  arr.push(val);
}
```

O(n)

```JavaScript
const arr = [1, 2, 3, 4, 5, 6];
function isValueInArray(arr, val) {
  let isInArray = false;
  for (let i = 0; i < arr.length; i++) {
    if (arr[i] === val) {
      isInArray = true;
    }
  }

  return isInArray
}
```

O(N^2)

Example: bubble sort (loop inside the loop)

O(log N)

Example: binary search

O(n log n)

### Links:
- [Big-O Cheat Sheet](http://bigocheatsheet.com/)