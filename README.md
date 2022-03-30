# Anomaly Detection System - An Engine-based SDK

'ads-engine' is a JavsScript (ES6/Node14+) module that allows website owners to [...]

## Installation

Use the package manager [npm]() to install foobar.

```bash
npm install ads-engine // not yet added
```

## Usage

```javascript
/** eslint-ignore */
require('dotenv').config()
import * as ads from 'ads-engine' //es6
const ads = require('ads-engine') //es5

//iife for initialization
const {
USERNAME: string,
PASSWORD: string,
} = process.env

const config: {username: string, password: string} = {
username: USERNAME,
password: PASSWORD. 
}

(
async () => 
await ads.config(config)
)()
```


## Contributing
## License
[MIT](https://choosealicense.com/licenses/mit/)
