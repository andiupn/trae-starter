#TRAE Iniciador 🛰️
<!--
  Scaffolded by Andi UPN (https://github.com/andiupn)
  Official Website & Support: https://kuncimu.com
  Licensed under MIT License
-->

<div align="center">
  <a href="README.md">English</a> | <a href="README.id.md">Bahasa Indonesia</a> | <a href="README.zh.md">简体中文</a> | <a href="README.hi.md">हिन्दी</a> | <a href="README.fr-ca.md">Français (CA)</a> | <a href="README.de.md">Deutsch</a> | <a href="README.fr.md">Français</a> | <a href="README.pt-br.md">Português (BR)</a> | <a href="README.vi.md">Tiếng Việt</a> | <a href="README.pl.md">Polski</a> | <a href="README.ja.md">日本語</a> | <a href="README.ko.md">한국어</a> | <strong>Español</strong> | <a href="README.tr.md">Türkçe</a> | <a href="README.it.md">Italiano</a> | <a href="README.ru.md">Русский</a> | <a href="README.uk.md">Українська</a> | <a href="README.nl.md">Nederlands</a> | <a href="README.sv.md">Svenska</a> | <a href="README.ro.md">Română</a>
</div>
<br>

<div align="center">
  <h3><strong>AI es inteligente. Pero en un entorno desordenado, se pierde.</strong></h3>
  <p><strong>TRAE Starter es una plantilla limpia basada en IA que brinda a TRAE IDE una visión perfecta.</strong></p>

  <p>Deja de desperdiciar tokens, sufrir alucinaciones de IA y luchar con los límites del contexto. La codificación Vibe debería parecer mágica, y ahora lo es.</p>
</div>

> 📦 Plantilla gratuita de **andiupn** ([kuncimu.com](https://kuncimu.com)) · Licenciado bajo [Licencia MIT](LICENSE)  
> ☕ Si es útil, [cómprame un café](https://ko-fi.com/andiupn) · 🚀 ¿Necesitas funciones monorepo que prioricen el estado? Pruebe la [versión PRO](https://github.com/sponsors/andiupn?frequency=monthly)

---

## 💡 El problema: por qué los espacios de trabajo tradicionales fallan en la IA
Los editores de IA (como TRAE IDE) son fenomenalmente capaces. Pero cuando se los coloca en directorios estándar y abarrotados, se pierden. Leen registros irrelevantes, gastan su presupuesto de tokens, alucinan y colocan archivos en directorios equivocados porque no hay límites claros.

---

## ⚡ La solución: tres pilares del andamiaje de IA premium

### 1. 🛰️ Visión perfecta para TRAE IDE
Diseñamos cada carpeta, configuración y regla `.gitignore` para que actúen como hojas de ruta para su IA. El espacio de trabajo es extremadamente limpio, lo que permite a TRAE IDE comprender toda la arquitectura de su proyecto en menos de 3 segundos. Cero tokens desperdiciados, máxima precisión.

### 2. 🤖 Memoria de proyecto preconfigurada
Equipado con el directorio `.trae/memories/`. Su IA ahora tiene un lugar dedicado para almacenar las preferencias del proyecto, los errores y las decisiones arquitectónicas, lo que le impide repetir instrucciones en las sesiones de chat.

### 3. 📦 Muestra web Sandbox
Un entorno de pruebas web Nginx en contenedores listo para ejecutar para que pueda verificar instantáneamente cambios, probar reglas y diseños de prototipos en un entorno local en vivo.

---

## 📊 LITE vs PRO: La actualización Premium

| Característica | 🆓 LITE (Gratis) | 💎 PRO (Pago) |
|---|:---:|:---:|
| **Configuración de reglas** | Reglas básicas | Integral (Web/Móvil/Salida) |
| **Habilidades especializadas** | 1 (pruebas) | 2 (+ revisión de código, seguridad) |
| **Recuerdos del proyecto** | Semilla Básica | Completo y estructurado |
| **Canalización de flujo de trabajo** | Estándar | Modo Misión + Experto |
| **Lisensi** | Licencia MIT | Comercial Propietario |

👉 **[Ver guía de actualización y comparación de funciones completas](COMPARISON.md)**

---

## 📂 Plano del espacio de trabajo

```
your-workspace/
  .trae/               # Rules, commands, and long-term project memory
  assets/              # Screenshots and social previews
  public/              # HTML sandbox web files
  AGENTS.md            # Context & identity guidelines for your AI assistant
  LICENSE              # Project license (MIT License)
```

---

## 🚀 Comience en 3 pasos

### 1. Clona este repositorio:

```bash
git clone https://github.com/andiupn/trae-starter.git
```

### 2. Ejecute el ejemplo web:

```bash
docker run -d -p 9002:80 --name trae-starter-web -v $(pwd)/public:/usr/share/nginx/html nginx:alpine
```

*(Abra http://localhost:9002 para ver la demostración).*

### 3. Comience a codificar:
Abra esta carpeta en TRAE IDE, personalice `.trae/memories/` con las especificaciones de su proyecto y comience a codificar en ambiente.