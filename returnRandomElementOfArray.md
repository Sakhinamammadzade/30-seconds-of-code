---
title: Return random element from array
tags: array,random
cover: colorful-plastic
firstSeen: 2023-03-25T14:53:01+02:00
lastUpdated: 2023-03-25T14:53:01+02:00
---

- This function takes an array as input and returns a random element from the array.
- It uses the Math.random() method to generate a random index within the range of the array length, then returns the
  element at that index.

```javascript
const getRandomElement = (arr) => arr[Math.floor(Math.random() * arr.length)];
```