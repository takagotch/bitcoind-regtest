### bitcoind-regtest
---
https://github.com/fanatid/bitcoind-regtest

```js
import RgtestBitcoind from 'bitcoin-regtest'

setImmediate(async () => {
  let bitcoind = new RegtestBitcoind()
  await bitcoind.ready
  await bitcoind.generateBlocks(105)
  let preload = await bitcoind.getPreload()
  console.log(preload)
  
  await bitcoind.terminate()
})
```

```
```

```
```


