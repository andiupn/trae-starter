#TRAE Démarreur 🛰️
<!--
  Scaffolded by Andi UPN (https://github.com/andiupn)
  Official Website & Support: https://kuncimu.com
  Licensed under MIT License
-->

<div align="center">
  <a href="README.md">English</a> | <a href="README.id.md">Bahasa Indonesia</a> | <a href="README.zh.md">简体中文</a> | <a href="README.hi.md">हिन्दी</a> | <strong>Français (CA)</strong> | <a href="README.de.md">Deutsch</a> | <a href="README.fr.md">Français</a> | <a href="README.pt-br.md">Português (BR)</a> | <a href="README.vi.md">Tiếng Việt</a> | <a href="README.pl.md">Polski</a> | <a href="README.ja.md">日本語</a> | <a href="README.ko.md">한국어</a> | <a href="README.es.md">Español</a> | <a href="README.tr.md">Türkçe</a> | <a href="README.it.md">Italiano</a> | <a href="README.ru.md">Русский</a> | <a href="README.uk.md">Українська</a> | <a href="README.nl.md">Nederlands</a> | <a href="README.sv.md">Svenska</a> | <a href="README.ro.md">Română</a>
</div>
<br>

<div align="center">
  <h3><strong>AI est intelligent. Mais dans un environnement désordonné, cela se perd.</strong></h3>
  <p><strong>TRAE Starter est un modèle propre, axé sur l'IA, qui donne à TRAE IDE une vision parfaite.</strong></p>

  <p>Arrêtez de gaspiller des jetons, de souffrir d'hallucinations de l'IA et de lutter avec les limites du contexte. Le codage Vibe devrait ressembler à de la magie, et c'est désormais le cas.</p>
</div>

> 📦 Modèle gratuit par **andiupn** ([kuncimu.com](https://kuncimu.com)) · Sous licence [Licence MIT](LICENSE)  
> ☕ Si cela est utile, [achetez-moi un café](https://ko-fi.com/andiupn) · 🚀 Besoin de fonctionnalités monorepo axées sur le statut ? Essayez la [version PRO](https://github.com/sponsors/andiupn?frequency=monthly)

---

## 💡 Le problème : pourquoi les espaces de travail traditionnels échouent à l'IA
Les éditeurs IA (comme TRAE IDE) sont incroyablement performants. Mais lorsqu’ils sont déposés dans des répertoires standard et encombrés, ils se perdent. Ils lisent des journaux non pertinents, explosent votre budget symbolique, hallucinent et placent les fichiers dans les mauvais répertoires parce qu'il n'y a pas de limites claires.

---

## ⚡ La solution : trois piliers d'un échafaudage d'IA haut de gamme

### 1. 🛰️ Vision parfaite pour TRAE IDE
Nous avons conçu chaque dossier, configuration et règle `.gitignore` pour servir de feuilles de route pour votre IA. L'espace de travail est extrêmement propre, permettant à TRAE IDE de comprendre l'ensemble de l'architecture de votre projet en moins de 3 secondes. Zéro jeton gaspillé, précision maximale.

### 2. 🤖 Mémoire de projet préconfigurée
Equipé du répertoire `.trae/memories/`. Votre IA dispose désormais d'un emplacement dédié pour stocker les préférences du projet, les pièges et les décisions architecturales, vous évitant ainsi de répéter les instructions au cours des sessions de chat.

### 3. 📦 Exemple Web Sandbox
Un bac à sable Web Nginx conteneurisé prêt à l'emploi qui vous permet de vérifier instantanément les modifications, de tester les règles et les mises en page de prototypes dans un environnement local en direct.

---

## 📊 LITE vs PRO : la mise à niveau Premium

| Fonctionnalité | 🆓 LITE (Gratuit) | 💎 PRO (Payant) |
|---|:---:|:---:|
| **Configuration des règles** | Règles de base | Complet (Web/Mobile/Sortie) |
| **Compétences spécialisées** | 1 (test) | 2 (+ révision du code, sécurité) |
| **Souvenirs du projet** | Semences de base | Complet et structuré |
| **Pipeline de flux de travail** | Norme | Quête + Mode Expert |
| **Lisensi** | Licence MIT | Commercial exclusif |

👉 **[Voir la comparaison complète des fonctionnalités et le guide de mise à niveau](COMPARISON.md)**

---

## 📂 Plan d'espace de travail

```
your-workspace/
  .trae/               # Rules, commands, and long-term project memory
  assets/              # Screenshots and social previews
  public/              # HTML sandbox web files
  AGENTS.md            # Context & identity guidelines for your AI assistant
  LICENSE              # Project license (MIT License)
```

---

## 🚀 Commencez en 3 étapes

### 1. Clonez ce référentiel :

```bash
git clone https://github.com/andiupn/trae-starter.git
```

### 2. Exécutez l'exemple Web :

```bash
docker run -d -p 9002:80 --name trae-starter-web -v $(pwd)/public:/usr/share/nginx/html nginx:alpine
```

*(Ouvrez http://localhost:9002 pour voir la démo).*

### 3. Commencez à coder :
Ouvrez ce dossier dans TRAE IDE, personnalisez `.trae/memories/` avec les spécifications de votre projet et commencez le codage d'ambiance !