# 판두안 스크린샷 TRAE 스타터

<div align="center">
  <a href="README.md">English</a> | <a href="README.id.md">Bahasa Indonesia</a> | <a href="README.zh.md">简体中文</a> | <a href="README.hi.md">हिन्दी</a> | <a href="README.fr-ca.md">Français (CA)</a> | <a href="README.de.md">Deutsch</a> | <a href="README.fr.md">Français</a> | <a href="README.pt-br.md">Português (BR)</a> | <a href="README.vi.md">Tiếng Việt</a> | <a href="README.pl.md">Polski</a> | <a href="README.ja.md">日本語</a> | <strong>한국어</strong> | <a href="README.es.md">Español</a> | <a href="README.tr.md">Türkçe</a> | <a href="README.it.md">Italiano</a> | <a href="README.ru.md">Русский</a> | <a href="README.uk.md">Українська</a> | <a href="README.nl.md">Nederlands</a> | <a href="README.sv.md">Svenska</a> | <a href="README.ro.md">Română</a>
</div>


Silakan simpan 스크린샷 웹사이트 TRAE Starter di 폴더 ini!

## Daftar 파일 양 Dibutuhkan
- `homepage.png`: 탐필란 우타마 홈페이지 스크린샷
- (선택사항) `mobile-view.png`: Tampilan di perangkat mobile
- (선택 사항) `demo-feature.png`: 상호작용용 데모

## 스크린샷의 Cara Menjalankan 웹 샘플
웹 샘플에 대한 Gunakan Docker:

```bash
# Di folder trae-starter
docker run -d -p 9002:80 --name trae-starter-web -v $(pwd)/public:/usr/share/nginx/html nginx:alpine

# Buka di browser: http://localhost:9002
```