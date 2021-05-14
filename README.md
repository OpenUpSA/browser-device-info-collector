# browser-device-info-collector
Really simple browser and device information collector. Submits to a Google Form. 

The JavaScript is intentionally simple and verbose to work on as many browsers as is possible with the fewest fatal errors.

Currently attempts to collect:
```
navigator.hardwareConcurrency
navigator.deviceMemory
navigator.platform
navigator.userAgent
navigator.appVersion
navigator.vendor
navigator.connection.downlink
navigator.connection.rtt
navigator.connection.effectiveType
navigator.connection.saveData
window.indexedDB
window.crypto
window.devicePixelRatio
window.localStorage
window.sessionStorage
window.screen.availHeight
window.screen.availWidth
window.screen.height
window.screen.width
window.screen.pixelDepth
window.screen.colorDepth
```