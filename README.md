Đây là code của thiết bị chỉ đường theo google maps dùng trên điện thoại androi. code được viết cho esp32 mini, sử dụng màn hình oled nhỏ gọn
 
Với thiết bị này thì cần một số phần cứng sau:

Esp32 mini c3 (có thể dùng esp32 khác cũng được. miễn là có bluetooth để kết nối với điện thoại)

Màn hình oled 0.96 inch (có thể sử dụng màn hình oled lớn hơn. đối với màn oled) có độ phân giải 124x64 thì không cần chỉnh code)

Dây điện để kết nối esp32 mini và màn hình (có thể dùng dây hàn trực tiếp hoặc dùng dây chân cắm cái - cái để kết nối và tháo ra khi muốn sử dụng vào dự án khác).

Thực hiện:  

Về phần cứng, mình sẽ kết nối màn hình với esp32 mini theo giao thức i2c. chân gnd kết nối với gnd, vdd kết nối với chân 3.3v của esp, chân sck và sda kết nối chân số 9 và 8 của esp32.

sau đó anh em tải chương trình về nạp vào esp 32 nữa là chạy được nhé,
