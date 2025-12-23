1️⃣ Cơ số là gì?

Cơ số (基数): số lượng ký tự dùng để biểu diễn số.

Trong FE hay ra 4 loại:

Cơ số  	Tên  	Ký hiệu	  Ví dụ
2	  Nhị phân	(2進数)	  1011
8  	Bát phân	(8進数)  	17
10	Thập phân	(10進数)  	11
16	Thập lục phân	(16進数)	B, 1F

👉 16 tiến có thêm chữ:
A=10, B=11, C=12, D=13, E=14, F=15


2️⃣ Nhị phân → Thập phân (2 → 10)
Cách làm

👉 Nhân từng bit với 2ⁿ rồi cộng lại

Ví dụ:

1011(2)
= 1×2³ + 0×2² + 1×2¹ + 1×2⁰
= 8 + 0 + 2 + 1
= 11(10)
📌 Thi FE rất hay ra dạng này


3️⃣ Thập phân → Nhị phân (10 → 2)
ÁP DỤNG ➡ Dạng: 8 – 4 – 2 – 1
✅ CÁCH 1 (TỐT NHẤT – KHÔNG CẦN THUỘC)

👉 Viết số hex thành tổng 8-4-2-1

Ví dụ: 9
9 = 8 + 1

8	4	2	1
1	0	0	1

➡ 1001

NẾU SỐ THẬP PHÂN LỚN CÓ THỂ DÙNG CÁCH 2: TỪ THẬP PHÂN → HEX → NHỊ PHÂN (siêu nhanh)
👉 FE ra rất nhiều câu có HEX

Bước:

  1️⃣ Đổi 10 → 16 (chia cho 16, rất ít bước)
  2️⃣ Mỗi 1 hex = 4 bit

Ví dụ: 156(10)
156 ÷ 16 = 9 dư 12 → C
9 ÷ 16 = 0 dư 9
→ 9C(16)
 N
Hex → nhị phân:
9  → 1001
C  → 1100 

➡ 10011100(2)

⏱ Cực nhanh – cực chuẩn FE


4️⃣ Nhị phân ↔ Bát phân (2 ↔ 8)

👉 3 bit = 1 chữ số bát phân
Nhị phân	Bát phân
  000      	0
  001	      1
  010	      2
  011	      3
  100	      4
  101	      5
  110	      6
  111	      7

Ví dụ:
  
  101011(2)
  → 101 | 011
  → 5   | 3
  → 53(8)


📌 Không cần tính toán – chỉ nhóm bit

5️⃣ Nhị phân ↔ Thập lục phân (2 ↔ 16)

👉 4 bit = 1 chữ số hex

Nhị phân	Hex
    0000	0
    1001	9
    1010	A
    1011	B
    1100	C
    1111	F

Ví dụ:
  
  10111100(2)
  → 1011 | 1100
  → B    | C
  → BC(16)


6️⃣ Thập lục phân → Thập phân (16 → 10)

👉 Nhân với 16ⁿ

Ví dụ:

  1F(16)
  = 1×16¹ + F×16⁰
  = 16 + 15
  = 31(10)



  3️⃣ TƯ DUY QUAN TRỌNG ĐỂ KHÔNG BỊ RỐI
Trường hợp	Cách dùng
HEX → 2	8421
2 → HEX	nhóm 4 bit
10 → 2 (số lớn)	bảng 2ⁿ
10 → 2 (thi FE)	đi vòng qua HEX

