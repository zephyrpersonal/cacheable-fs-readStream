# Cacheable-Fs-Stream

## Usage

```js
const createCacheableStream = require('cacheable-fs-stream')
const getCacheableFileStream = createCacheableStream()

getCacheableFileStream('path/to/your/file', e => {
  console.error(e)
  // handle error
}).pipe(writableStream)
```

## TODO

[ ] add multiple stores support
