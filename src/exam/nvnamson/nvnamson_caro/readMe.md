# Kiểm Tra Kết Quả Bàn Cờ Caro

## Mô tả

Cho một bàn cờ caro hình vuông kích thước `n × n`, mỗi ô có thể là:

- `x` — đánh bởi Ti
- `o` — đánh bởi Teo
- `.` — ô chưa được đánh

Nhiệm vụ của bạn là xác định ai thắng cuộc:

- Nếu người chơi `x` (Ti) có một chuỗi 5 quân liên tiếp theo hàng ngang, hàng dọc hoặc đường chéo → in ra `Ti wins`
- Nếu người chơi `o` (Teo) có một chuỗi 5 quân liên tiếp tương tự → in ra `Teo wins`
- Nếu không có ai thắng → in ra `Not yet`

---

## Input

- Dòng đầu tiên chứa một số nguyên `n` (`5 ≤ n ≤ 20`) — kích thước bàn cờ.
- `n` dòng tiếp theo, mỗi dòng chứa `n` ký tự là một trong `x`, `o`, hoặc `.` — biểu diễn trạng thái của bàn cờ.

---

## Output

- In ra kết quả trò chơi:
  - `Ti wins` nếu người chơi `x` thắng
  - `Teo wins` nếu người chơi `o` thắng
  - `Not yet` nếu chưa có ai thắng

---

## Ví dụ

### Input

```
5
x.x..
xxox.
.oxxo
..oxo
...xx
```

### Output

```
Ti wins
```
