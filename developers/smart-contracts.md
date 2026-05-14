# Smart Contract

SimpleChain hỗ trợ triển khai smart contract bằng Solidity.

## Yêu cầu

Cài đặt:

- Node.js
- Hardhat
- MetaMask

## Cài Hardhat

```bash
npm install --save-dev hardhat
```

## Tạo project

```bash
npx hardhat
```

## Ví dụ contract

```solidity
// SPDX-License-Identifier: MIT
pragma solidity ^0.8.0;

contract HelloSimpleChain {
    string public message = "Hello SimpleChain";
}
```

## Deploy contract

```bash
npx hardhat run scripts/deploy.js --network simplechain
```

## Kết nối network

```javascript
module.exports = {
  networks: {
    simplechain: {
      url: "https://rpc.simplechain.com",
      chainId: 1337
    }
  }
};
```