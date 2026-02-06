# Mạch hiển thị MKE-M08 LCD2004 I2C Module

## Giới thiệu sản phẩm
MKE-M08 LCD2004 I2C Module là mạch hiển thị ký tự sử dụng màn hình LCD2004, có khả năng hiển thị 4 dòng, mỗi dòng 20 ký tự, phù hợp để hiển thị các thông tin cơ bản như trạng thái hệ thống, giá trị cảm biến, menu cài đặt hoặc thông báo người dùng. Mạch được tích hợp sẵn bộ chuyển đổi giao tiếp I2C, giúp việc kết nối với mạch điều khiển trở nên đơn giản và gọn gàng, chỉ cần 2 chân giao tiếp I2C là SDA (Data) và SCL (Clock) giúp tiết kiệm đáng kể số lượng chân I/O, rất thích hợp cho các hệ thống sử dụng nhiều cảm biến hoặc thiết bị ngoại vi.

Mạch hiển thị MKE-M08 LCD2004 I2C Module hỗ trợ điện áp điều khiển 3.3V và 5VDC, cho phép kết nối trực tiếp và an toàn với các bo mạch điều khiển phổ biến như Arduino, Raspberry Pi, Jetson Nano, Micro:bit và nhiều nền tảng khác. Sản phẩm đi kèm cáp kết nối 4P XH2.54 – Dupont, đảm bảo kết nối chắc chắn, ổn định và thuận tiện trong quá trình lắp đặt và sử dụng.

## Thông số kỹ thuật
- Điện áp hoạt động: 5VDC
- Điện áp giao tiếp: TTL 3.3VDC/5VDC
- Chuẩn giao tiếp: Digital I2C
- Các chân giao tiếp: SDA (Serial Data) / SCL (Serial Clock)
- Loại LCD: LCD2004 (4 dòng, mỗi dòng 20 ký tự)
- Tích hợp sẵn bộ chuyển đổi và trở kéo cho giao tiếp I2C.
- Tích hợp biến trở chỉnh độ tương phản.
- Tích hợp nút nhấn cấu hình chức năng và địa chỉ I2C.
- Khả năng tương thích:
  - Arduino
  - Raspberry Pi
  - Jetson Nano
  - Micro:bit
  - Và các board điều khiển 3.3/5VDC khác
- Thiết kế mạch:
  - Ổn định, chống nhiễu
  - Phù hợp cho ứng dụng học tập và thực tế
- Đi kèm cáp kết nối: 4P XH2.54–Dupont

## Các chân tín hiệu
<table><thead>
  <tr>
    <th>MKE-M08</th>
    <th>Ghi chú</th>
  </tr></thead>
<tbody>
  <tr>
    <td>GND</td>
    <td>Chân cấp nguồn âm 0VDC</td>
  </tr>
  <tr>
    <td>5V</td>
    <td>Chân cấp nguồn dương 5VDC</td>
  </tr>
  <tr>
    <td>SDA</td>
    <td>Chân tín hiệu I2C Serial Data</td>
  </tr>
  <tr>
    <td>SCL</td>
    <td>Chân tín hiệu I2C Serial Clock</td>
  </tr>
  <tr>
    <td>SETUP</td>
    <td>Nút nhấn cấu hình chức năng và địa chỉ I2C</td>
  </tr>
  <tr>
    <td>CONTRAST</td>
    <td>Biến trở chỉnh độ tương phản của màn hình</td>
  </tr>
</tbody>
</table>

## Hướng dẫn sử dụng
### Hướng dẫn kết nối
- Cấp nguồn 5VDC cho mạch qua hai chân GND và 5V.
- Kết nối chân SCL của Module với chân I2C Clock xủa mạch điều khiển.
- Kết nối chân SDA của Module với chân I2C Data của mạch điều khiển.

### Hướng dẫn sử dụng với Arduino Uno / Vietduino Uno / ESP32
- Trong **Tools / Library Manager**, tìm và cài đặt bộ thư viện tổng hợp **"MKE_ONE" by MakerEdu.vn**
- Mở chương trình mẫu **"MKE_M08_LCD2004_I2C_Serial_XXX"** tại **File / Examples / MAKEREDU / Module / MKE_M08_LCD2004_I2C**
- Cấu hình board mạch tương ứng là **Arduino Uno / ESP32**, chọn đúng cổng **COM Port** của mạch và nhấn **Upload** để nạp chương trình.
- Cấp nguồn 5VDC cho mạch, kết nối chân SDA và SCL của Module với chân điều khiển được khai báo trong chương trình.
- Xem kết quả mạch hoạt động theo chương trình đã nạp.

### Hướng dẫn lập trình với Micro:bit (kéo thả khối)

- Khởi động [Microsoft MakeCode](https://makecode.microbit.org/) và **Import** chương trình theo đường link sau: `https://github.com/makereduvn/mke_m08_lcd2004_i2c_microbit/`
- Kết nối mạch Micro:bit và **Download** chương trình.
- Cấp nguồn 5VDC cho mạch, kết nối chân SDA và SCL của Module với chân điều khiển được khai báo trong chương trình.
- Xem kết quả mạch hoạt động theo chương trình đã nạp.

Nếu bắt đầu tự án mới cần cài đặt Extension **MKE_ONE_MICROBIT** trên [Microsoft MakeCode](https://makecode.microbit.org/) theo [hướng dẫn tại đây](https://github.com/makereduvn/MKE_ONE_MICROBIT). Sau khi cài đặt thành công, các khối lệnh của Extension **MKE_ONE_MICROBIT** sẽ xuất hiện trong danh sách block và sẵn sàng để sử dụng.

## Kích thước sản phẩm
![MKE-08 LCD2004 I2C](/extras/MKE-M08_1.jpg)

## Hình ảnh sản phẩm
![MKE-08 LCD2004 I2C](/extras/MKE-M08_2.png)
![MKE-08 LCD2004 I2C](/extras/MKE-M08_3.png)
