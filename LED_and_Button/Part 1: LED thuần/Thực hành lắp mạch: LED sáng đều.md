# LED sáng đều
Link: gsafdsaf

# Chuẩn bị:
- 1 LED đỏ
- 1 nguồn 3.7V
- điện trở hoặc biến trở
- VOM hoặc DNM
- Dây dẫn, testboard, 

# Thực hành:
- Tính điện trở hạn mức cho LED đỏ biết LED đỏ có:
   - V_led = 1.8V hoặc 2.2V => chọn V_led = 2V
   - I_led = 10mA hoặc 20mA => chọn I_led = 15mA

  Ta có công thức: R = V_nguồn - V_led / I_led = (3.7 - 2)/15.10^-3 = 113 ôm

  => Cần chọn điện trở hoặc điều chỉnh biến trở có giá trị 113 ôm, hoặc trong khoảng từ 100 -> 120 ôm

# Sơ đồ đấu nối:
  - Nối cực + của nguồn vào một đầu điện trở, đầu còn lại nối chân anode của LED (chân dài). Nếu dùng biến trở thì nối cực + của nguồn vào chân 1, chân 2 nối với anode của LED
  - Chân còn lại (cathode, chân ngắn) nối với cực - của nguồn
