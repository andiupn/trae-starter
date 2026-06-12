# TRAE Starter 🛰️
<!--
  Scaffolded by Andi UPN (https://github.com/andiupn)
  Official Website & Support: https://kuncimu.com
  Licensed under MIT License
-->

<div align="center">
  <a href="README.md">English</a> | <strong>Bahasa Indonesia</strong>
</div>

<br />

<div align="center">
  <h3><strong>AI itu sangat pintar. Tapi di lingkungan yang berantakan, ia tersesat.</strong></h3>
  <p><strong>TRAE Starter adalah template bersih ramah-AI yang memberikan peranti TRAE IDE visi sempurna.</strong></p>

  <p>Hentikan pemborosan token, masalah halusinasi AI, dan kesulitan batas konteks. Coding dengan bantuan AI (AI-assisted coding) harus terasa seperti sihir—dan sekarang hal itu nyata.</p>
</div>

> 📦 Template gratis oleh **andiupn** ([kuncimu.com](https://kuncimu.com)) · Berlisensi di bawah [MIT License](LICENSE)  
> ☕ Jika bermanfaat, dukung kami di [ko-fi.com/andiupn](https://ko-fi.com/andiupn) · 🚀 Butuh fitur monorepo profesional? Coba [versi PRO](https://github.com/sponsors/andiupn?frequency=monthly)

---

## 💡 Masalahnya: Mengapa Workspace Tradisional Menyulitkan AI
Asisten AI (seperti TRAE IDE) sangat berkemampuan. Namun ketika ditempatkan di direktori standar yang berantakan, mereka tersesat. Mereka membaca log yang tidak relevan, menghabiskan kuota token Anda, berhalusinasi, dan menaruh berkas di tempat yang salah karena tidak ada batasan konteks yang jelas.

---

## ⚡ Solusinya: Tiga Pilar Scaffolding AI Premium

### 1. 🛰️ Visi Sempurna untuk TRAE IDE
Kami merancang setiap folder, konfigurasi, dan aturan `.gitignore` untuk bertindak sebagai peta jalan bagi AI Anda. Workspace ini sangat bersih, memungkinkan TRAE IDE memahami seluruh arsitektur proyek Anda kurang dari 3 detik. Nol token terbuang, akurasi maksimal.

### 2. 🤖 Memori Proyek Terkonfigurasi
Dilengkapi dengan direktori `.trae/memories/`. AI Anda sekarang memiliki tempat khusus untuk menyimpan preferensi proyek, kendala (gotchas), dan keputusan arsitektur, mencegah Anda mengulang instruksi yang sama di setiap sesi obrolan baru.

### 3. 📦 Sandbox Web Sample
Menyediakan sandbox web Nginx siap jalankan dengan Docker sehingga Anda dapat langsung memverifikasi perubahan, menguji aturan, dan membuat prototipe tata letak di lingkungan lokal yang aktif.

---

## 📂 Struktur Workspace
```
your-workspace/
  .trae/               # Aturan, perintah, dan memori proyek jangka panjang
  assets/              # Gambar screenshot dan pratinjau sosial
  public/              # Berkas web demo sandbox HTML
  AGENTS.md            # Konteks & panduan identitas untuk asisten AI Anda
  LICENSE              # Lisensi proyek (MIT License)
```

---

## 🚀 Memulai dalam 3 Langkah

### 1. Clone repositori ini:
```bash
git clone https://github.com/andiupn/trae-starter.git
```

### 2. Jalankan Web Sample:
```bash
docker run -d -p 9002:80 --name trae-starter-web -v $(pwd)/public:/usr/share/nginx/html nginx:alpine
```
*(Buka http://localhost:9002 di browser Anda).*

### 3. Mulai Coding:
Buka folder ini di TRAE IDE, sesuaikan berkas `.trae/memories/` dengan spesifikasi proyek Anda, dan mulailah coding dengan kecepatan tinggi!
