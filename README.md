# babel-plugin-virtual-jade

Compiles virtual .jade files into raw css for import into a javascript variables
```js
import template from './buttons.jade'
```

## Install

```
npm i babel-plugin-virtual-jade --save-dev
```

## Usage
### Babel config
```
{
  "plugins": ["babel-plugin-virtual-jade"]
}
```

### CLI
```
babel --plugins babel-plugin-virtual-jade src/ --out-dir build
```

## Change log

### 1.0.0
* Initial release

