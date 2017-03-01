# babel-plugin-virtual-jade

Compiles and inlines virtual .jade files
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

### 1.3.0
* Pass plugin options through to virtual-jade
### 1.0.0
* Initial release

