1.  Trò chơi của Shi-Ura

---

[Shishimaru](http://codefun.vn/profile.php?id=117) và
[Uramihsihs](http://codefun.vn/profile.php?id=29) đang chơi một trò chơi
trên bảng được chia thành a hàng và b cột. Khi trò chơi bắt đầu,
[Shishimaru](http://codefun.vn/profile.php?id=117) đặt hộp đựng thuốc ảo
trên một ô của bảng. Sau đó
[Uramihsihs](http://codefun.vn/profile.php?id=29) chọn một ô để ném vào
đó quả bom ảo và [Shishimaru](http://codefun.vn/profile.php?id=117) sẽ
trả lời nếu hộp thuốc của anh ta có nằm trong phạm vi ảnh hưởng của bom
hay không. Phạm vi của một quả bom với đường kính p được ném xuống khu
vực (r,s) là một hình vuông với cạnh song song với cạnh của bảng, có tâm
ở (r,s) và độ dài các cạnh bằng p.

Viết chương trình xác định số lượng ô mà hộp thuốc của
[Shishimaru](http://codefun.vn/profile.php?id=117) vẫn an toàn sau khi
một số quả bom đã được ném ra.

INPUT

Dòng thứ nhất chứa 3 số tự nhiên: 1 ≤ a, b, k ≤ 100 lần lượt là số hàng,
số cột và số quả bom được ném. Trong k dòng tiếp theo sẽ ghi các số
nguyên r, s, p, t mô tả quả bom được ném xuống khu vực ở hàng thứ r và
cột thứ s với đường kính 1 ≤ p ≤ 99, p lẻ, `t = 1` nếu hộp thuốc trong
phạm vi quả bom, không thì `t = 0`.

OUTPUT

In ra số lượng ô có thể đặt hộp thuốc

```
+---------------+---------+---------+---------+
| Sample Input  | 6 6 2   | 5 5 3   | 5 4 1   |
|               |         |         |         |
|               | 3 3 3 1 | 3 3 3 1 | 2 1 5 0 |
|               |         |         |         |
|               | 4 4 3 1 | 3 4 1 0 |         |
|               |         |         |         |
|               |         | 3 4 3 1 |         |
+===============+=========+=========+=========+
| Sample Output | 4       | 5       | 8       |
+---------------+---------+---------+---------+
```

1.  SPOJ

---

[Shishimaru](http://codefun.vn/profile.php?id=117) đang lo lắng về số
tiền hóa đơn điện thoại để lướt web trên Internet.

Một phút lướt trong khoảng thời gian **7:00-19:00** mất **10** cent, và
trong khoảng thời gian **giữa 19:00 và 07:00** mất **5** cents (giá là
như nhau cho tất cả các ngày trong tháng).

Thời điểm bắt đầu và kết thúc của một kết nối Internet luôn luôn được
làm tròn **đến phút (không phải giây),** và một kết nối kéo dài **tối đa
60 phút.**

Bạn có một danh sách các kết nối, viết một chương trình tính toán **tổng
số** tiền sử dụng Internet.

INPUT

Trong dòng đầu tiên ghi số lượng kết nối, 1 ≤ N ≤ 100. Mỗi dòng trong N
dòng sau mô tả một kết nối, trong các định dạng sau: HH: MM DD. với HH:
MM biểu thị giờ, phút bắt đầu của kết nối, và DD biểu thị khoảng thời
gian kết nối (đơn vị phút, tối đa 60). Giữa MM và DD có một dấu cách.
Nếu giờ hoặc phút bắt đầu là số một chữ số, thì có một **số không** ở
phía trước của con số đó. Thời gian được ký hiệu là từ 00:00 đến 23:59.

OUTPUT

In ra tổng số tiền (đơn vị cent).

```
+----------+----------+----------+----------+
| spoj.in  | 2        | 3        | 5        |
|          |          |          |          |
|          | 11:02 11 | 20:05 12 | 00:00 05 |
|          |          |          |          |
|          | 15:30 01 | 06:45 30 | 06:47 35 |
|          |          |          |          |
|          |          | 13:08 15 | 11:30 18 |
|          |          |          |          |
|          |          |          | 18:33 60 |
|          |          |          |          |
|          |          |          | 23:59 22 |
+==========+==========+==========+==========+
| spoj.out | 120      | 435      | 1035     |
+----------+----------+----------+----------+
```

3.  MO

---

[Shishimaru](http://codefun.vn/profile.php?id=117) và
[Uramihsihs](http://codefun.vn/profile.php?id=29) đang chơi MO
(mini-go). MO tương tự như trò GO của Trung Quốc cổ đại, nhưng đơn giản
hơn vì được chơi trên bảng một chiều gồm một dãy các ô vuông liên tiếp.
[Shishimaru](http://codefun.vn/profile.php?id=117) dùng quân trắng, và
được chơi trước. Slavko dùng quân đen, và anh chơi sau.

Ban đầu, tất cả các ô vuông đều trống.  Hai người luân phiên chơi và
trong mỗi bước, họ đặt một quân của mình trên bất kỳ ô vuông trống nào.

Nếu có chuỗi liên tiếp các quân của đối phương nằm giữa quân vừa đặt và
quân đặt trước đó cùng màu sắc, thì toàn bộ chuỗi quân của đối phương
bị loại bỏ.

Các ô vuông trên bàn được biểu thị bằng số từ 1 đến P, từ trái sang
phải. Viết chương trình tính toán số quân trắng và số quân đen trong
bảng trên khi kết thúc trận đấu.

INPUT

Dòng đầu tiên ghi hai số nguyên 1 ≤ P ≤ 100 và 1 ≤ N ≤ 1000, là số lượng
của ô vuông và tổng số bước đi chuyển của cả hai người chơi. Mỗi dòng
trong số N dòng tiếp theo ghi bước đi của Mirko và Slavko, từ lúc khởi
đầu tới khi kết thúc trò chơi.

OUTPUT

In ra số quân màu trắng và số quân màu đen khi trò chơi kết thúc.

```
+--------+-----+-----+-----+
| mo.in  | 4 4 | 5 6 | 6 8 |
|        |     |     |     |
|        | 2   | 1   | 1   |
|        |     |     |     |
|        | 3   | 4   | 2   |
|        |     |     |     |
|        | 4   | 5   | 5   |
|        |     |     |     |
|        | 3   | 2   | 3   |
|        |     |     |     |
|        |     | 3   | 4   |
|        |     |     |     |
|        |     | 2   | 6   |
|        |     |     |     |
|        |     |     | 2   |
|        |     |     |     |
|        |     |     | 3   |
+========+=====+=====+=====+
| mo.out | 2 1 | 3 1 | 2   |
+--------+-----+-----+-----+
```

---

---

[shishimaru](http://codefun.vn/profile.php?id=117)
[uramihsihs](http://codefun.vn/profile.php?id=29)
