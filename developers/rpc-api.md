# RPC API

SimpleChain hỗ trợ JSON-RPC API tương thích EVM.

## RPC Endpoint

```bash
https://rpc.simplechain.com
```

## Lấy block hiện tại

### Request

```json
{
  "jsonrpc":"2.0",
  "method":"eth_blockNumber",
  "params":[],
  "id":1
}
```

### Response

```json
{
  "jsonrpc":"2.0",
  "id":1,
  "result":"0x1b4"
}
```

## Lấy số dư ví

### Request

```json
{
  "jsonrpc":"2.0",
  "method":"eth_getBalance",
  "params":[
    "0x0000000000000000000000000000000000000000",
    "latest"
  ],
  "id":1
}
```

## WebSocket Support

```bash
wss://rpc.simplechain.com/ws
```

## API tương thích

- Ethereum JSON-RPC
- Web3.js
- Ethers.js
- Hardhat