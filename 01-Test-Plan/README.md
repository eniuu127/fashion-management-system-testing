# Kế hoạch kiểm thử – Hệ thống quản lý thời trang

**Nguồn:** Báo cáo học phần Đánh giá và Kiểm định chất lượng phần mềm, chương III (2026).

## Phạm vi kiểm thử trọng tâm

| Use Case | Các nội dung kiểm thử |
|---|---|
| UC01 – Đăng ký | Đăng ký hợp lệ; email trùng/sai định dạng; dữ liệu trống; mật khẩu không hợp lệ |
| UC02 – Đăng nhập | Tài khoản hợp lệ/không tồn tại; mật khẩu sai; quản lý phiên; kiểm soát quyền |
| UC05 – Quản lý giỏ hàng | Xem/thêm/xóa hàng; cập nhật số lượng; kiểm tra biến thể và tồn kho |

**Phương pháp:** kiểm thử hộp đen thủ công; Unit Test bằng JUnit 5/Mockito và báo cáo độ phủ JaCoCo; tự động hóa giao diện bằng Selenium; hiệu năng API bằng JMeter.

**Ngoài phạm vi chuyên sâu của báo cáo kiểm thử:** thanh toán PayOS, quản lý kho, sản phẩm, khuyến mãi, thống kê doanh thu và các nghiệp vụ khác của hệ thống.

Đây là bản giới thiệu trích ý từ tài liệu nhóm, chưa phải file Test Plan nguyên bản đã xử lý thông tin cá nhân.
