# recursive-stats

## Install

```bash
npm install recursive-stats --save
```

## Usage

```js

const stats = require('recursive-stats');

stats('/path/to/a', (err, res) => {
    if (err) {
        console.log(err);
    }

    console.log(res);
})
```
