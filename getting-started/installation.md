# Cài đặt

Hướng dẫn cài đặt và kết nối với mạng SimpleChain.

## Yêu cầu hệ thống

Trước khi bắt đầu, cần cài đặt:

- Node.js >= 18
- Git
- MetaMask
- VS Code

## Cài Node.js

Truy cập website chính thức:

- https://nodejs.org

Kiểm tra phiên bản:

```bash
node -v
npm -v
```

## Clone project

```bash
git clone https://github.com/Tung2606/simplechain-docs-vn.git
```

## Cài dependencies

```bash
npm install
```

## Kết nối RPC

Thông tin mạng SimpleChain:

| Thông tin | Giá trị |
|---|---|
| RPC URL | https://rpc.simplechain.com |
| Chain ID | 1337 |
| Currency Symbol | SIM |

## Kiểm tra kết nối

Sau khi cài đặt thành công:

- ví có thể kết nối mạng
- có thể gửi transaction
- có thể deploy smart contract

## Lỗi thường gặp

### Sai Chain ID

Kiểm tra lại:

```bash
Chain ID: 1337
```

### RPC không phản hồi

- kiểm tra internet
- kiểm tra URL RPC
- thử reconnect ví