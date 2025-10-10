# Làm LED sáng đèn
Giả sử chúng ta có 1 nguồn điện, 1 đèn LED, điện trở, các linh kiện khác v.v => Bài toán: àm sao để đèn led sáng ổn định

# Nguyên lý hoạt động:
LED chỉ sáng (ổn định) khi có dòng điện đi qua đúng chiều (anode -> cathode), ngoài ra LED không tự hạn chế dòng nên cần điện trở hạn dòng để giữ cho dòng luôn nằm trong vùng an toàn làm cho LED sáng ổn định, không bị cháy hoặc hư hỏng.

# Sơ đồ nguyên lý:
[+ Nguồn] --> [điện trở] --> [anode (chân dài]>, [cathode (chân ngắn)] --> [- Nguồn hoặc GND]
- Chân anode nối điện trở
- Chân cathode nối cực âm nguồn hoặc nối đất

# Cách tính điện trở hạn dòng 
Như đã nói ở trên: LED không tự hạn chế dòng nên cần điện trở hạn dòng để giữ cho dòng luôn nằm trong vùng an toàn làm cho LED sáng ổn định, không bị cháy hoặc hư hỏng. 

*Nếu không có điện trở mà nối trực tiếp led với nguồn thì sẽ xảy ra hiện tượng cháy led*. 

Ta có công thức:        `R =  (V_nguồn - V_led)/I_led`

Trong đó: đối với từng loại led khác nhau sẽ có thông số khác nhau:

| **Loại LED** | **Màu ánh sáng** | **Điện áp rơi (Vf)** | **Dòng định mức (If)** | **Công suất xấp xỉ** | **Ứng dụng phổ biến** |
|:--------------|:----------------:|:--------------------:|:----------------------:|:---------------------:|:----------------------:|
| **LED đỏ**    | Đỏ               | 1.8 – 2.2 V          | 10 – 20 mA             | ~0.04 W               | Báo hiệu, hiển thị trạng thái, mạch test |
| **LED xanh lá** | Xanh lá cây      | 2.0 – 3.0 V          | 10 – 20 mA             | ~0.05 W               | Báo nguồn, tín hiệu OK, đèn trang trí |
| **LED trắng** | Trắng / Trắng lạnh | 3.0 – 3.5 V          | 15 – 25 mA             | ~0.07 W               | Chiếu sáng, đèn nền, IoT hiển thị |

**Ghi chú:**
- Dòng định mức thường là 20 mA, nhưng nên chạy khoảng 10–15 mA để LED bền hơn.
- LED công suất cao (1W, 3W, 5W, …) cần tản nhiệt và mạch ổn dòng riêng.
- Điện áp rơi tăng theo bước sóng ngắn hơn — LED xanh, trắng cần điện áp cao hơn LED đỏ.



