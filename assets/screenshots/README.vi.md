# Panduan Ảnh chụp màn hình TRAE Starter

<div align="center">
  <a href="README.md">English</a> | <a href="README.id.md">Bahasa Indonesia</a> | <a href="README.zh.md">简体中文</a> | <a href="README.hi.md">हिन्दी</a> | <a href="README.fr-ca.md">Français (CA)</a> | <a href="README.de.md">Deutsch</a> | <a href="README.fr.md">Français</a> | <a href="README.pt-br.md">Português (BR)</a> | <strong>Tiếng Việt</strong> | <a href="README.pl.md">Polski</a> | <a href="README.ja.md">日本語</a> | <a href="README.ko.md">한국어</a> | <a href="README.es.md">Español</a> | <a href="README.tr.md">Türkçe</a> | <a href="README.it.md">Italiano</a> | <a href="README.ru.md">Русский</a> | <a href="README.uk.md">Українська</a> | <a href="README.nl.md">Nederlands</a> | <a href="README.sv.md">Svenska</a> | <a href="README.ro.md">Română</a>
</div>
<br>


Bạn có thể dễ dàng chụp ảnh màn hình trang web TRAE Starter trong thư mục này!

## Daftar File yang Dibutuhkan
- `homepage.png`: Ảnh chụp màn hình trang chủ tampilan utama
- (tùy chọn) `mobile-view.png`: Tamil trên điện thoại di động
- (tùy chọn) `demo-feature.png`: Bản trình diễn tương tác phù hợp

## Mẫu web của Cara Menjalankan cho ảnh chụp màn hình
Gunakan Docker cho mẫu web công cụ sau:

```bash
# Di folder trae-starter
docker run -d -p 9002:80 --name trae-starter-web -v $(pwd)/public:/usr/share/nginx/html nginx:alpine

# Buka di browser: http://localhost:9002
```