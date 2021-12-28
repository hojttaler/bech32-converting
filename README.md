# bech32-converting

This library is designed to convert bech32 addresses to hex and vice versa.

## Installation

```bash
npm install bech32-converting
```

## Usage
```javascript
import converter from "bech32-converting"

converter('prefix').toHex('address')
converter('prefix').toBech32('address')

// Example

converter('eth').toBech32('0x0E3f45Cbfda1C9Eb008Ebc9873F3DBA1d9A86E9D')
// eth1pcl5tjla58y7kqywhjv88u7m58v6sm5afc6dwn

converter('eth').toHex('eth1pcl5tjla58y7kqywhjv88u7m58v6sm5afc6dwn')
// 0x0E3f45Cbfda1C9Eb008Ebc9873F3DBA1d9A86E9D
```
