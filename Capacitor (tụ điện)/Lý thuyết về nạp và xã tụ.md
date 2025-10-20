# Tích trữ và phóng điện
🧠 1. Nguyên lý hoạt động

Tụ điện gồm hai bản dẫn đặt song song, cách nhau bằng chất điện môi (air, giấy, gốm, nhựa, v.v.). Khi có hiệu điện thế (U) đặt vào hai bản, điện tích (+) tích trên bản dương và điện tích (−) tích trên bản âm → tụ tích năng lượng điện trường.

Công thức: Q = C x U 

Trong đó:
- Q: điện tích (Coulomb)
- C: điện dung của tụ (Farad)
- U: điện áp giữa hai bản tụ (Volt)

⚡ 2. Quá trình tích điện (Nạp tụ)

Khi nối tụ với nguồn điện (thông qua điện trở):
- Ban đầu, điện áp trên tụ 𝑈c = 0.
- Dòng điện chạy vào tụ làm điện áp tăng dần
- Khi tụ đầy, Uc = U_nguồn => dòng điện giảm dần về 0
  Phương trình điện áp khi tụ nạp: `Uc(t) = U_nguồn x (1-e^(-t/RxC)`

🔌 3. Quá trình phóng điện (Xả tụ)

Khi ngắt nguồn, tụ sẽ phóng điện qua điện trở hoặc tải nối vào. Điện áp trên tụ giảm dần theo thời gian: `Uc(t)) = U_ban_đầu x e ^ -t/RC`

 Dòng điện lúc này chạy ngược chiều so với lúc nạp, cho đến khi điện áp của tụ bằng 0

⏱️ 3. Các công thức quan trọng:
Khi tụ có điện dung C nạp hoặc xã qua điện trở R, tốc độ thay đổi điện áp phụ thuộc vào tíc  RxC, ta gọi là hằng số thời gian (τ – Tau)

τ = R x C, đơn vị giây

Trong quá trình nạp: 

Uc(t) = U_nguồn x (1 - e^(-t/RC))

Điện áp sẽ tăng từ 0 -> U_nguồn

|Thời gian|Điện áp trên tụ|
|:--------|:--------------|
|t = 0|0%|
|t = 1τ|63% U_nguồn|
|t = 2τ|86% U_nguồn|
|t = 3τ|95% U_nguồn|
|t = 4τ|98% U nguồn|
|t = 5τ|99,3% U_nguồn|
=> Thời gian nạp đầy khoảng 5τ 

Bằng cách chứng trinh tương tụ với phương trình tụ xã: Uc(t) = Uban_đầu x e^(-t/RC)
ta cũng có thời gian tụ xã là 5τ
