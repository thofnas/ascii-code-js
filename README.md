# ASCII code
ASCII encoder and decoder in javascript.

## Usage
HTML:
```javascript
<script src="ascii.js"></script>
```

JavaScript:
```javascript
const message = "'Even a man who has nothing can still offer his life.'"
const encoded_message = encode(message)
const decoded_message = decode(encoded_message)
```

10-digit Decimal code:
```javascript
const message = "'Even a man who has nothing can still offer his life.'"
const encoded_message = encode(message, 'dec') //'hex' by default
const decoded_message = decode(encoded_message, 'dec') //'hex' by default
```

## Special thanks to
[justynr](https://github.com/justynr) for his [Ascii table](https://github.com/justynr/Ascii-JSON-Table) (Please don't ban me I just dunno anything about the GNU license)
