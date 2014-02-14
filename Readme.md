# util

  A Node.js compatible util module.

  It currently only implements the `inherits` function, to more easily allow
  `require('util').inherits` to work identical in both Node.js as well as
  browsers.

## Installation

  Install with [component(1)](http://component.io):

    $ component install Wizcorp/util

## API

```javascript
var inherits = require('util').inherits;

inherits(ChildClass, ParentClass);
```

## License

  MIT
