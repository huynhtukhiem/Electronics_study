# Tổng hợp kiến thức về Biến Trở (Variable Resistor)

# Khái niệm
**Biến trở** (Variable Resistor) là linh kiện điện tử có **điện trở thay đổi được**. Nó cho phép **điều chỉnh dòng điện hoặc điện áp** trong mạch điện bằng cách xoay hoặc trượt con chạy (núm vặn). 

# Cấu tạo
Biến trở gồm 3 phần chính:
- **Hai chân cố định**: nối hai đầu của dải điện trở.
- **Một chân giữa (con chạy)**: trượt trên bề mặt điện trở để thay đổi giá trị.

# Phân loại biến trở

| **Loại biến trở** | **Ký hiệu** | **Đặc điểm** | **Ứng dụng** |
|:------------------:|:------------:|:-------------:|:-------------:|
| **Potentiometer (Chiết áp)** | 3 chân | Dùng làm bộ chia điện áp | Điều chỉnh âm lượng, độ sáng, cảm biến |
| **Rheostat** | 2 chân | Dùng điều chỉnh dòng qua tải | Điều khiển quạt, đèn công suất nhỏ |
| **Trim Pot (Biến trở tinh chỉnh)** | Nhỏ, có vít vặn | Hiệu chỉnh mạch, cố định sau khi chỉnh | Mạch cảm biến, đo lường, Arduino |

# Nguyên lý hoạt động
Khi **xoay trục biến trở**, con chạy di chuyển → thay đổi **độ dài phần điện trở** mà dòng điện đi qua → **thay đổi giá trị điện trở tổng thể**.

# Các giá trị thường gặp
| Giá trị danh định | Khoảng điều chỉnh | Ứng dụng phổ biến |
|:------------------:|:------------------:|:------------------:|
| **1KΩ** | 0 → 1KΩ | Điều chỉnh dòng lớn, đèn LED |
| **10KΩ** | 0 → 10KΩ | Mạch cảm biến, chia áp, tín hiệu analog |
| **100KΩ** | 0 → 100KΩ | Mạch đo ADC, mạch logic, tín hiệu nhỏ |
| **1MΩ** | 0 → 1MΩ | Mạch khuếch đại, lọc tín hiệu nhỏ |

# Cách chọn biến trở phù hợp
| Ứng dụng | Biến trở đề nghị | Lý do |
|:---------:|:----------------:|:------:|
| Điều chỉnh sáng LED | 1K – 10K | Dòng vài mA, không quá cao |
| Cảm biến hoặc ADC (Arduino, ESP32) | 10K – 50K | Dòng nhỏ, ổn định tín hiệu |
| Mạch âm thanh | 10K – 100K log | Phù hợp với mạch analog |
| Mạch công suất (motor) | < 1K Rheostat | Dòng lớn, cần công suất cao |

# Ứng dụng thực tế
- Điều chỉnh **độ sáng LED**, **âm lượng loa**, **tốc độ quạt**.  
- Hiệu chỉnh **giá trị cảm biến** (ánh sáng, nhiệt độ, độ ẩm).  
- Tạo **bộ chia áp** trong mạch đo điện áp.  
- Dùng trong **mạch Arduino / ESP32** để nhập tín hiệu analog.


