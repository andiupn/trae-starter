# Panduan Screenshot TRAE Starter

<div align="center">
  <a href="README.md">English</a> | <a href="README.id.md">Bahasa Indonesia</a> | <a href="README.zh.md">简体中文</a> | <a href="README.hi.md">हिन्दी</a> | <a href="README.fr-ca.md">Français (CA)</a> | <a href="README.de.md">Deutsch</a> | <a href="README.fr.md">Français</a> | <a href="README.pt-br.md">Português (BR)</a> | <a href="README.vi.md">Tiếng Việt</a> | <a href="README.pl.md">Polski</a> | <a href="README.ja.md">日本語</a> | <a href="README.ko.md">한국어</a> | <a href="README.es.md">Español</a> | <a href="README.tr.md">Türkçe</a> | <a href="README.it.md">Italiano</a> | <a href="README.ru.md">Русский</a> | <strong>Українська</strong> | <a href="README.nl.md">Nederlands</a> | <a href="README.sv.md">Svenska</a> | <a href="README.ro.md">Română</a>
</div>
<br>


Silakan simpan screenshot website TRAE Starter di folder ini!

## Daftar File yang Dibutuhkan
- `homepage.png`: Скріншот tampilan utama домашньої сторінки
- (необов'язково) `mobile-view.png`: Tampilan di perangkat mobile
- (необов'язково) `demo-feature.png`: Demo fitur interaktif

## Зробити веб-зразок для створення знімка екрана
Налаштуйте Docker для веб-прикладу зміни ланки:

```bash
# Di folder trae-starter
docker run -d -p 9002:80 --name trae-starter-web -v $(pwd)/public:/usr/share/nginx/html nginx:alpine

# Buka di browser: http://localhost:9002
```