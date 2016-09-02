# statelib
A stupid, simple, clean, ridiculously small state management library

# Usage
```js
var statelib = require('./statelib');

var x = statelib(1);
console.log(x()); // output: 1

var y = statelib(() => x() + 2);
console.log(y()); // output: 3

x(8);
console.log(y()); // output: 10
```

# License
MIT