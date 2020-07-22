# is-xid
is-xid is a unique id checker module for node.js.

## Install
```
npm i is-xid
```

## Usage
```js
const isXid = require('is-xid');

const id = 'bs6mkqt4pi406bibv930';
isXid(id); // true
```

## Checks
- Character length is equal to 20,
- Bytes length is equal to 12,
- Encoding is in Base32 hex,
- K-ordered string (incoming feature)

## Licence
[MIT License](https://github.com/joffreyverd/is-xid/blob/master/LICENSE)

### Documentation
[xid](https://github.com/rs/xid)
