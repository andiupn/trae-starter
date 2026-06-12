#TRAE Starter🛰️
<!--
  Scaffolded by Andi UPN (https://github.com/andiupn)
  Official Website & Support: https://kuncimu.com
  Licensed under MIT License
-->

<div align="center">
  <a href="README.md">English</a> | <a href="README.id.md">Bahasa Indonesia</a> | <a href="README.zh.md">简体中文</a> | <a href="README.hi.md">हिन्दी</a> | <a href="README.fr-ca.md">Français (CA)</a> | <a href="README.de.md">Deutsch</a> | <a href="README.fr.md">Français</a> | <a href="README.pt-br.md">Português (BR)</a> | <a href="README.vi.md">Tiếng Việt</a> | <a href="README.pl.md">Polski</a> | <a href="README.ja.md">日本語</a> | <a href="README.ko.md">한국어</a> | <a href="README.es.md">Español</a> | <a href="README.tr.md">Türkçe</a> | <a href="README.it.md">Italiano</a> | <a href="README.ru.md">Русский</a> | <a href="README.uk.md">Українська</a> | <strong>Nederlands</strong>
</div>

<br />

<div align="center">
  <h3><strong>AI is slim. Maar in een rommelige omgeving gaat het verloren.</strong></h3>
  <p><strong>TRAE Starter is een schone, AI-first-sjabloon die TRAE IDE een perfect zicht geeft.</strong></p>

  <p>Stop met het verspillen van tokens, het lijden aan AI-hallucinaties en het worstelen met contextgrenzen. Vibe-codering zou als magie moeten aanvoelen, en nu doet het dat ook.</p>
</div>

> 📦 Gratis sjabloon van **andiupn** ([kuncimu.com](https://kuncimu.com)) · Gelicentieerd onder [MIT-licentie](LICENSE)  
> ☕ Indien nuttig, [koop een kopje koffie voor mij](https://ko-fi.com/andiupn) · 🚀 Heeft u status-first monorepo-functies nodig? Probeer de [PRO-versie](https://github.com/sponsors/andiupn?frequency=monthly)

---

## 💡 Het probleem: waarom traditionele werkruimten tekortschieten op het gebied van AI
AI-editors (zoals TRAE IDE) zijn fenomenaal capabel. Maar als ze in standaard, rommelige mappen worden geplaatst, raken ze verdwaald. Ze lezen irrelevante logboeken, blazen uw tokenbudget door, hallucineren en plaatsen bestanden in de verkeerde mappen omdat er geen duidelijke grenzen zijn.

---

## ⚡ De oplossing: drie pijlers van premium AI-steigers

### 1. 🛰️ Perfect zicht voor TRAE IDE
We hebben elke map, configuratie en `.gitignore` regel ontworpen om als routekaarten voor uw AI te fungeren. De werkruimte is extreem schoon, waardoor TRAE IDE uw volledige projectarchitectuur in minder dan 3 seconden kan begrijpen. Geen verspilde tokens, maximale nauwkeurigheid.

### 2. 🤖 Vooraf geconfigureerd projectgeheugen
Uitgerust met `.trae/memories/` directory. Uw AI heeft nu een speciale plek om projectvoorkeuren, valkuilen en architecturale beslissingen op te slaan, zodat u geen instructies hoeft te herhalen tijdens chatsessies.

### 3. 📦 Sandbox-webvoorbeeld
Een kant-en-klare Nginx-websandbox in containers, zodat u direct wijzigingen, testregels en prototype-indelingen kunt verifiëren in een live lokale omgeving.

---

## 📊 LITE versus PRO: de premium-upgrade

| Kenmerk | 🆓 LITE (gratis) | 💎 PRO (betaald) |
|---|:---:|:---:|
| **Regelconfiguratie** | Basisregels | Uitgebreid (web/mobiel/uitvoer) |
| **Gespecialiseerde vaardigheden** | 1 (testen) | 2 (+ codebeoordeling, beveiliging) |
| **Projectherinneringen** | Basiszaad | Compleet & Gestructureerd |
| **Workflowpijplijn** | Standaard | Quest + Expert-modus |
| **Lisensi** | MIT-licentie | Eigen commercieel |

👉 **[Bekijk de volledige functievergelijkings- en upgradehandleiding](COMPARISON.md)**

---

## 📂 Blauwdruk werkruimte

```
your-workspace/
  .trae/               # Rules, commands, and long-term project memory
  assets/              # Screenshots and social previews
  public/              # HTML sandbox web files
  AGENTS.md            # Context & identity guidelines for your AI assistant
  LICENSE              # Project license (MIT License)
```

---

## 🚀 Ga aan de slag in 3 stappen

### 1. Kloon deze repository:

```bash
git clone https://github.com/andiupn/trae-starter.git
```

### 2. Voer het webvoorbeeld uit:

```bash
docker run -d -p 9002:80 --name trae-starter-web -v $(pwd)/public:/usr/share/nginx/html nginx:alpine
```

*(Open http://localhost:9002 om de demo te bekijken).*

### 3. Begin met coderen:
Open deze map in TRAE IDE, pas `.trae/memories/` aan met uw projectspecificaties en begin met het coderen van de vibe!