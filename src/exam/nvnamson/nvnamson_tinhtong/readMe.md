# Tính tổng các số chẵn không chia hết cho 3

## Mô tả bài toán

Cho hai số nguyên A và B, tính tổng tất cả các số nguyên i thỏa mãn:

- A < i < B
- i là số chẵn (i % 2 == 0)
- i không chia hết cho 3 (i % 3 != 0)

## Input

- Dòng đầu tiên chứa số nguyên A
- Dòng thứ hai chứa số nguyên B

## Output

- Một số nguyên duy nhất là tổng các số thỏa mãn điều kiện

## Ví dụ

### Input

```
1
33
```

### Output

```
182
```

## Giải thích

Các số thỏa mãn điều kiện trong khoảng (1, 33) là: 2, 4, 8, 10, 14, 16, 20, 22, 26, 28, 32
Tổng của chúng là: 2 + 4 + 8 + 10 + 14 + 16 + 20 + 22 + 26 + 28 + 32 = 182
