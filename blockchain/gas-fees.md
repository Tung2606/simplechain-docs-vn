# Phí gas

Gas fee là chi phí xử lý transaction trên SimpleChain.

## Mục đích của gas fee

Gas được sử dụng để:

- chống spam transaction
- trả thưởng validator
- xử lý smart contract

## Thành phần gas

| Thành phần | Ý nghĩa |
|---|---|
| Gas Limit | giới hạn gas |
| Gas Price | giá gas |
| Total Fee | tổng phí |

## Công thức tính

```text
Total Fee = Gas Limit × Gas Price
```

## Ví dụ

| Gas Limit | Gas Price | Total Fee |
|---|---|---|
| 21000 | 1 Gwei | 0.000021 SIM |

## Tối ưu gas fee

- tránh transaction dư thừa
- tối ưu smart contract
- sử dụng batch transaction