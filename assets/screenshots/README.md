# Panduan Screenshot TRAE Starter

Silakan simpan screenshot website TRAE Starter di folder ini!

## Daftar File yang Dibutuhkan
- `homepage.png`: Screenshot tampilan utama homepage
- (opsional) `mobile-view.png`: Tampilan di perangkat mobile
- (opsional) `demo-feature.png`: Demo fitur interaktif

## Cara Menjalankan Web Sample untuk Screenshot
Gunakan Docker untuk menjalankan web sample:
```bash
# Di folder trae-starter
docker run -d -p 9002:80 --name trae-starter-web -v $(pwd)/public:/usr/share/nginx/html nginx:alpine

# Buka di browser: http://localhost:9002
```
