
# pixi.js backend shim 

for using canvas in node with pixi.js and maybe tiled-utils

https://github.com/Automattic/node-canvas/wiki/Installation---Windows

https://www.microsoft.com/en-us/download/details.aspx?id=48159

* Windows SDK 8.1

* Uniwersalny zestaw CRT systemu Windows

example use (in node js env):
```
# for pixi in node js
require('pixi-shim')
const PIXI = require('pixi.js')

# for tiled integration with pixi (in node/browser)
const TiledUtils = require('tiled-utils')
const tu = new TiledUtils(PIXI)
```