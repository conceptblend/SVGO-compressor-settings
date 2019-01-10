# SVGO-compressor-settings
My preferred settings for the Sketch SVGO compressor plugin

### Modified settings
```javascript
convertPathData : true // RISK: Modifies path data and _could_ modify the shape. PRO: reduces paths dramatically and hasn't affected the paths tested to date in any significant way.
removeHiddenElems: true // I mean, why not?!?
removeStyleElement : true // for good measure (we don't use this)
removeScriptElement : true // for good measure
moveElemsAttrsToGroup : true // this will elevate attributes on flattened shapes
```
