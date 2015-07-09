# afor

Simple npm module to make async iterators in Node.js

### Installation
```
npm install afor --save
```

### Usage
```
var afor = require('afor');

afor(0, 1000, function(i){
  console.log('I: ' + i);
});
```

### Why an async iterator?
Try this code in your Node.js console and check it yourself:
```
for (var i = 0; i < 10000000; i++) {
  console.log("We're on:", i);
}
```

