# Đếm Số Cặp Thỏa Mãn `(a + b) % 3 == 0`

## Mô tả

Cho một mảng gồm `n` số nguyên `a[1], a[2], ..., a[n]`, hãy đếm số lượng cặp chỉ số `(i, j)` sao cho:

- `1 ≤ i < j ≤ n`
- `(a[i] + a[j]) % 3 == 0`

---

## Input

- Dòng đầu tiên chứa một số nguyên `n` (`1 ≤ n ≤ 10^5`) — số phần tử của mảng.
- Dòng tiếp theo chứa `n` số nguyên `a[i]` (`1 ≤ a[i] ≤ 10^9`) — các phần tử của mảng.

---

## Output

- In ra một số nguyên — số cặp `(i, j)` thỏa mãn điều kiện đã cho.

---

## Ví dụ

### Input

```
5
1 2 3 4 5
```

### Output

```
4
```
