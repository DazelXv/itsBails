# Baileys WhisykeySocket
<p align='center'>
  <img src="https://files.catbox.moe/4lqm94.jpg" width="500">
</p>

--- 

## Usage
```json
"depencies": {
  "zelbail": "github:DazelXv/itsBails"
}
```
## Import
```javascript
const {
  default:makeWASocket,
  // Other Options 
} = require('zelbail');
```


## Tutorial !
```javascript
const {
  default: makeWASocket,
  fetchLatestWAWebVersion
} = require('zelbail');

const client = makeWASocket({
  browser: ['Ubuntu', 'Chrome', '20.00.1'],
  printQRInTerminal: false,
  version: fetchLatestWAWebVersion()
  // Other options
});
