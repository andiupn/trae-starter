# Capture d'écran de Panduan TRAE Starter

<div align="center">
  <a href="README.md">English</a> | <a href="README.id.md">Bahasa Indonesia</a> | <a href="README.zh.md">简体中文</a> | <a href="README.hi.md">हिन्दी</a> | <strong>Français (CA)</strong> | <a href="README.de.md">Deutsch</a> | <a href="README.fr.md">Français</a> | <a href="README.pt-br.md">Português (BR)</a> | <a href="README.vi.md">Tiếng Việt</a> | <a href="README.pl.md">Polski</a> | <a href="README.ja.md">日本語</a> | <a href="README.ko.md">한국어</a> | <a href="README.es.md">Español</a> | <a href="README.tr.md">Türkçe</a> | <a href="README.it.md">Italiano</a> | <a href="README.ru.md">Русский</a> | <a href="README.uk.md">Українська</a> | <a href="README.nl.md">Nederlands</a> | <a href="README.sv.md">Svenska</a> | <a href="README.ro.md">Română</a>
</div>
<br>


Silakan simpan capture d'écran du site Web TRAE Starter di dossier ini !

## Fichier Daftar yang Dibutuhkan
- `homepage.png` : Capture d'écran de la page d'accueil de Tampilan Utama
- (facultatif) `mobile-view.png` : Tampilan di perangkat mobile
- (facultatif) `demo-feature.png` : Démo fitur interaktif

## Cara Menjalankan Web Sample pour une capture d'écran
Utilisez Docker pour trouver un exemple Web :

```bash
# Di folder trae-starter
docker run -d -p 9002:80 --name trae-starter-web -v $(pwd)/public:/usr/share/nginx/html nginx:alpine

# Buka di browser: http://localhost:9002
```