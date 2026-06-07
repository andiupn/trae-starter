# TRAE Starter 🛰️
<!--
  Scaffolded by Andi UPN (https://github.com/andiupn)
  Official Website & Support: https://kuncimu.com
  Licensed under MIT License
-->

<div align="center">
  <strong>English</strong> | <a href="README.id.md">Bahasa Indonesia</a>
</div>

<br />

<div align="center">
  <h3><strong>AI is smart. But in a messy environment, it gets lost.</strong></h3>
  <p><strong>TRAE Starter is a clean, AI-first template that gives TRAE IDE perfect vision.</strong></p>

  <p>Stop wasting tokens, suffering from AI hallucinations, and struggling with context boundaries. Vibe coding should feel like magic—and now it does.</p>
</div>

> 📦 Free template by **andiupn** ([kuncimu.com](https://kuncimu.com)) · Licensed under [MIT License](LICENSE)  
> ☕ If useful, [buy me a coffee](https://ko-fi.com/andiupn) · 🚀 Need status-first monorepo features? Try the [PRO version](https://github.com/sponsors/andiupn?frequency=monthly)

---

## 💡 The Problem: Why Traditional Workspaces Fail AI
AI Editors (like TRAE IDE) are phenomenally capable. But when dropped into standard, cluttered directories, they get lost. They read irrelevant logs, blow through your token budget, hallucinate, and place files in the wrong directories because there are no clear boundaries.

---

## ⚡ The Solution: Three Pillars of Premium AI Scaffolding

### 1. 🛰️ Perfect Vision for TRAE IDE
We designed every folder, config, and `.gitignore` rule to act as roadmaps for your AI. The workspace is extremely clean, allowing TRAE IDE to understand your entire project architecture in less than 3 seconds. Zero wasted tokens, maximum accuracy.

### 2. 🤖 Pre-Configured Project Memory
Equipped with `.trae/memories/` directory. Your AI now has a dedicated place to store project preferences, gotchas, and architectural decisions, preventing you from repeating instructions across chat sessions.

### 3. 📦 Sandbox Web Sample
A ready-to-run containerized Nginx web sandbox so you can instantly verify changes, test rules, and prototype layouts in a live local environment.

---

## 📊 LITE vs PRO: The Premium Upgrade

| Feature | 🆓 LITE (Free) | 💎 PRO (Paid) |
|---|:---:|:---:|
| **Rules Configuration** | Basic rules | Comprehensive (Web/Mobile/Output) |
| **Specialized Skills** | 1 (testing) | 2 (+ code-review, security) |
| **Project Memories** | Basic Seed | Complete & Structured |
| **Workflow Pipeline** | Standard | Quest + Expert Mode |
| **Lisensi** | MIT License | Proprietary Commercial |

👉 **[View Full Feature Comparison & Upgrade Guide](COMPARISON.md)**

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

## 🚀 Get Started in 3 Steps

### 1. Clone this repository:
```bash
git clone https://github.com/andiupn/trae-starter.git
```

### 2. Run the Web Sample:
```bash
docker run -d -p 9002:80 --name trae-starter-web -v $(pwd)/public:/usr/share/nginx/html nginx:alpine
```
*(Open http://localhost:9002 to view the demo).*

### 3. Start Coding:
Open this folder in TRAE IDE, customize `.trae/memories/` with your project specs, and begin vibe coding!
