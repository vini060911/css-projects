#GEOM - Formas geométricas

```javascript
class GEOMAngles {
  width
  height
}

const GEOMangles = GEOMAngles

class GEOM {
  TRIANGLE = 0
  SQUARE = 1
  RECTANGLE = 2
  CIRCLE = 3
  ANGLE = GEOMangles
}

function geometry2d(data) {
  data.domElement.style.background = data.background
}

const GEOM = new GEOM()
const TRIANGLE = GEOM.TRIANGLE, SQUARE = GEOM.SQUARE, RECTANGLE = GEOM.RECTANGLE, CIRCLE = GEOM.CIRCLE

const geom = new geometry2d({ domElement: document.createElement })
```
