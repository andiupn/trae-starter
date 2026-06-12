# TRAE Starter 🛰️
<!--
  Scaffolded by Andi UPN (https://github.com/andiupn)
  Official Website & Support: https://kuncimu.com
  Licensed under MIT License
-->

<div align="center">
  <a href="README.md">English</a> | <a href="README.id.md">Bahasa Indonesia</a> | <a href="README.zh.md">简体中文</a> | <a href="README.hi.md">हिन्दी</a> | <a href="README.fr-ca.md">Français (CA)</a> | <a href="README.de.md">Deutsch</a> | <a href="README.fr.md">Français</a> | <a href="README.pt-br.md">Português (BR)</a> | <a href="README.vi.md">Tiếng Việt</a> | <a href="README.pl.md">Polski</a> | <a href="README.ja.md">日本語</a> | <a href="README.ko.md">한국어</a> | <a href="README.es.md">Español</a> | <a href="README.tr.md">Türkçe</a> | <a href="README.it.md">Italiano</a> | <a href="README.ru.md">Русский</a> | <strong>Українська</strong> | <a href="README.nl.md">Nederlands</a>
</div>

<br />

<div align="center">
  <h3><strong>ШІ розумний. Але в безладному середовищі він губиться.</strong></h3>
  <p><strong>TRAE Starter — це простий шаблон, що базується на штучному інтелекті, який забезпечує ідеальне бачення TRAE IDE.</strong></p>

  <p>Припиніть витрачати токени, страждати від галюцинацій ШІ та боротися з контекстними межами. Кодування Vibe має відчуватися як магія, і тепер це так.</p>
</div>

> 📦 Безкоштовний шаблон від **andiupn** ([kuncimu.com](https://kuncimu.com)) · Ліцензовано відповідно до [ліцензії MIT](LICENSE)  
> ☕ Якщо це корисно, [приготуйте мені кави](https://ko-fi.com/andiupn) · 🚀 Потрібні функції monorepo, які мають перш за все статус? Спробуйте [PRO версію](https://github.com/sponsors/andiupn?frequency=monthly)

---

## 💡 Проблема: чому традиційні робочі простори зазнають невдачі ШІ
Редактори штучного інтелекту (наприклад, TRAE IDE) мають феноменальні можливості. Але коли їх опускають у стандартні захаращені каталоги, вони губляться. Вони читають невідповідні журнали, продувають ваш бюджет токенів, галюцинують і розміщують файли не в тих каталогах, оскільки немає чітких меж.

---

## ⚡ Рішення: три стовпи першокласних риштувань AI

### 1. 🛰️ Perfect Vision для TRAE IDE
Ми розробили кожну папку, конфігурацію та правило `.gitignore`, щоб діяти як дорожні карти для вашого ШІ. Робочий простір надзвичайно чистий, що дозволяє TRAE IDE зрозуміти всю архітектуру вашого проекту менш ніж за 3 секунди. Нуль марних жетонів, максимальна точність.

### 2. 🤖 Попередньо налаштована пам'ять проекту
Оснащено каталогом `.trae/memories/`. Ваш штучний інтелект тепер має спеціальне місце для зберігання налаштувань проекту, недоліків і архітектурних рішень, що запобігає повторенню інструкцій під час сеансів чату.

### 3. 📦 Веб-приклад пісочниці
Готова до роботи контейнеризована веб-пісочниця Nginx, щоб ви могли миттєво перевіряти зміни, тестувати правила та макети прототипів у реальному локальному середовищі.

---

## 📊 LITE vs PRO: преміум-оновлення

| Особливість | 🆓 LITE (безкоштовно) | 💎 PRO (Платно) |
|---|:---:|:---:|
| **Конфігурація правил** | Основні правила | Комплексний (веб/мобільний/вихід) |
| **Спеціалізовані навички** | 1 (тестування) | 2 (+перегляд коду, безпека) |
| **Спогади про проект** | Базове насіння | Повний і структурований |
| **Конвеєр робочого процесу** | Стандарт | Квест + Експертний режим |
| **Lisensi** | Ліцензія MIT | Власна комерційна |

👉 **[Переглянути повний посібник із порівняння функцій і оновлення](COMPARISON.md)**

---

## 📂 План робочого простору

```
your-workspace/
  .trae/               # Rules, commands, and long-term project memory
  assets/              # Screenshots and social previews
  public/              # HTML sandbox web files
  AGENTS.md            # Context & identity guidelines for your AI assistant
  LICENSE              # Project license (MIT License)
```

---

## 🚀 Розпочніть у 3 кроки

### 1. Клонуйте це сховище:

```bash
git clone https://github.com/andiupn/trae-starter.git
```

### 2. Запустіть веб-зразок:

```bash
docker run -d -p 9002:80 --name trae-starter-web -v $(pwd)/public:/usr/share/nginx/html nginx:alpine
```

*(Відкрийте http://localhost:9002, щоб переглянути демонстрацію).*

### 3. Почніть кодування:
Відкрийте цю папку в TRAE IDE, налаштуйте `.trae/memories/` специфікаціями вашого проекту та почніть кодувати Vibe!