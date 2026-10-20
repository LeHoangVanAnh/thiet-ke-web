# NHẬT KÝ PROMPT ENGINEERING (VIBE CODING LOG)
- **Họ và tên:** [Lê Hoàng Vân Anh]
- **MSSV:** [125000727]
- **Tên đề tài Website:** Website Tiệm Bánh Ngọt Chuẩn Âu - Lê Hoàng Vân Anh
- **Công cụ AI đã sử dụng:** Gemini (AI Collaborator)

## 1. Yêu cầu ban đầu (System/Initial Prompt)
> *Ghi lại prompt tổng quan ban đầu bạn dùng để khởi tạo khung website.*
- **Prompt:** "tạo code trang web bánh ngọt chuẩn Âu với tên trang web Lê Hoàng Vân Anh với tone màu xanh dương pastle và trắng, có nút chỉnh sửa màu nền, nút để chuyển trang khác mượt mà có trang chủ, giỏ hàng, thông tin , sản phẩm, liên hệ, đánh giá"

## 2. Quá trình tinh chỉnh & Giải quyết sự cố (Iteration Iterations)

### Lần 1: Dựng khung Website, Tone màu pastel & Hiệu ứng chuyển trang
- **Prompt đã dùng:** Yêu cầu khởi tạo ban đầu (như mục 1).
- **Kết quả AI tạo ra:** AI đã tạo một file HTML hoàn chỉnh với cấu trúc CSS Variables định nghĩa màu xanh dương pastel và trắng, tích hợp sẵn nút đổi màu nền (`toggleTheme`), hiệu ứng chuyển trang mượt mà bằng CSS transitions giữa 6 trang (Trang chủ, Sản phẩm, Giỏ hàng, Thông tin, Đánh giá, Liên hệ) cùng giao diện responsive.
- **Nhận xét & Tinh chỉnh của SV:** Cấu trúc ban đầu hoạt động rất mượt mà. Tuy nhiên, phần giỏ hàng mới chỉ hiển thị danh sách tĩnh đơn giản chưa có tính năng nhập thông tin người nhận để hoàn tất đơn hàng.

### Lần 2: Bổ sung Form thông tin khách hàng & Chức năng đặt hàng trực tuyến
- **Prompt đã dùng:** "tạo code trang web bánh ngọt chuẩn Âu với tên trang web Lê Hoàng Vân Anh với tone màu xanh dương pastle và trắng, có nút chỉnh sửa màu trang, nút để chuyển trang khác mượt mà có trang chủ, giỏ hàng, thông tin , sản phẩm, liên hệ, đánh giá,điền thông tin khách hàng"
- **Kết quả AI tạo ra:** AI cập nhật lại trang Giỏ hàng thành dạng bố cục chia đôi (Grid layout): Một bên hiển thị bảng sản phẩm đã chọn và tổng tiền, một bên là Form điền thông tin khách hàng (Họ tên, Số điện thoại, Địa chỉ nhận bánh) cùng sự kiện JavaScript xử lý xác nhận đặt hàng thành công.
- **Nhận xét & Tinh chỉnh của SV:** AI đã bổ sung rất chính xác tính năng form điền thông tin khách hàng nằm trực tiếp trong trang giỏ hàng, giúp website có độ hoàn thiện cao giống như một trang e-commerce thực tế.

## 3. Đánh giá cá nhân về quá trình Vibe Coding
- **AI đã giúp bạn tiết kiệm thời gian ở phần nào nhất:** 
  - Tiết kiệm lượng lớn thời gian trong việc viết mã nguồn cấu trúc HTML/CSS toàn diện, xây dựng hệ thống biến đổi màu sắc (`CSS Variables`) linh hoạt và viết sẵn các hàm JavaScript xử lý logic chuyển trang mượt mà cùng quản lý giỏ hàng.
- **Bài học rút ra khi đặt câu hỏi (Prompt) cho AI trong thiết kế web:** 
  - Cần mô tả rõ ràng các tính năng tương tác phức tạp (như form nhập thông tin thanh toán, giỏ hàng động) ngay từ đầu hoặc đưa vào các bước tinh chỉnh cụ thể để AI hiểu đúng mô hình nghiệp vụ của trang web, từ đó đưa ra giải pháp thiết kế giao diện (UI/UX) tối ưu và chính xác nhất.