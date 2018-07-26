1.  XẾP HÀNG

---

Nam đang đứng trong 1 hàng n người (vị trí từ 1 → n), nhưng anh ấy không
biết chính xác vị trí hiện tại của mình. Tuy nhiên anh ấy biết rằng có
ít nhất a người đứng trước anh ấy và nhiều nhất b người đứng sau anh ấy
(0 \< a, b \< n \< 100). Có bao nhiêu khả năng về vị trí của anh ấy
trong hàng.

INPUT

Gồm nhiều test, mỗi test nằm trên một dòng, gồm 3 số n, a và b

OUTPUT

Với mỗi test, in ra trên một dòng số khả năng có thể có về vị trí của
Nam trong hàng

```
+--------------+---------------+
| Sample Input | Sample Output |
+==============+===============+
| 6 3 4        | 3             |
|              |               |
| 12 2 4       | 5             |
+--------------+---------------+
```

2.  TỔNG BÌNH PHƯƠNG

---

Nhập vào số n ≤ 10000. Tính tổng các chữ số của ![n^2^](http://www.sciweavers.org/tex2img.php?eq=n%5E2%5E&bc=White&fc=Black&im=jpg&fs=12&ff=arev&edit=0).

INPUT

Gồm nhiều test, mỗi test nằm trên một dòng ghi số n

OUTPUT

Tổng các chữ số của ![n^2^](http://www.sciweavers.org/tex2img.php?eq=n%5E2%5E&bc=White&fc=Black&im=jpg&fs=12&ff=arev&edit=0).

```
+--------------+---------------+
| Sample Input | Sample Output |
+==============+===============+
| 4            | 7             |
|              |               |
| 9            | 9             |
+--------------+---------------+
```

3.  ĐẾM Ô

---

Cho bảng số kích thước N x N. Biết rằng ô ở vị trí hàng i, cột j (i, j)
có giá trị là `i * j`. Các hàng và cột được đánh số bắt đầu từ 1.

Cho số nguyên dương x. Đếm số ô trong bảng có giá trị là x.

INPUT

Gồm nhiều test, mỗi test nằm trên một dòng gồm 2 số N và x

OUTPUT

Với mỗi test, in ra trên một dòng số ô trong bảng có giá trị là x

```
+--------------+---------------+
| Sample Input | Sample Output |
+==============+===============+
| 10 5         | 2             |
|              |               |
| 3 4          | 1             |
+--------------+---------------+
```

4.  CẮT GHÉP

---

Hoàng muốn viết một xâu ký tự bằng cách cắt và nối các ký tự từ tiêu đề
của 1 bài báo. Các khoảng trắng thì không cần cắt, ký tự viết thường và
viết hoa là khác nhau. Cho xâu tiêu đề s1 ( độ dài ≤ 400) và xâu cần
viết s2 (độ dài ≤ 400). Hoàng có viết được xâu s2 bằng cách chỉ dùng các
ký tự từ xâu s1 hay không ??

INPUT

Gồm nhiều test, mỗi test nằm trên 2 dòng, dòng 1: ghi xâu s1, dòng 2 ghi
xâu s2. Mỗi xâu có không quá 10000 ký tự.

OUTPUT

Với mỗi test, in ra trên một dòng YES nếu từ xâu s1 có ghép để tạo thành
xâu s2. In ra NO nếu không thể

```
+------------------------------------+---------------+
| Sample Input                       | Sample Output |
+====================================+===============+
| hom nay My bat dau khong kich Irac | YES           |
|                                    |               |
| kich cau                           | NO            |
|                                    |               |
| aaa aa                             |               |
|                                    |               |
| bbb bb                             |               |
+------------------------------------+---------------+
```

5.  NGÀY NÀO

---

Nhập vào tháng năm bất kì. Cho biết tháng đó có bao nhiêu ngày?

INPUT

Gồm nhiều test, mỗi test nằm trên một dòng và ghi 2 số: tháng và năm. Dữ
liệu đảm bảo hợp lệ

OUTPUT

Với mỗi test, in ra trên một dòng số ngày có trong tháng đó

```
+--------------+---------------+
| Sample Input | Sample Output |
+==============+===============+
| 12 2015      | 31            |
|              |               |
| 2 2015       | 28            |
+--------------+---------------+
```

6.  PHÊ THƠ

---

Nam là một nhà phê bình thơ "lập dị". Theo đánh giá của Nam, một khổ thơ
( 4 dòng ) chỉ được xem là đúng chuẩn nếu mỗi dòng thơ lần lượt có chính
xác 4, 5, 6, 7 ký tự là nguyên âm ( nguyên âm là 1 trong các ký tự `a`,
`e`, `i`, `o`, `u` -- không phân biệt in hoa hay in thường).

Nhập vào 1 đoạn thơ 4 dòng. Kiểm tra xem đoạn thơ có thỏa mãn yêu cầu
của Nam hay không?

INPUT

Gồm nhiều test, mỗi test gồm 4 dòng thơ. Các test cách nhau một dòng
trống.

OUTPUT

Với mỗi test, in ra trên một dòng YES nếu Đoạn thơ có thỏa mãn yêu cầu
hoặc NO nếu ngược lại

```
+--------------------------+---------------+
| Sample Input             | Sample Output |
+==========================+===============+
| Dau tuan                 | YES           |
|                          |               |
| Em di hoc that som       |               |
|                          |               |
| Gap thay co gap ban be   |               |
|                          |               |
| Em thay long minh vui la |               |
+--------------------------+---------------+
```

7.  SỐ BỰ

---

Cho dãy A gồm n số tự nhiên (2 ≤ n ≤ 100). Ta định nghĩa 1 bước chuyển
đổi là việc chuyển 1 đơn vị từ 1 trong các số ở vị trí từ 2 đến n sang
số ở vị trí đầu tiên của dãy. Cần thực hiện ít nhất bao nhiêu bước
chuyển đổi để sau khi chuyển số ở vị trí đầu tiên là số lớn nhất "thực
sự" trong dãy ( `A[1] > A[i]` mọi `i = 2...n`).

INPUT

Gồm nhiều test, mỗi test gồm 2 dòng : dòng 1 -- số n, dòng 2 -- dãy n số

OUTPUT

Với mỗi test, in ra trên một dòng số bước chuyển đổi

```
+--------------+---------------+
| Sample Input | Sample Output |
+==============+===============+
| 1            | 0             |
|              |               |
| 1            | 1             |
|              |               |
| 2            |               |
|              |               |
| 2 3          |               |
+--------------+---------------+
```
