## Usage

```javascript
var format = require('format-util')
  , msg = format('%s', 'foo');
```

Or with an array of values in the second argument just like with vsprintf:
```javascript
var format = require('format-util')
  , msg = format('My name is %s, I drink %s!', ['Alex', 'vodka']);
```
