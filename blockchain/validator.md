# Validator

Validator là thành phần quan trọng của mạng SimpleChain.

## Vai trò

Validator thực hiện:

- xác thực giao dịch
- tạo block
- đồng bộ blockchain
- bảo mật mạng

## Yêu cầu hệ thống

| Thành phần | Khuyến nghị |
|---|---|
| CPU | 4 Core |
| RAM | 8 GB |
| Storage | SSD 200 GB |
| Network | 100 Mbps |

## Cài đặt node

Clone source:

```bash
git clone https://github.com/simplechain/node.git
```

Cài dependencies:

```bash
npm install
```

Khởi động node:

```bash
npm run start
```

## Đồng bộ blockchain

Node sẽ tự:

- tải block
- xác thực dữ liệu
- đồng bộ trạng thái mạng

## Bảo mật validator

Khuyến nghị:

- sử dụng firewall
- backup private key
- không public server management port
> 🔒 Khuyến nghị sử dụng VPS riêng cho validator production.