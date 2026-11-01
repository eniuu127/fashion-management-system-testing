# HỆ THỐNG QUẢN LÝ THỜI TRANG
**Software Testing Portfolio | Đồ án liên ngành Công nghệ thông tin 2026**

## 1. Giới thiệu dự án

Hệ thống quản lý thời trang là ứng dụng web thương mại điện tử B2C, hỗ trợ khách hàng mua sắm trực tuyến và hỗ trợ nhân viên, quản trị viên quản lý sản phẩm, biến thể, tồn kho, khuyến mãi và đơn hàng.

- **Công nghệ hệ thống:** Java Spring Boot, MySQL, HTML, CSS, JavaScript.
- **Phương thức thanh toán:** COD và PayOS.
- **Chức năng hỗ trợ:** Chatbot AI tìm kiếm và gợi ý sản phẩm.
- **Repository mã nguồn hệ thống:** [haiha74/DALN](https://github.com/haiha74/DALN).

Repository này giới thiệu **tài liệu phân tích và đặc tả yêu cầu phần mềm (SRS), kế hoạch kiểm thử và kết quả thực hành kiểm thử thủ công (Manual Testing)**. Mã nguồn hệ thống được lưu trữ riêng tại repository liên kết ở trên.

## 2. Phạm vi kiểm thử

Bộ kiểm thử gồm **177 Test Case thuộc 14 nhóm chức năng**, bao phủ các luồng nghiệp vụ chính:

- **Tài khoản:** Đăng ký, đăng nhập và quản lý phiên.
- **Mua sắm:** Danh mục, tìm kiếm, chi tiết sản phẩm, biến thể, giỏ hàng, voucher, đặt hàng và thanh toán.
- **Đơn hàng:** Trạng thái đơn hàng và đánh giá sản phẩm.
- **Quản trị:** Sản phẩm, biến thể, tồn kho và khuyến mãi.
- **Chức năng hỗ trợ:** Chatbot tìm kiếm sản phẩm, banner và giao diện.

Kiểm thử được thực hiện chủ yếu theo phương pháp **Manual Testing kết hợp Black-box Testing**, sử dụng các kỹ thuật **Equivalence Partitioning**, **Boundary Value Analysis** và **Scenario-based Testing**.

**Công cụ hỗ trợ:** Microsoft Excel, Google Chrome, Chrome DevTools và Postman.

## 3. Kết quả thực thi Test Case

| Trạng thái | Số lượng | Tỷ lệ trên tổng |
|---|---:|---:|
| Pass (Đạt) | 140 | 79,1% |
| Fail (Không đạt) | 15 | 8,5% |
| Not Tested (Chưa kiểm thử) | 22 | 12,4% |
| **Tổng** | **177** | **100%** |

- **Tỷ lệ thực thi:** 155/177 = **87,6%**.
- **Tỷ lệ Pass trên các Test Case đã thực thi:** 140/155 = **90,3%**.

Số liệu được tổng hợp từ bộ Test Case đã ghi nhận, không phải kết quả của một lần chạy kiểm thử mới. Các trường hợp Fail chưa được quy đổi thành số lượng Bug Report độc lập.

## 4. Tài liệu phân tích và kiểm thử

| Thư mục | Nội dung |
|---|---|
| [01-Requirement-Analysis](./01-Requirement-Analysis/) | Tài liệu SRS: yêu cầu chức năng, phi chức năng, đặc tả Use Case, biểu đồ trình tự và hoạt động. |
| [02-Test-Plan](./02-Test-Plan/) | Kế hoạch kiểm thử: mục tiêu, phạm vi, phương pháp, môi trường, tiêu chí và rủi ro. |
| [03-Test-Cases](./03-Test-Cases/) | Bộ 177 Test Case, dữ liệu kiểm thử và kết quả thực thi ở định dạng Excel/PDF. |

**Xem nhanh tài liệu:**

- [Đặc tả yêu cầu phần mềm (SRS – PDF)](./01-Requirement-Analysis/SRS_He_Thong_Quan_Ly_Va_Ban_Hang_Thoi_Trang.pdf)
- [Test Plan (PDF)](./02-Test-Plan/Test%20Plan.pdf)
- [Test Cases (Excel)](./03-Test-Cases/CV_TestCase_ĐALN.xlsx)
- [Test Cases (PDF)](./03-Test-Cases/CV_TestCase_ĐALN.pdf)
- [Mã nguồn hệ thống](https://github.com/haiha74/DALN)

## 5. Phạm vi đóng góp và lưu ý

Đây là dự án học tập có sự tham gia của nhiều thành viên. Repository này giới thiệu tài liệu phân tích yêu cầu, tài liệu kiểm thử và số liệu ghi nhận trong quá trình thực hành, **không khẳng định toàn bộ công việc phát triển hoặc kiểm thử là sản phẩm cá nhân**.

Các hoạt động kiểm thử đơn vị, kiểm thử tự động, hiệu năng và bảo mật chuyên sâu không nằm trong phạm vi của Test Plan thủ công được trình bày tại đây. Hiện chưa công bố Bug Report hoặc Evidence độc lập; các kết quả kiểm thử cần được hiểu trong phạm vi bộ Test Case hiện có.
