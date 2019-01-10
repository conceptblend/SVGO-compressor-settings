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

### How to update your settings

To update your SVGO Compressor Settings:
1. Ensure you have [SVGO Compressor plugin](https://github.com/BohemianCoding/svgo-compressor) installed
1. Open Sketch
1. Navigate to Plugins > SVGO Compressor > About SVGO Compressor
1. Click "Edit SVGO Settings…"
1. Copy the contents of [svgo.json](https://github.com/conceptblend/SVGO-compressor-settings/raw/master/svgo.json) into the text editor
1. Save and Close the svgo.json settings file
1. Return to Sketch
