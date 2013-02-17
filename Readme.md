
# prevent

  Cross-browser preventDefault

## Installation

    $ component install yields/prevent

## Example

```js
anchor.onclick = require('prevent');
anchor.onclick = function(e){
  if (something) return require('prevent')(e);
};
```

## API

### prevent(e)

  Prevent the given `e`.

## License

  MIT
