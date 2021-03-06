*This repository is a mirror of the [component](http://component.io) module [danzajdband/random](http://github.com/danzajdband/random). It has been modified to work with NPM+Browserify. You can install it using the command `npm install npmcomponent/danzajdband-random`. Please do not open issues or send pull requests against this repo. If you have issues with this repo, report it to [npmcomponent](https://github.com/airportyh/npmcomponent).*
# random

  Generate random numbers

## Installation

    $ component install danzajdband/random

## Usage


```js
var rand = require('random');

console.log(rand()); // Returns a Number between 0 and 1.
console.log(rand(1)); // Returns a Number between 1 and 2.
console.log(rand(-6, 38)); // Returns a Number between -6 and 38.
console.log(rand(7, 19, true)); // Returns a Integer between 7 and 19.
```


## API

### random(min = 0, max = min + 1, truncate)
  
Return a random number between `min` and `max`. If truncate is set to `true` return only integer values.


## License

  MIT
