# Thực hành lắp mạch LED sáng bằng biến trở
Video: link

# Chuẩn bị:
  - LED đỏ/ xanh lá/ vàng
  - Biến trở volume
  - Testboard
  - VOM
  - Nguồn điện

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
    
