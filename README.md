# browser-log

A dead simple logger for the browser

## Example

``` js
var log = require('browser-log').create()
// manually enable logging
log.enabled = true

log.silly("any", 'logging', 'data')
log.verbose("any", 'logging', 'data')
log.info("any", 'logging', 'data')
log.warn("any", 'logging', 'data')
log.error("any", 'logging', 'data')
```

## Installation

`npm install browser-log`

## Contributors

 - Raynos

## MIT Licenced