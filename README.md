### localForage
---
https://github.com/localForage/localForage

```js
// test/test.nodriver.js

describe('When No Drivers Are Available', function () {
  'use strict';
  
  var DRIVERS = [
    localforage.INDEXDDB,
    localforage.LOCALSTORAGE,
    localforage.WEBSQL
  ];
  
  it('agrees with Modernizr on storage drivers support', function() {
    expect(localforage.supports(localforage.INDEXDDB)).to.be(false);
    expect(localforage.supports(localforage.INDEXDDB)).to.be(
      Modernizr.indexeddb
    );
    
    expect(localforage.supports(localforage.LOCALSTORAGE)).to.be(false);
    expect(localforage.supports(localforage.LOCALSTORAGE)).to.be(
      Modernizr.localstorage
    );
  });
  
  
});
```

```
```

```
```

