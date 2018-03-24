# string-arraybuffer

> Easily convert string to arrayBuffer and from arrayBuffer to string

Useful when dealling with a function which accepts arraybuffer or return arraybuffer.


## Install

```
$ npm install string-arraybuffer
```


## Usage

```js
const string_arraybuffer = require('string-arraybuffer');

####Converting String to ArrayBuffer
string_arraybuffer.str2ab("I love Africa")
//=> Uint8Array [ 73, 32, 108, 111, 118, 101, 32, 65, 102, 114, 105, 99, 97 ]

####Converting ArrayBuffer to String
//=> "I love Africa"
```


## Related

## License

MIT © [Andrews Agyemang Opoku](http://fandrews.com)
