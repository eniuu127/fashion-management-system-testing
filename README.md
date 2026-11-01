# HỆ THỐNG QUẢN LÝ THỜI TRANG

**Software Testing Portfolio | Dự án học tập (2026)**

## Tổng quan hệ thống

Website quản lý thời trang sử dụng Java Spring Boot và MySQL; phục vụ khách hàng, nhân viên và quản trị viên, gồm các nghiệp vụ tài khoản, sản phẩm, giỏ hàng, đơn hàng và thanh toán. Repository này tập trung trình bày **tài liệu kiểm thử**, không thay thế kho mã nguồn phát triển hệ thống.

## Phạm vi và phương pháp kiểm thử

Theo báo cáo học phần *Đánh giá và kiểm định chất lượng phần mềm*, phạm vi kiểm thử trọng tâm gồm:

- **UC01 – Đăng ký:** thông tin hợp lệ, trùng email, dữ liệu trống, định dạng không hợp lệ.
- **UC02 – Đăng nhập:** xác thực tài khoản, mật khẩu sai, phiên đăng nhập và quyền truy cập.
- **UC05 – Giỏ hàng:** thêm/xóa sản phẩm, điều chỉnh số lượng, kiểm tra biến thể và tồn kho.

Phương pháp nhóm thực hành: Manual Testing, Unit Testing (JUnit 5, Mockito, JaCoCo), UI Automation (Selenium WebDriver), Performance Testing (Apache JMeter). Việc nêu các phương pháp này phản ánh báo cáo của **nhóm học phần**, không có nghĩa mọi kịch bản hay mã nguồn đều được đăng tại đây.

## Kết quả từ bảng Test Case Excel

| Kết quả | Số lượng |
|---|---:|
| Đạt | 140 |
| Không đạt | 15 |
| Chưa test | 22 |
| Không chạy | 0 |
| **Tổng** | **177** |

- **Tỷ lệ đạt / tổng số ca:** 140/177 ≈ **79,1%**.
- **Tỷ lệ đạt / số ca đã có kết luận Đạt hoặc Không đạt:** 140/155 ≈ **90,3%**.
- Những con số trên lấy từ phần thống kê của file Excel đã cung cấp; không phải phép kiểm thử mới được chạy trên GitHub.
- **15 trường hợp Không đạt không tự động tương ứng với 15 Bug Report độc lập.** Hiện chưa có hồ sơ lỗi riêng đã được xác minh.

## Cấu trúc tài liệu

- [01-Test-Plan](01-Test-Plan/): mô tả kế hoạch, mục tiêu và phạm vi kiểm thử.
- [02-Test-Cases](02-Test-Cases/): giới thiệu bảng Test Case Excel; chờ tải file bảng tính gốc.
- [03-Test-Results](03-Test-Results/): tổng hợp kết quả từ bảng Excel.

## Nguồn tài liệu và phạm vi đóng góp

Dựa trên bảng Test Case và báo cáo của hai nhóm học phần/đồ án liên quan tới cùng hệ thống. Thành quả phát triển, kiểm thử và các số liệu trong báo cáo có phần đóng góp của nhiều thành viên. Không quy toàn bộ công việc nhóm thành sản phẩm cá nhân.

**Lưu ý:** Chưa có ảnh minh chứng lỗi hoặc Bug Report riêng, nên không tạo dữ liệu giả. Tài liệu gốc chỉ nên công khai sau khi kiểm tra thông tin cá nhân và quyền chia sẻ.
