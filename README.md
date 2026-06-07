# 🖨️ Anh Vinh Co. – Website

Website giới thiệu công ty **Công ty TNHH Dịch vụ và Thương mại Anh Vinh**  
Chuyên chế bản dịch vụ ngành in: CTP Offset và CTF (in lưới, in flexo).

---

## 📁 Cấu trúc thư mục

```
anhvinh-website/
├── index.html          ← Trang chủ chính (song ngữ Việt/Anh)
├── css/
│   └── style.css       ← Toàn bộ CSS (responsive, brand colors)
├── assets/
│   └── logo.png        ← Logo công ty
└── README.md           ← Hướng dẫn này
```

---

## 🚀 Hướng dẫn Upload lên GitHub Pages

### Bước 1: Tạo tài khoản GitHub (nếu chưa có)
1. Truy cập [github.com](https://github.com)
2. Nhấn **Sign up** và đăng ký tài khoản miễn phí

---

### Bước 2: Tạo Repository mới
1. Sau khi đăng nhập, nhấn dấu **`+`** ở góc trên phải → **New repository**
2. Điền thông tin:
   - **Repository name:** `anhvinh-website` _(hoặc tên bất kỳ)_
   - **Description:** Website công ty Anh Vinh (tùy chọn)
   - Chọn **Public** _(bắt buộc để dùng GitHub Pages miễn phí)_
   - ✅ Tick **Add a README file**
3. Nhấn **Create repository**

---

### Bước 3: Upload files lên GitHub

**Cách A – Upload trực tiếp qua trình duyệt (đơn giản nhất):**

1. Vào repository vừa tạo
2. Nhấn **Add file** → **Upload files**
3. Kéo thả toàn bộ thư mục `anhvinh-website` vào ô upload
   > ⚠️ Phải upload cả **thư mục con** `css/` và `assets/` đúng cấu trúc
4. Cuộn xuống → nhấn **Commit changes**

**Cách B – Dùng Git (nếu có Git cài sẵn):**

```bash
# Clone repository về máy
git clone https://github.com/TEN_CUA_BAN/anhvinh-website.git

# Copy toàn bộ files vào thư mục vừa clone
# Sau đó:
cd anhvinh-website
git add .
git commit -m "Initial website upload"
git push origin main
```

---

### Bước 4: Bật GitHub Pages

1. Vào repository → tab **Settings** (bánh răng)
2. Ở menu trái, tìm mục **Pages**
3. Trong **Source**, chọn:
   - Branch: **`main`**
   - Folder: **`/ (root)`**
4. Nhấn **Save**
5. Chờ **1–3 phút**, GitHub sẽ hiển thị link website:
   ```
   https://TEN_CUA_BAN.github.io/anhvinh-website/
   ```

---

### Bước 5: Truy cập website

Sau khi bật Pages, truy cập địa chỉ:
```
https://TEN_CUA_BAN.github.io/anhvinh-website/
```
_(Thay `TEN_CUA_BAN` bằng username GitHub của bạn)_

✅ Website đã online và **hoàn toàn miễn phí**!

---

## 🛠️ Cách chỉnh sửa nội dung

### Thay đổi thông tin liên hệ:
Mở file `index.html`, tìm và sửa các phần:
- Số điện thoại: tìm `082.251.2242`, `083.255.8572`, `0916.447.199`
- Email: tìm `anhvinhhp34@gmail.com`
- Link Zalo: tìm `https://zalo.me/0822512242`

### Thay đổi màu sắc:
Mở file `css/style.css`, tìm phần `:root` ở đầu file:
```css
:root {
  --red:  #DC143C;    /* Màu đỏ thương hiệu */
  --blue: #003DA5;    /* Màu xanh thương hiệu */
}
```

### Thêm ảnh:
Đặt ảnh vào thư mục `assets/` rồi tham chiếu trong HTML:
```html
<img src="assets/ten-anh.jpg" alt="Mô tả ảnh" />
```

---

## 🌐 Tính năng của website

| Tính năng | Chi tiết |
|-----------|----------|
| 🌐 Song ngữ | Tiếng Việt / English, lưu lựa chọn |
| 📱 Responsive | Mobile, tablet, desktop |
| 🎨 Brand colors | Đỏ #DC143C + Xanh #003DA5 |
| ⚡ Animation | Fade-up khi scroll, smooth scroll |
| 📧 Form liên hệ | Mở email client với nội dung form điền sẵn |
| 🗺️ Google Maps | Nhúng bản đồ tại trang liên hệ |
| 🔝 Scroll to top | Nút cuộn lên đầu trang |
| 🔍 SEO cơ bản | Meta tags, semantic HTML |

---

## 📞 Thông tin công ty

- **Tên:** Công ty TNHH Dịch vụ và Thương mại Anh Vinh
- **ĐT:** 082.251.2242 / 083.255.8572 / 0916.447.199
- **Email:** anhvinhhp34@gmail.com
- **Zalo:** 082.251.2242

---

## 📝 Ghi chú kỹ thuật

- Website không cần server, chạy hoàn toàn bằng HTML/CSS/JS tĩnh
- Font chữ load từ Google Fonts (cần internet khi xem)
- Form liên hệ dùng `mailto:` – mở ứng dụng email của người dùng
- Để nhận form qua web (không cần email client), có thể tích hợp [Formspree.io](https://formspree.io) miễn phí

---

*Website tạo bởi Claude AI – Anthropic | 2025*
