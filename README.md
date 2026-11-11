# Portfolio cá nhân — Nguyễn Ngọc Hoàng Châu

Website portfolio giới thiệu Nguyễn Ngọc Hoàng Châu, Senior Graphic Designer và Visual & Creative Designer tại TP. Hồ Chí Minh. Trang trình bày thông tin cá nhân, các dự án tiêu biểu, năng lực thiết kế và phương thức liên hệ.

## Nội dung

- **Giới thiệu:** Định hướng thiết kế và kinh nghiệm về nhận diện thương hiệu, key visual, truyền thông số, UI/UX và GenAI.
- **Dự án:** Bốn dự án được chọn về Brand Identity, Key Visual, UI/UX và GenAI.
- **Năng lực:** Các kỹ năng thiết kế cùng công cụ Adobe, Figma và Generative AI.
- **Liên hệ:** Email, điện thoại và biểu mẫu gửi lời nhắn.

## Tính năng

- Bố cục đáp ứng cho màn hình lớn và thiết bị di động.
- Con trỏ tùy chỉnh, hiệu ứng nghiêng và ánh sáng cho thẻ dự án trên thiết bị có chuột.
- Hiệu ứng âm thanh tùy chọn được tạo bằng Web Audio API.
- Hỗ trợ tùy chọn giảm chuyển động của hệ điều hành.
- Biểu mẫu liên hệ tạo email và mở ứng dụng email mặc định; website không gửi dữ liệu biểu mẫu lên máy chủ.

## Chạy website

Đây là website tĩnh, không cần cài đặt dependency hoặc build. Mở `index.html` trực tiếp bằng trình duyệt, hoặc chạy một HTTP server tĩnh trong thư mục dự án, ví dụ:

```bash
python3 -m http.server 8000
```

Sau đó truy cập <http://localhost:8000>.

## Công nghệ và tài nguyên

- HTML, CSS và JavaScript thuần; mã được đặt trong `index.html`.
- Google Fonts cung cấp Inter và Space Grotesk.
- Ảnh dự án được tải từ Unsplash.
- Cần kết nối Internet để tải font và hình ảnh từ các dịch vụ bên ngoài.

## Cấu trúc

```text
.
├── index.html   # Toàn bộ giao diện, kiểu dáng và tương tác
└── README.md    # Tài liệu dự án
```

## Liên kết

- Portfolio: <https://nnhchau91.wordpress.com/>
- Email: <mailto:nnhchau91@gmail.com>
- LinkedIn và Behance hiện liên kết tới trang chủ của từng dịch vụ; cập nhật URL hồ sơ cá nhân trong `index.html` khi có đường dẫn chính thức.