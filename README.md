# union.js

File JavaScript sederhana untuk menggabungkan dua array menjadi satu (union).

## Cara Penggunaan

```js
const union = (a, b) => [...new Set([...a, ...b])];

console.log(union([1, 2, 3], [3, 4, 5]));
// Output: [1, 2, 3, 4, 5]
