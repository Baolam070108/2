# HƯỚNG DẪN CÀI ĐẶT CẢM BIẾN ĐỘ ẨM## Heading
## Trang trại Lan

### 1. Mục đích
Cảm biến độ ẩm giúp kiểm tra độ ẩm của đất.
Khi đất khô, hệ thống sẽ bật máy bơm để tưới nước.

### 2. Cài đặt thiết bị
Mở Terminal và nhập lệnh sau để kiểm tra phiên bản Python:

```bash
python --version
```

Cài đặt thư viện điều khiển thiết bị:

```bash
pip install gpiozero
```

### 3. Code điều khiển máy bơm

```python
# Đọc độ ẩm đất và điều khiển máy bơm
do_am = 25
nguong_do_am = 30

if do_am < nguong_do_am:
    print("Đất khô, bật máy bơm")
else:
    print("Đất đủ ẩm, tắt máy bơm")
```

Trong đó:
- `do_am`: Độ ẩm hiện tại của đất.
- `nguong_do_am`: Ngưỡng độ ẩm cần thiết.
- `print()`: Hiển thị thông báo trên màn hình.

*Lưu ý:* Đây là code mô phỏng. Muốn điều khiển máy bơm thật, cần kết nối cảm biến và mạch điều khiển phù hợp.

### 4. Bảng so sánh cảm biến

| Tiêu chí | Cảm biến cũ | Cảm biến mới |
|---|---|---|
| Giá thành | Thấp | Cao hơn |
| Độ bền | Dễ bị ăn mòn | Bền hơn |
| Độ chính xác | Trung bình | Tốt hơn |
| Bảo trì | Thường xuyên | Ít hơn |

### 5. Danh sách kiểm tra thiết bị

- [ ] Kiểm tra cảm biến độ ẩm.
- [ ] Kiểm tra dây kết nối.
- [ ] Kiểm tra nguồn điện.
- [ ] Cài đặt Python và thư viện cần thiết.
- [ ] Chạy thử chương trình.
- [ ] Kiểm tra hoạt động của máy bơm.

### 6. Lưu ý về ký tự đặc biệt

Dùng dấu `\` để hiển thị ký tự Markdown mà không bị định dạng.

Ví dụ:
- `\*` hiển thị ký tự \*
- `\#` hiển thị ký tự \#

### 7. Kết luận

Thực hiện đúng các bước trên giúp việc lắp đặt,
kiểm tra và sử dụng cảm biến độ ẩm dễ dàng hơn.

