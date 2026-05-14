# SDK

SimpleChain hỗ trợ nhiều SDK dành cho developer.

## Web3.js

Cài đặt:

```bash
npm install web3
```

Kết nối RPC:

```javascript
const Web3 = require("web3");

const web3 = new Web3(
  "https://rpc.simplechain.com"
);
```

## Ethers.js

Cài đặt:

```bash
npm install ethers
```

Kết nối:

```javascript
const { ethers } = require("ethers");

const provider = new ethers.JsonRpcProvider(
  "https://rpc.simplechain.com"
);
```

## Hardhat

SimpleChain tương thích hoàn toàn với Hardhat.

## Foundry

Có thể deploy smart contract bằng Foundry.