# Giao diện chi tiết sản phẩm VIETTIEN (HTML5 + CSS3)

Đây là dự án giao diện tĩnh phục vụ bài tập. Không sử dụng backend, cơ sở dữ liệu, JavaScript hoặc thư viện giao diện.

## Cấu trúc

- `index.html`: cấu trúc nội dung trang.
- `style.css`: màu sắc, bố cục, thành phần và responsive.

## Cách chạy

1. Tải và giải nén thư mục dự án.
2. Mở `index.html` bằng Chrome, Edge, Firefox hoặc trình duyệt hiện đại.
3. Để thuận tiện khi chỉnh sửa, mở thư mục bằng Visual Studio Code. Có thể dùng tiện ích Live Server nếu đã cài, nhưng không bắt buộc.
4. Cần có kết nối Internet để tải ảnh minh họa từ Unsplash và font Be Vietnam Pro từ Google Fonts. Nếu không có mạng, thay các URL ảnh bằng ảnh cục bộ trong thư mục `images/` và dùng font hệ thống.

## Lưu ý

- Đây là mockup minh họa, không phải website chính thức của Việt Tiến.
- Giá, mã sản phẩm, đánh giá, thông số size và chính sách trong trang là dữ liệu mẫu; cần xác minh và thay bằng dữ liệu chính thức trước khi sử dụng thực tế.
- Nút mua hàng, tăng/giảm số lượng, phóng to ảnh, menu và nút thêm nhanh chỉ minh họa giao diện, chưa có chức năng xử lý vì dự án không dùng JavaScript/backend.
- Lựa chọn màu/size dùng radio HTML nên có thể thay đổi trạng thái lựa chọn. Các mục chính sách dùng `details/summary` và có thể mở/đóng.

## Checklist kiểm tra

- [ ] Mở trang ở màn hình desktop (ví dụ 1366px): ảnh và thông tin sản phẩm nằm cạnh nhau.
- [ ] Kiểm tra tablet (ví dụ 800px): các cột vẫn đủ rộng, không đè lên nhau.
- [ ] Kiểm tra mobile (ví dụ 390px và 320px): nội dung xếp dọc, không có cuộn ngang toàn trang.
- [ ] Thử chọn màu và size; size XXL mẫu bị vô hiệu hóa.
- [ ] Mở/đóng các mục giao hàng, đổi trả và hỗ trợ.
- [ ] Dùng phím Tab để kiểm tra khả năng focus và trạng thái focus nhìn thấy được.
- [ ] Kiểm tra văn bản thay thế ảnh (alt), nhãn điều hướng và độ tương phản.
- [ ] Kiểm tra khi ảnh hoặc font bên ngoài không tải được.
- [ ] Thay toàn bộ giá, mã sản phẩm, bảng size và chính sách mẫu bằng thông tin đã xác minh.
- [ ] Nếu muốn nút mua hàng hoạt động thật, cần bổ sung JavaScript và hệ thống giỏ hàng/backend ở bước sau.


## Quy ước tổ chức code

- `index.html` được chia khu vực bằng chú thích: header, điều hướng, sản phẩm, mô tả, bảng size, chính sách, sản phẩm liên quan và footer.
- `style.css` được trình bày theo từng khai báo trên dòng riêng, kèm tiêu đề nhóm để dễ tìm và chỉnh sửa.
- Các giá trị giao diện và breakpoint được giữ nguyên; lần chỉnh sửa này tập trung vào khả năng đọc và bảo trì code.
