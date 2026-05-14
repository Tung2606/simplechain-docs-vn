# Cơ chế đồng thuận

SimpleChain sử dụng cơ chế đồng thuận Validator-based để đảm bảo:

- bảo mật mạng
- tốc độ giao dịch cao
- khả năng mở rộng

## Validator

Validator chịu trách nhiệm:

- xác thực block
- xác thực transaction
- duy trì trạng thái blockchain

## Quy trình xác thực

```text
User Transaction
↓
Mempool
↓
Validator xác thực
↓
Tạo block mới
↓
Block được thêm vào blockchain
```

## Ưu điểm

- phí thấp
- tốc độ nhanh
- block time ổn định
- tiết kiệm tài nguyên hơn Proof of Work

## Bảo mật

Hệ thống validator giúp:

- giảm spam transaction
- chống tấn công mạng
- tăng độ ổn định blockchain