#TRAE Starter 🛰️
<!--
  Scaffolded by Andi UPN (https://github.com/andiupn)
  Official Website & Support: https://kuncimu.com
  Licensed under MIT License
-->

<div align="center">
  <a href="README.md">English</a> | <a href="README.id.md">Bahasa Indonesia</a> | <a href="README.zh.md">简体中文</a> | <a href="README.hi.md">हिन्दी</a> | <a href="README.fr-ca.md">Français (CA)</a> | <a href="README.de.md">Deutsch</a> | <a href="README.fr.md">Français</a> | <a href="README.pt-br.md">Português (BR)</a> | <a href="README.vi.md">Tiếng Việt</a> | <a href="README.pl.md">Polski</a> | <a href="README.ja.md">日本語</a> | <a href="README.ko.md">한국어</a> | <a href="README.es.md">Español</a> | <a href="README.tr.md">Türkçe</a> | <a href="README.it.md">Italiano</a> | <a href="README.ru.md">Русский</a> | <a href="README.uk.md">Українська</a> | <a href="README.nl.md">Nederlands</a> | <a href="README.sv.md">Svenska</a> | <strong>Română</strong>
</div>

<br />

<div align="center">
  __HTML_44<strong>AI este inteligent. Dar într-un mediu dezordonat, se pierde.</strong></h3>
  <p><strong>TRAE Starter este un șablon curat, creat de AI, care oferă TRAE IDE o viziune perfectă.</strong></p>

  <p>Nu mai risipiți jetoane, nu suferi de halucinații AI și nu te mai lupta cu limitele contextului. Codarea vibrațiilor ar trebui să pară magică, iar acum este.</p>
</div>

> 📦 Șablon gratuit de la **andiupn** ([kuncimu.com](https://kuncimu.com)) · Licențiat sub [Licență MIT](LICENSE)  
> ☕ Dacă este util, [cumpără-mi o cafea](https://ko-fi.com/andiupn) · 🚀 Ai nevoie de funcții monorepo pentru starea întâi? Încercați [versiunea PRO](https://github.com/sponsors/andiupn?frequency=monthly)

---

## 💡 Problema: De ce spațiile de lucru tradiționale eșuează AI
Editorii AI (cum ar fi TRAE IDE) sunt extraordinar de capabili. Dar când sunt aruncate în directoare standard, aglomerate, se pierd. Ei citesc jurnalele irelevante, vă scapă bugetul de simboluri, halucinează și plasează fișiere în directoare greșite, deoarece nu există limite clare.

---

## ⚡ Soluția: Trei piloni ai schelei premium AI

### 1. 🛰️ Perfect Vision pentru TRAE IDE
Am conceput fiecare folder, configurație și regulă `.gitignore` pentru a acționa ca foi de parcurs pentru AI-ul tău. Spațiul de lucru este extrem de curat, permițând TRAE IDE să înțeleagă întreaga arhitectură a proiectului în mai puțin de 3 secunde. Zero jetoane risipite, precizie maximă.

### 2. 🤖 Memorie de proiect preconfigurată
Echipat cu directorul `.trae/memories/`. AI dvs. are acum un loc dedicat pentru a stoca preferințele de proiect, problemele și deciziile arhitecturale, împiedicându-vă să repetați instrucțiunile în sesiunile de chat.

### 3. 📦 Sandbox Web Sample
Un sandbox web Nginx containerizat gata de rulat, astfel încât să puteți verifica instantaneu modificările, regulile de testare și machetele prototip într-un mediu local live.

---

## 📊 LITE vs PRO: Upgrade Premium

| Caracteristica | 🆓 LITE (gratuit) | 💎 PRO (Plătit) |
|---|:---:|:---:|
| **Configurarea regulilor** | Reguli de bază | Cuprinzător (Web/Mobil/Ieșire) |
| **Abilități de specialitate** | 1 (testare) | 2 (+ revizuire cod, securitate) |
| **Amintiri de proiect** | Sămânță de bază | Complet & Structurat |
| **Workflow Pipeline** | Standard | Modul Quest + Expert |
| **Lisensi** | Licență MIT | Proprietate comercială |

👉 **[Vedeți Ghidul complet de comparare și actualizare a funcțiilor](COMPARISON.md)**

---

## 📂 Planul spațiului de lucru

```
your-workspace/
  .trae/               # Rules, commands, and long-term project memory
  assets/              # Screenshots and social previews
  public/              # HTML sandbox web files
  AGENTS.md            # Context & identity guidelines for your AI assistant
  LICENSE              # Project license (MIT License)
```

---

## 🚀 Începeți în 3 pași

### 1. Clonează acest depozit:

```bash
git clone https://github.com/andiupn/trae-starter.git
```

### 2. Rulați proba web:

```bash
docker run -d -p 9002:80 --name trae-starter-web -v $(pwd)/public:/usr/share/nginx/html nginx:alpine
```

*(Deschideți http://localhost:9002 pentru a vedea demonstrația).*

### 3. Începeți codarea:
Deschideți acest dosar în TRAE IDE, personalizați `.trae/memories/` cu specificațiile proiectului și începeți codarea vibrațiilor!