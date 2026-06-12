#TRAE Khởi Đầu 🛰️
<!--
  Scaffolded by Andi UPN (https://github.com/andiupn)
  Official Website & Support: https://kuncimu.com
  Licensed under MIT License
-->

<div align="center">
  <a href="README.md">English</a> | <a href="README.id.md">Bahasa Indonesia</a> | <a href="README.zh.md">简体中文</a> | <a href="README.hi.md">हिन्दी</a> | <a href="README.fr-ca.md">Français (CA)</a> | <a href="README.de.md">Deutsch</a> | <a href="README.fr.md">Français</a> | <a href="README.pt-br.md">Português (BR)</a> | <strong>Tiếng Việt</strong> | <a href="README.pl.md">Polski</a> | <a href="README.ja.md">日本語</a> | <a href="README.ko.md">한국어</a> | <a href="README.es.md">Español</a> | <a href="README.tr.md">Türkçe</a> | <a href="README.it.md">Italiano</a> | <a href="README.ru.md">Русский</a> | <a href="README.uk.md">Українська</a> | <a href="README.nl.md">Nederlands</a> | <a href="README.sv.md">Svenska</a> | <a href="README.ro.md">Română</a>
</div>
<br>

<div align="center">
  __HTML_28_<strong>AI rất thông minh. Nhưng trong một môi trường lộn xộn, nó sẽ bị thất lạc.__HTML_30_</h3>
  <p><strong>TRAE Starter là một mẫu rõ ràng, ưu tiên AI mang đến cho TRAE IDE tầm nhìn hoàn hảo.</strong></p>

  <p>Hãy ngừng lãng phí mã thông báo, chịu đựng ảo giác về AI và đấu tranh với các ranh giới ngữ cảnh. Mã hóa Vibe sẽ giống như một phép thuật—và bây giờ thì đúng như vậy.</p>
</div>

> 📦 Mẫu miễn phí của **andiupn** ([kuncimu.com](https://kuncimu.com)) · Được cấp phép theo [Giấy phép MIT](LICENSE)  
> ☕ Nếu hữu ích, [mua cho tôi một ly cà phê](https://ko-fi.com/andiupn) · 🚀 Bạn cần các tính năng monorepo ưu tiên trạng thái? Hãy thử [phiên bản PRO](https://github.com/sponsors/andiupn?frequency=monthly)

---

## 💡 Vấn đề: Tại sao không gian làm việc truyền thống lại thất bại với AI
Trình chỉnh sửa AI (như TRAE IDE) có khả năng phi thường. Nhưng khi thả vào các thư mục tiêu chuẩn, lộn xộn, chúng sẽ bị lạc. Họ đọc các nhật ký không liên quan, tiêu tốn ngân sách mã thông báo của bạn, gây ảo giác và đặt các tệp vào sai thư mục vì không có ranh giới rõ ràng.

---

## ⚡ Giải pháp: Ba trụ cột của giàn giáo AI cao cấp

### 1. 🛰️ Tầm nhìn hoàn hảo cho TRAE IDE
Chúng tôi đã thiết kế mọi thư mục, cấu hình và quy tắc `.gitignore` để hoạt động như lộ trình cho AI của bạn. Không gian làm việc cực kỳ sạch sẽ, cho phép TRAE IDE hiểu toàn bộ kiến ​​trúc dự án của bạn trong vòng chưa đầy 3 giây. Không lãng phí mã thông báo, độ chính xác tối đa.

### 2. 🤖 Bộ nhớ dự án được cấu hình sẵn
Được trang bị thư mục `.trae/memories/`. AI của bạn hiện có một nơi dành riêng để lưu trữ các tùy chọn, vấn đề cần giải quyết và các quyết định về kiến ​​trúc của dự án, ngăn bạn lặp lại hướng dẫn trong các phiên trò chuyện.

### 3. 📦 Mẫu web hộp cát
Hộp cát web Nginx được đóng gói sẵn sàng chạy để bạn có thể xác minh ngay lập tức các thay đổi, quy tắc kiểm tra và bố cục nguyên mẫu trong môi trường cục bộ trực tiếp.

---

## 📊 LITE vs PRO: Bản nâng cấp cao cấp

| Tính năng | 🆓 LITE (Miễn phí) | 💎 PRO (Trả phí) |
|---|:---:|:---:|
| **Cấu hình quy tắc** | Quy tắc cơ bản | Toàn diện (Web/Di động/Đầu ra) |
| **Kỹ năng chuyên môn** | 1 (thử nghiệm) | 2 (+ đánh giá mã, bảo mật) |
| **Ký ức dự án** | Hạt giống cơ bản | Hoàn thiện & Có cấu trúc |
| **Quy trình công việc** | Tiêu chuẩn | Chế độ nhiệm vụ + chuyên gia |
| **Giấy phép** | Giấy phép MIT | Thương mại độc quyền |

👉 **[Xem hướng dẫn nâng cấp và so sánh đầy đủ tính năng](COMPARISON.md)**

---

## 📂 Sơ đồ không gian làm việc

```
your-workspace/
  .trae/               # Rules, commands, and long-term project memory
  assets/              # Screenshots and social previews
  public/              # HTML sandbox web files
  AGENTS.md            # Context & identity guidelines for your AI assistant
  LICENSE              # Project license (MIT License)
```

---

## 🚀 Bắt đầu sau 3 bước

### 1. Sao chép kho lưu trữ này:

```bash
git clone https://github.com/andiupn/trae-starter.git
```

### 2. Chạy mẫu Web:

```bash
docker run -d -p 9002:80 --name trae-starter-web -v $(pwd)/public:/usr/share/nginx/html nginx:alpine
```

*(Mở http://localhost:9002 để xem bản demo).*

### 3. Bắt đầu viết mã:
Mở thư mục này trong TRAE IDE, tùy chỉnh `.trae/memories/` với thông số kỹ thuật dự án của bạn và bắt đầu viết mã Vibe!