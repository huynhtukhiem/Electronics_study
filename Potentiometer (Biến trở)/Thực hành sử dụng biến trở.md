# Thực hành lắp mạch LED sáng bằng biến trở
Video: link

# Chuẩn bị:
  - LED đỏ/ xanh lá/ vàng
  - Biến trở volume 10K
  - Testboard
  - VOM
  - Nguồn điện 3.8V

# Thực hành:
Bước 1: Tính toán điện trở hạn dòng

- Nguồn điện 3.8V
- Sử dụng led màu xanh lá cây => V_led = 2.2V; I_led = 20mA
=> R = (V_nguồn - V_led)/I_led = (3.8 - 2.2) / 20.10^-3 =  80 ôm
=> Vậy cần điều chỉnh biến trở về 80 ôm

Bước 2: Điều chỉnh biến trở
- Cắm que đen vào chân 1, que đỏ vào chân 2
- Điều chỉnh VOM sao cho R về 80

Trong trường hợp không thể điều chỉnh R về 80 được vì biến trở có giá trị quá lớn vd: 10k ôm => dùng điện trở song song
 - Mắc một điện trở R = 80 ôm song song với biến trở 10K ôm, ta có công thức R_song_song = (R1.R2)/(R1 + R2) = (80 x 10x10^3) / (80 + 10x10^3) = 79,37 ôm
 - Ngoài ra cũng có thể sử dụng R = 100 ôm nếu không có 80 ôm

 Bước 3: Sơ đồ đấu nối
 - Nối dây dương của nguồn vào chân 1 của biến trở.
 - Nối chân 2 của biến trở vào chân anode của LED
 - Chân cathode của LED nối với dây âm của nguồn
