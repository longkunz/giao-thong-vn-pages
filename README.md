# Giao Thong VN Live - Trang Công Khai Tài Liệu Pháp Lý & Điều Khoản

Kho lưu trữ công khai chứa tài liệu điều khoản sử dụng, chính sách quyền riêng tư và tài liệu hỗ trợ người dùng của ứng dụng **Giao Thông VN Live**, được xuất bản tự động qua GitHub Pages.

## 1. Địa chỉ truy cập chính thức (GitHub Pages)

- **Trang chủ / Điều khoản dịch vụ:** [https://longkunz.github.io/giao-thong-vn-pages/](https://longkunz.github.io/giao-thong-vn-pages/)
- **Đường dẫn trực tiếp Điều khoản:** [https://longkunz.github.io/giao-thong-vn-pages/terms.html](https://longkunz.github.io/giao-thong-vn-pages/terms.html)
- **Liên hệ & Góp ý:** [https://longkunz.github.io/giao-thong-vn-pages/contact.html](https://longkunz.github.io/giao-thong-vn-pages/contact.html)

## 2. Thông số kỹ thuật

- **Mã định danh nội dung hiện tại (`content-id`):** `giao-thong-vn-terms-v1-draft`
- **Ngày dự thảo:** `2026-11-07`
- **Giao thức:** HTTPS bắt buộc
- **Khả năng tương thích:** Tối ưu hóa hiển thị di động (mobile-friendly), hỗ trợ Dark Mode tự động theo thiết bị, tương thích WebView trên iOS và Android.

## 3. Quy trình cập nhật nội dung (Update & Publish Workflow)

1. **Chỉnh sửa nội dung:**
   - Bản gốc nằm trong repo ứng dụng (`docs/legal/*.md`, `docs/legal/pages/*.html`); publish nguyên văn `privacy.html`, `terms.html`, `index.html` sang repo này (`index.html` trùng khớp `terms.html`).
   - Nếu thay đổi nội dung có tính chất quan trọng, cập nhật thuộc tính `data-content-id` (ví dụ: `giao-thong-vn-terms-v2`) và ngày hiệu lực `data-effective-date`.
2. **Kiểm thử trước khi commit:**
   - Mở file HTML trên trình duyệt hoặc công cụ mô phỏng thiết bị di động để kiểm tra bố cục và khả năng đọc.
3. **Commit & Push:**
   - Đẩy commit lên nhánh `main`. GitHub Pages sẽ tự động kích hoạt tiến trình triển khai trang tĩnh trong vòng 1-2 phút.
4. **Xác nhận phát hành:**
   - Kiểm tra HTTPS URL trên thiết bị thật hoặc kiểm tra mã phản hồi HTTP 200.

## 4. Trạng thái phát hành

Bản hiện tại là **bản chính thức phiên bản 2.0**, hiệu lực từ ngày 15/11/2026, thay thế phiên bản 1.0 (hiệu lực 08/11/2026). Ứng dụng yêu cầu người dùng chấp thuận lại khi mã định danh nội dung thay đổi.
