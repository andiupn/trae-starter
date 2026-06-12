#TRAE Iniciante 🛰️
<!--
  Scaffolded by Andi UPN (https://github.com/andiupn)
  Official Website & Support: https://kuncimu.com
  Licensed under MIT License
-->

<div align="center">
  <strong>Inglês</strong> | <a href="README.id.md">Bahasa Indonésia</a> | <a href="README.zh.md">简体中文</a> | <a href="README.hi.md">हिन्दी</a> | <a href="README.fr-ca.md">Français (CA)</a> | <a href="README.de.md">Alemão</a> | <a href="README.fr.md">Français</a> | <a href="README.pt-br.md">Português (BR)</a> | <a href="README.vi.md">Tiếng Việt</a> | <a href="README.pl.md">Polski</a>
</div>

<br />

<div align="center">
  <h3><strong>AI é inteligente. Mas em um ambiente confuso, ele se perde.</strong></h3>
  <p><strong>TRAE Starter é um modelo limpo e baseado em IA que oferece ao TRAE IDE uma visão perfeita.</strong></p>

  <p>Pare de desperdiçar tokens, sofrer de alucinações de IA e lutar com limites de contexto. A codificação do Vibe deveria parecer mágica - e agora parece.</p>
</div>

> 📦 Modelo gratuito de **andiupn** ([kuncimu.com](https://kuncimu.com)) · Licenciado sob [Licença MIT](LICENSE)  
> ☕ Se for útil, [me compre um café](https://ko-fi.com/andiupn) · 🚀 Precisa de recursos de monorepo que priorizam o status? Experimente a [versão PRO](https://github.com/sponsors/andiupn?frequency=monthly)

---

## 💡 O problema: por que os espaços de trabalho tradicionais falham na IA
Editores de IA (como TRAE IDE) são fenomenalmente capazes. Mas quando colocados em diretórios padrão e desordenados, eles se perdem. Eles leem registros irrelevantes, estouram seu orçamento de tokens, têm alucinações e colocam arquivos nos diretórios errados porque não há limites claros.

---

## ⚡ A solução: três pilares do andaime de IA premium

### 1. 🛰️ Visão perfeita para TRAE IDE
Projetamos cada pasta, configuração e regra `.gitignore` para funcionar como roteiros para sua IA. O espaço de trabalho é extremamente limpo, permitindo que o TRAE IDE entenda toda a arquitetura do seu projeto em menos de 3 segundos. Zero tokens desperdiçados, precisão máxima.

### 2. 🤖 Memória de projeto pré-configurada
Equipado com diretório `.trae/memories/`. Sua IA agora tem um local dedicado para armazenar preferências de projeto, dicas e decisões arquitetônicas, evitando que você repita instruções em sessões de chat.

### 3. 📦 Amostra da Web Sandbox
Um sandbox da web Nginx em contêiner pronto para execução para que você possa verificar instantaneamente alterações, testar regras e layouts de protótipo em um ambiente local ativo.

---

## 📊 LITE vs PRO: a atualização premium

| Recurso | 🆓 LITE (grátis) | 💎 PRO (pago) |
|---|:---:|:---:|
| **Configuração de regras** | Regras básicas | Abrangente (Web/Mobile/Output) |
| **Habilidades especializadas** | 1 (teste) | 2 (+ revisão de código, segurança) |
| **Memórias do Projeto** | Semente Básica | Completo e Estruturado |
| **Pipeline de fluxo de trabalho** | Padrão | Missão + Modo Especialista |
| **Licenciamento** | Licença MIT | Comercial Proprietário |

👉 **[Ver comparação completa de recursos e guia de atualização](COMPARISON.md)**

---

## 📂 Projeto do espaço de trabalho

```
your-workspace/
  .trae/               # Rules, commands, and long-term project memory
  assets/              # Screenshots and social previews
  public/              # HTML sandbox web files
  AGENTS.md            # Context & identity guidelines for your AI assistant
  LICENSE              # Project license (MIT License)
```

---

## 🚀 Comece em 3 etapas

### 1. Clone este repositório:

```bash
git clone https://github.com/andiupn/trae-starter.git
```

### 2. Execute o exemplo da Web:

```bash
docker run -d -p 9002:80 --name trae-starter-web -v $(pwd)/public:/usr/share/nginx/html nginx:alpine
```

*(Abra http://localhost:9002 para ver a demonstração).*

### 3. Comece a codificar:
Abra esta pasta no TRAE IDE, personalize `.trae/memories/` com as especificações do seu projeto e comece a codificação do vibe!