# TRAE Başlangıç 🛰️
<!--
  Scaffolded by Andi UPN (https://github.com/andiupn)
  Official Website & Support: https://kuncimu.com
  Licensed under MIT License
-->

<div align="center">
  <a href="README.md">English</a> | <a href="README.id.md">Bahasa Indonesia</a> | <a href="README.zh.md">简体中文</a> | <a href="README.hi.md">हिन्दी</a> | <a href="README.fr-ca.md">Français (CA)</a> | <a href="README.de.md">Deutsch</a> | <a href="README.fr.md">Français</a> | <a href="README.pt-br.md">Português (BR)</a> | <a href="README.vi.md">Tiếng Việt</a> | <a href="README.pl.md">Polski</a> | <a href="README.ja.md">日本語</a> | <a href="README.ko.md">한국어</a> | <a href="README.es.md">Español</a> | <strong>Türkçe</strong> | <a href="README.it.md">Italiano</a> | <a href="README.ru.md">Русский</a> | <a href="README.uk.md">Українська</a> | <a href="README.nl.md">Nederlands</a> | <a href="README.sv.md">Svenska</a> | <a href="README.ro.md">Română</a>
</div>

<br />

<div align="center">
  <h3><strong>AI akıllıdır. Ancak dağınık bir ortamda kaybolur.</strong></h3>
  <p><strong>TRAE Starter, TRAE IDE'ye mükemmel görüş sağlayan temiz, yapay zeka öncelikli bir şablondur.</strong></p>

  <p>Belirteç israfına, yapay zeka halüsinasyonlarına maruz kalmaya ve bağlam sınırlarıyla boğuşmaya son verin. Vibe kodlaması sihir gibi hissettirmeli ve şimdi öyle.</p>
</div>

> 📦 **andiupn** ([kuncimu.com](https://kuncimu.com)) tarafından hazırlanan ücretsiz şablon · [MIT Lisansı](LICENSE) kapsamında lisanslıdır  
> ☕ Yararlıysa, [bana bir kahve al](https://ko-fi.com/andiupn) · 🚀 Durum öncelikli monorepo özelliklerine mi ihtiyacınız var? [PRO sürümünü] deneyin(https://github.com/sponsors/andiupn?frequency=monthly)

---

## 💡 Sorun: Geleneksel Çalışma Alanları Neden Yapay Zeka'da Başarısız Oluyor?
AI Editörleri (TRAE IDE gibi) olağanüstü derecede yeteneklidir. Ancak standart, karmaşık dizinlere düştüklerinde kaybolurlar. İlgisiz günlükleri okurlar, token bütçenizi tüketirler, halüsinasyon görürler ve net sınırlar olmadığı için dosyaları yanlış dizinlere yerleştirirler.

---

## ⚡ Çözüm: Birinci Sınıf Yapay Zekalı İskelenin Üç Temeli

### 1. 🛰️ TRAE IDE için Mükemmel Vizyon
Her klasörü, yapılandırmayı ve `.gitignore` kuralını yapay zekanız için yol haritası görevi görecek şekilde tasarladık. Çalışma alanı son derece temiz olup TRAE IDE'nin tüm proje mimarinizi 3 saniyeden daha kısa sürede anlamasına olanak tanır. Sıfır jeton israfı, maksimum doğruluk.

### 2. 🤖 Önceden Yapılandırılmış Proje Belleği
`.trae/memories/` dizini ile donatılmıştır. Yapay zekanızın artık proje tercihlerini, elde edilen sonuçları ve mimari kararları depolamak için ayrılmış bir yeri var ve bu da talimatları sohbet oturumlarında tekrarlamanızı engelliyor.

### 3. 📦 Sandbox Web Örneği
Değişiklikleri, kuralları test etmenizi ve prototip düzenlerini canlı bir yerel ortamda anında doğrulayabilmenizi sağlayan, çalıştırılmaya hazır, kapsayıcılı bir Nginx web sanal alanı.

---

## 📊 LITE ve PRO: Premium Yükseltmesi

| Özellik | 🆓 LITE (Ücretsiz) | 💎 PRO (Ücretli) |
|---|:---:|:---:|
| **Kural Yapılandırması** | Temel kurallar | Kapsamlı (Web/Mobil/Çıktı) |
| **Uzmanlaşmış Beceriler** | 1 (test) | 2 (+ kod incelemesi, güvenlik) |
| **Proje Anıları** | Temel Tohum | Tam ve Yapılandırılmış |
| **İş Akışı Ardışık Düzeni** | Standart | Görev + Uzman Modu |
| **Lisensi** | MİT Lisansı | Tescilli Ticari |

👉 **[Tam Özellik Karşılaştırma ve Yükseltme Kılavuzunu Görüntüleyin](COMPARISON.md)**

---

## 📂 Çalışma Alanı Planı

```
your-workspace/
  .trae/               # Rules, commands, and long-term project memory
  assets/              # Screenshots and social previews
  public/              # HTML sandbox web files
  AGENTS.md            # Context & identity guidelines for your AI assistant
  LICENSE              # Project license (MIT License)
```

---

## 🚀 3 Adımda Başlayın

### 1. Bu depoyu klonlayın:

```bash
git clone https://github.com/andiupn/trae-starter.git
```

### 2. Web Örneğini çalıştırın:

```bash
docker run -d -p 9002:80 --name trae-starter-web -v $(pwd)/public:/usr/share/nginx/html nginx:alpine
```

*(Demoyu görüntülemek için http://localhost:9002 adresini açın).*

### 3. Kodlamaya Başlayın:
Bu klasörü TRAE IDE'de açın, `.trae/memories/` proje özelliklerinizle özelleştirin ve titreşim kodlamaya başlayın!