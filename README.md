## Prune Number Counters

Basically, prune a.k.a abbreviate number counters for example **1,250,000** to **1.3M**

### Install Pruned

```bash
npm i pruned
```
### Import pruned in your react app

```js
import pruned from 'pruned';
```

### Require the pruned package

```js
const pruned = require('pruned');
```

### Pass in the number value

```js
let newRating = pruned.Number(value);
```

### Examples...

```js
let value = 5300;
let likes = pruned.Number(value); // Output : 5.3K
```