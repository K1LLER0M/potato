# potato.js

A potato library inspired by [five.js](https://github.com/jackdclark/five)

## Usage:

### Install the module

```sh
npm install potatojs
# Or with yarn
yarn add potatojs
```

### Require the module

```javascript
var potato = require('potatojs');
```

### In the browser

```javascript
<script type="text/javascript" src="./potato.js"></script>
```

### A potato

```javascript
potato(); // "potato"
```

### Check for potato

```javascript
potato.isPotato("potato"); // true
```

### Potato emoji

```javascript
potato.emoji(); // "🥔"
```

### Fries emoji

```javascript
potato.best(); // "🍟"
```

### A potato with a delay

```javascript
potato.slowCook(500); // "potato" after 500 ms
```

### A picture of a potato

```javascript
potato.picture(); // you can guess it
```

### Async code

```javascript
potato.async().then(potato => {
  // potato === "potato"
})
```

### Different radices

```javascript
potato.binary(); // 0b011100000110111101110100011000010111010001101111
potato.hex(); // 0x706f7461746f
```

### Potato md5 hash

```javascript
potato.md5(); // "8ee2027983915ec78acc45027d874316"
```

### Generate random potato
```javascript
potato.random(); // "delicious potato"
```

## Lisence
MIT