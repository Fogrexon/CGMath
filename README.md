# CGMath

Math library for 3D Computer Graphics

## Build

In this repository
```
npm run build
```

## Install

In your repository
```
npm install cg-math
```

## Use

ESModule
```js
import { Vector4 } from 'cg-math';

const v = new Vector4(1.0, 0.0, 1.0, 0.0);

const mat = new Matrix4([
  1, 0, 0, 0,
  0, 1, 0, 1,
  0, 0, 1, 0,
  0, 1, 0, 0,
]);

const result = mat.multiply(v);

```

Browser
```javascript

const v = new CGMath.Vector4(1.0, 0.0, 1.0, 0.0);

const mat = new CGMath.Matrix4([
  1, 0, 0, 0,
  0, 1, 0, 1,
  0, 0, 1, 0,
  0, 1, 0, 0,
]);

const result = mat.multiply(v);
```

### Example

## Demos


## Author

Fogrexon
