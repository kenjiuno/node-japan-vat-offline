# node-japan-vat-offline

Supply a well known copy of Japanese consumption tax table.

```js
const japanVat = require('node-japan-vat-offline');

console.log(japanVat.table());
```

Sample output:

```txt
[ { since: '2019-10-01', percent: 10 },
  { since: '2014-04-01', percent: 8 },
  { since: '1997-04-01', percent: 5 },
  { since: '1989-04-01', percent: 3 } ]
```
