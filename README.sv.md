# TRAE Starter 🛰️
<!--
  Scaffolded by Andi UPN (https://github.com/andiupn)
  Official Website & Support: https://kuncimu.com
  Licensed under MIT License
-->

<div align="center">
  <a href="README.md">English</a> | <a href="README.id.md">Bahasa Indonesia</a> | <a href="README.zh.md">简体中文</a> | <a href="README.hi.md">हिन्दी</a> | <a href="README.fr-ca.md">Français (CA)</a> | <a href="README.de.md">Deutsch</a> | <a href="README.fr.md">Français</a> | <a href="README.pt-br.md">Português (BR)</a> | <a href="README.vi.md">Tiếng Việt</a> | <a href="README.pl.md">Polski</a> | <a href="README.ja.md">日本語</a> | <a href="README.ko.md">한국어</a> | <a href="README.es.md">Español</a> | <a href="README.tr.md">Türkçe</a> | <a href="README.it.md">Italiano</a> | <a href="README.ru.md">Русский</a> | <a href="README.uk.md">Українська</a> | <a href="README.nl.md">Nederlands</a> | <strong>Svenska</strong> | <a href="README.ro.md">Română</a>
</div>

<br />

<div align="center">
  <h3><strong>AI är smart. Men i en rörig miljö försvinner den.</strong></h3>
  <p><strong>TRAE Starter är en ren, AI-first mall som ger TRAE IDE perfekt syn.</strong></p>

  <p>Sluta slösa bort tokens, lida av AI-hallucinationer och kämpa med sammanhangsgränser. Vibe-kodning ska kännas som magi – och nu gör det det.</p>
</div>

> 📦 Gratis mall av **andiupn** ([kuncimu.com](https://kuncimu.com)) · Licensierad under [MIT License](LICENSE)  
> ☕ Om det är användbart, [köp mig en kaffe](https://ko-fi.com/andiupn) · 🚀 Behöver du statusförsta monorepo-funktioner? Prova [PRO-versionen](https://github.com/sponsors/andiupn?frequency=monthly)

---

## 💡 Problemet: Varför traditionella arbetsytor misslyckas med AI
AI-redigerare (som TRAE IDE) är fenomenalt kapabla. Men när de hamnar i vanliga, röriga kataloger, går de vilse. De läser irrelevanta loggar, blåser igenom din tokenbudget, hallucinerar och placerar filer i fel kataloger eftersom det inte finns några tydliga gränser.

---

## ⚡ Lösningen: Tre pelare av premium AI-ställningar

### 1. 🛰️ Perfekt vision för TRAE IDE
Vi designade varje mapp, konfiguration och `.gitignore`-regel för att fungera som färdplaner för din AI. Arbetsytan är extremt ren, vilket gör att TRAE IDE kan förstå hela din projektarkitektur på mindre än 3 sekunder. Noll bortkastade tokens, maximal noggrannhet.

### 2. 🤖 Förkonfigurerat projektminne
Utrustad med katalogen `.trae/memories/`. Din AI har nu en dedikerad plats för att lagra projektpreferenser, gotchas och arkitektoniska beslut, vilket hindrar dig från att upprepa instruktioner över chattsessioner.

### 3. 📦 Sandlåda webbexempel
En färdig containeriserad Nginx webbsandlåda så att du omedelbart kan verifiera ändringar, testregler och prototyplayouter i en levande lokal miljö.

---

## 📊 LITE vs PRO: Premium-uppgraderingen

| Funktion | 🆓 LITE (gratis) | 💎 PRO (betald) |
|---|:---:|:---:|
| **Regelkonfiguration** | Grundläggande regler | Omfattande (Webb/Mobil/Output) |
| **Specialiserade färdigheter** | 1 (testning) | 2 (+ kodgranskning, säkerhet) |
| **Projektminnen** | Basic Seed | Komplett & strukturerad |
| **Arbetsflödesrörledning** | Standard | Quest + Expertläge |
| **Lisensi** | MIT-licens | Proprietär reklam |

👉 **[Visa fullständig jämförelse av funktioner och uppgraderingsguide](COMPARISON.md)**

---

## 📂 Arbetsyta Blueprint

```
your-workspace/
  .trae/               # Rules, commands, and long-term project memory
  assets/              # Screenshots and social previews
  public/              # HTML sandbox web files
  AGENTS.md            # Context & identity guidelines for your AI assistant
  LICENSE              # Project license (MIT License)
```

---

## 🚀 Kom igång i 3 steg

### 1. Klona detta förråd:

```bash
git clone https://github.com/andiupn/trae-starter.git
```

### 2. Kör webbexemplet:

```bash
docker run -d -p 9002:80 --name trae-starter-web -v $(pwd)/public:/usr/share/nginx/html nginx:alpine
```

*(Öppna http://localhost:9002 för att se demon).*

### 3. Börja koda:
Öppna den här mappen i TRAE IDE, anpassa `.trae/memories/` med dina projektspecifikationer och börja vibekodning!