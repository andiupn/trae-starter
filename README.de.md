#TRAE-Starter 🛰️
<!--
  Scaffolded by Andi UPN (https://github.com/andiupn)
  Official Website & Support: https://kuncimu.com
  Licensed under MIT License
-->

<div align="center">
  <strong>Englisch</strong> | <a href="README.id.md">Bahasa Indonesia</a> | <a href="README.zh.md">简体中文</a> | <a href="README.hi.md">हिन्दी</a> | <a href="README.fr-ca.md">Français (CA)</a> | <a href="README.de.md">Deutsch</a> | <a href="README.fr.md">Français</a> | <a href="README.pt-br.md">Português (BR)</a> | <a href="README.vi.md">Tiếng Việt</a> | <a href="README.pl.md">Polnisch</a>
</div>

<br />

<div align="center">
  <h3><strong>KI ist intelligent. Aber in einer chaotischen Umgebung geht es verloren.</strong></h3>
  <p><strong>TRAE Starter ist eine saubere, KI-orientierte Vorlage, die TRAE IDE eine perfekte Sicht verleiht.</strong></p>

  <p>Hören Sie auf, Token zu verschwenden, unter KI-Halluzinationen zu leiden und mit Kontextgrenzen zu kämpfen. Vibe-Codierung sollte sich wie Magie anfühlen – und jetzt tut es das auch.</p>
</div>

> 📦 Kostenlose Vorlage von **andiupn** ([kuncimu.com](https://kuncimu.com)) · Lizenziert unter [MIT-Lizenz](LICENSE)  
> ☕ Wenn nützlich, [kauf mir einen Kaffee](https://ko-fi.com/andiupn) · 🚀 Benötigen Sie Status-First-Monorepo-Funktionen? Probieren Sie die [PRO-Version](https://github.com/sponsors/andiupn?frequency=monthly) aus.

---

## 💡 Das Problem: Warum traditionelle Arbeitsbereiche die KI versagen
KI-Editoren (wie TRAE IDE) sind phänomenal leistungsfähig. Aber wenn sie in standardmäßigen, überfüllten Verzeichnissen abgelegt werden, gehen sie verloren. Sie lesen irrelevante Protokolle, sprengen Ihr Token-Budget, halluzinieren und legen Dateien in den falschen Verzeichnissen ab, weil es keine klaren Grenzen gibt.

---

## ⚡ Die Lösung: Drei Säulen des Premium-KI-Gerüsts

### 1. 🛰️ Perfekte Vision für TRAE IDE
Wir haben jeden Ordner, jede Konfiguration und jede `.gitignore`-Regel so entworfen, dass sie als Roadmaps für Ihre KI dienen. Der Arbeitsbereich ist äußerst übersichtlich, sodass TRAE IDE Ihre gesamte Projektarchitektur in weniger als 3 Sekunden verstehen kann. Keine verschwendeten Token, maximale Genauigkeit.

### 2. 🤖 Vorkonfigurierter Projektspeicher
Ausgestattet mit dem Verzeichnis `.trae/memories/`. Ihre KI verfügt jetzt über einen speziellen Ort zum Speichern von Projektpräferenzen, Fallstricken und Architekturentscheidungen, sodass Sie in Chat-Sitzungen keine Anweisungen wiederholen müssen.

### 3. 📦 Sandbox-Webbeispiel
Eine betriebsbereite, containerisierte Nginx-Web-Sandbox, mit der Sie Änderungen, Testregeln und Prototyp-Layouts sofort in einer lokalen Live-Umgebung überprüfen können.

---

## 📊 LITE vs. PRO: Das Premium-Upgrade

| Funktion | 🆓 LITE (Kostenlos) | 💎 PRO (Kostenpflichtig) |
|---|:---:|:---:|
| **Regelkonfiguration** | Grundregeln | Umfassend (Web/Mobil/Ausgabe) |
| **Spezialfähigkeiten** | 1 (Testen) | 2 (+ Codeüberprüfung, Sicherheit) |
| **Projekterinnerungen** | Grundlegendes Saatgut | Vollständig und strukturiert |
| **Workflow-Pipeline** | Standard | Quest + Expertenmodus |
| **Lizenz** | MIT-Lizenz | Proprietäre Werbung |

👉 **[Vollständigen Funktionsvergleich und Upgrade-Leitfaden anzeigen](COMPARISON.md)**

---

## 📂 Workspace Blueprint

```
your-workspace/
  .trae/               # Rules, commands, and long-term project memory
  assets/              # Screenshots and social previews
  public/              # HTML sandbox web files
  AGENTS.md            # Context & identity guidelines for your AI assistant
  LICENSE              # Project license (MIT License)
```

---

## 🚀 Beginnen Sie in 3 Schritten

### 1. Dieses Repository klonen:

```bash
git clone https://github.com/andiupn/trae-starter.git
```

### 2. Führen Sie das Webbeispiel aus:

```bash
docker run -d -p 9002:80 --name trae-starter-web -v $(pwd)/public:/usr/share/nginx/html nginx:alpine
```

*(Öffnen Sie http://localhost:9002, um die Demo anzusehen).*

### 3. Beginnen Sie mit dem Codieren:
Öffnen Sie diesen Ordner in TRAE IDE, passen Sie `.trae/memories/` an Ihre Projektspezifikationen an und beginnen Sie mit der Vibe-Codierung!