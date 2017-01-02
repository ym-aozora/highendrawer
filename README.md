# Highendrawer

Highendrawer provides javascript and css drawers to your website and applications.


## Demo

https://ym-aozora.github.io/highendrawer/


## Documentation

https://ym-aozora.github.io/highendrawer/doc/


## Usage

### With ES6/import

```javascript
import Highendrawer from 'highendrawer';

let drawer = new Highendrawer({
  element: document.getElementById('drawer')
});
```

### With require

```javascript
const Highendrawer = require('highendrawer');

let drawer = new Highendrawer({
  element: document.getElementById('drawer')
});
```

### With Browser

```html
<script src="dist/highendrawer.js"></script>
```

```javascript
var drawer = new Highendrawer({
  element: document.getElementById('drawer')
});
```


## License

[MIT](https://raw.githubusercontent.com/ym-aozora/highendrawer/master/LICENSE)
