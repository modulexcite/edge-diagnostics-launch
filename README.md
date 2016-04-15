# edge-diagnostics-launch
Launcher for Microsoft Edge Diagnostics Adapter to make it simpler to start an instance of the Edge with diagnostics enabled.

## Installation
`npm install edge-diagnostics-launch`

## Options
No options for now.

## Usage
```javascript
var launch = require('edge-diagnostics-launch')
var options = {}

// launch(<url>, <options>, callback)
launch('http://microsoft.com', options, function(err, strout) {
  console.log('err', err)
})
```

## License

MIT.
