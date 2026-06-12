#TRAE Стартер 🛰️
<!--
  Scaffolded by Andi UPN (https://github.com/andiupn)
  Official Website & Support: https://kuncimu.com
  Licensed under MIT License
-->

<div align="center">
  <a href="README.md">English</a> | <a href="README.id.md">Bahasa Indonesia</a> | <a href="README.zh.md">简体中文</a> | <a href="README.hi.md">हिन्दी</a> | <a href="README.fr-ca.md">Français (CA)</a> | <a href="README.de.md">Deutsch</a> | <a href="README.fr.md">Français</a> | <a href="README.pt-br.md">Português (BR)</a> | <a href="README.vi.md">Tiếng Việt</a> | <a href="README.pl.md">Polski</a> | <a href="README.ja.md">日本語</a> | <a href="README.ko.md">한국어</a> | <a href="README.es.md">Español</a> | <a href="README.tr.md">Türkçe</a> | <a href="README.it.md">Italiano</a> | <strong>Русский</strong> | <a href="README.uk.md">Українська</a> | <a href="README.nl.md">Nederlands</a> | <a href="README.sv.md">Svenska</a> | <a href="README.ro.md">Română</a>
</div>
<br>

<div align="center">
  <h3><strong>ИИ умен. Но в беспорядке он теряется.</strong></h3>
  <p><strong>TRAE Starter — это чистый шаблон с ИИ, который обеспечивает идеальное видение TRAE IDE.</strong></p>

  <p>Хватит тратить токены, страдать от галлюцинаций ИИ и бороться с границами контекста. Программирование Vibe должно ощущаться как волшебство — и теперь оно так и есть.</p>
</div>

> 📦 Бесплатный шаблон от **andiupn** ([kuncimu.com](https://kuncimu.com)) · Лицензия [MIT License](LICENSE)  
> ☕ Если полезно, [купи мне кофе](https://ko-fi.com/andiupn) · 🚀 Нужны функции монорепозитория с приоритетом статуса? Попробуйте [PRO-версию](https://github.com/sponsors/andiupn?frequency=monthly)

---

## 💡 Проблема: почему традиционные рабочие пространства не справляются с искусственным интеллектом
Редакторы искусственного интеллекта (например, TRAE IDE) обладают феноменальными возможностями. Но при попадании в стандартные, захламленные каталоги они теряются. Они читают ненужные журналы, тратят ваш бюджет токенов, галлюцинируют и размещают файлы не в тех каталогах, потому что нет четких границ.

---

## ⚡ Решение: три столпа премиальной системы искусственного интеллекта

### 1. 🛰️ Perfect Vision для TRAE IDE
Мы разработали каждую папку, конфигурацию и правило `.gitignore` так, чтобы они служили дорожными картами для вашего ИИ. Рабочее пространство чрезвычайно чистое, что позволяет TRAE IDE понять всю архитектуру вашего проекта менее чем за 3 секунды. Ноль потраченных жетонов, максимальная точность.

### 2. 🤖 Предварительно настроенная память проекта
Оборудован каталогом `.trae/memories/`. У вашего ИИ теперь есть специальное место для хранения настроек проекта, ошибок и архитектурных решений, что позволяет вам не повторять инструкции во время сеансов чата.

### 3. 📦 Веб-пример песочницы
Готовая к использованию контейнерная веб-песочница Nginx, позволяющая мгновенно проверять изменения, тестировать правила и макеты прототипов в живой локальной среде.

---

## 📊 LITE против PRO: Премиум-обновление

| Особенность | 🆓 ЛАЙТ (бесплатно) | 💎 ПРО (Платный) |
|---|:---:|:---:|
| **Конфигурация правил** | Основные правила | Комплексный (Интернет/Мобильный/Вывод) |
| **Специальные навыки** | 1 (тестирование) | 2 (+ код-ревью, безопасность) |
| **Воспоминания о проекте** | Базовое семя | Полный и структурированный |
| **Конвейер рабочего процесса** | Стандарт | Квест + Экспертный режим |
| **Лисенси** | Лицензия MIT | Собственная коммерческая |

👉 **[Посмотреть полное руководство по сравнению функций и обновлению](COMPARISON.md)**

---

## 📂 План рабочего пространства

```
your-workspace/
  .trae/               # Rules, commands, and long-term project memory
  assets/              # Screenshots and social previews
  public/              # HTML sandbox web files
  AGENTS.md            # Context & identity guidelines for your AI assistant
  LICENSE              # Project license (MIT License)
```

---

## 🚀 Начните за 3 шага

### 1. Клонируйте этот репозиторий:

```bash
git clone https://github.com/andiupn/trae-starter.git
```

### 2. Запустите веб-пример:

```bash
docker run -d -p 9002:80 --name trae-starter-web -v $(pwd)/public:/usr/share/nginx/html nginx:alpine
```

*(Откройте http://localhost:9002 для просмотра демо).*

### 3. Начните кодирование:
Откройте эту папку в TRAE IDE, настройте `.trae/memories/` в соответствии со спецификациями вашего проекта и начните кодирование Vibe!