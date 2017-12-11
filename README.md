# Crypto API for JavaScript/TypeScript
It's a library is cut from https://github.com/nf404/crypto-api

[It's a library is cut from](https://github.com/nf404/crypto-api)
([Crypto API for JavaScript](https://github.com/nf404/crypto-api))



## Examples



Using on JavaScript(ES6)/TypeScript
```typescript
import {Whirlpool,encoders}  from '../common/whirlpool'

let whirlpool = new Whirlpool()
let hash=whirlpool.getHash("message")
encoders.toBase64(hash)
encoders.fromBase64('bWVzc2FnZQ==')
encoders.fromUtf("message")
encoders.toHex('message')
```


