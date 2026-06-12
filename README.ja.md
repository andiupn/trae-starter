#TRAE スターター 🛰️
<!--
  Scaffolded by Andi UPN (https://github.com/andiupn)
  Official Website & Support: https://kuncimu.com
  Licensed under MIT License
-->

<div align="center">
  <a href="README.md">English</a> | <a href="README.id.md">Bahasa Indonesia</a> | <a href="README.zh.md">简体中文</a> | <a href="README.hi.md">हिन्दी</a> | <a href="README.fr-ca.md">Français (CA)</a> | <a href="README.de.md">Deutsch</a> | <a href="README.fr.md">Français</a> | <a href="README.pt-br.md">Português (BR)</a> | <a href="README.vi.md">Tiếng Việt</a> | <a href="README.pl.md">Polski</a> | <strong>日本語</strong> | <a href="README.ko.md">한국어</a> | <a href="README.es.md">Español</a> | <a href="README.tr.md">Türkçe</a> | <a href="README.it.md">Italiano</a> | <a href="README.ru.md">Русский</a> | <a href="README.uk.md">Українська</a> | <a href="README.nl.md">Nederlands</a>
</div>

<br />

<div align="center">
  <h3><strong>AI は賢いです。しかし、乱雑な環境では紛失してしまいます。</strong></h3>
  <p><strong>TRAE Starter は、TRAE IDE に完璧なビジョンを与えるクリーンな AI ファーストのテンプレートです。</strong></p>

  <p>トークンの無駄遣い、AI の幻覚に悩まされること、コンテキストの境界に悩まされることはもうやめましょう。 Vibe コーディングは魔法のように感じられるはずですが、今では魔法のように感じられます。</p>
</div>

> 📦 **andiupn** による無料テンプレート ([kuncimu.com](https://kuncimu.com)) · [MIT ライセンス](LICENSE) に基づいてライセンスされています  
> ☕ 役に立ったら、[コーヒーを買ってきてください](https://ko-fi.com/andiupn) · 🚀 ステータス優先のモノリポジトリ機能が必要ですか? [PRO バージョン](https://github.com/sponsors/andiupn?frequency=monthly) をお試しください

---

## 💡 問題: 従来のワークスペースが AI に失敗する理由
AI エディター (TRAE IDE など) は驚異的な能力を持っています。しかし、標準の乱雑なディレクトリにドロップすると、紛失してしまいます。明確な境界がないため、無関係なログを読み取り、トークンの予算を使い果たし、幻覚を起こし、ファイルを間違ったディレクトリに配置します。

---

## ⚡ ソリューション: プレミアム AI 足場の 3 つの柱

### 1. 🛰️ TRAE IDE の完璧なビジョン
すべてのフォルダー、構成、`.gitignore` ルールは、AI のロードマップとして機能するように設計されています。ワークスペースは非常にクリーンなので、TRAE IDE は 3 秒以内にプロジェクト アーキテクチャ全体を理解できます。無駄なトークンはゼロ、最高の精度。

### 2. 🤖 事前設定されたプロジェクトメモリ
`.trae/memories/` ディレクトリを装備。 AI には、プロジェクトの設定、注意事項、アーキテクチャ上の決定を保存するための専用の場所があり、チャット セッション間で指示を繰り返すことがなくなります。

### 3. 📦 サンドボックス Web サンプル
すぐに実行できるコンテナ化された Nginx Web サンドボックスにより、ライブ ローカル環境で変更、テスト ルール、プロトタイプ レイアウトを即座に検証できます。

---

## 📊 LITE vs PRO: プレミアムアップグレード

|特集 | 🆓 ライト (無料) | 💎PRO (有料) |
|---|:---:|:---:|
| **ルールの設定** |基本ルール |総合（Web/モバイル/アウトプット） |
| **専門スキル** | 1 (テスト) | 2 (+ コードレビュー、セキュリティ) |
| **プロジェクトの思い出** |基本シード |完全かつ構造化された |
| **ワークフロー パイプライン** |標準 |クエスト + エキスパート モード |
| **リセンシ** | MITライセンス |独自のコマーシャル |

👉 **[全機能の比較とアップグレード ガイドを表示](COMPARISON.md)**

---

## 📂 ワークスペースのブループリント

```
your-workspace/
  .trae/               # Rules, commands, and long-term project memory
  assets/              # Screenshots and social previews
  public/              # HTML sandbox web files
  AGENTS.md            # Context & identity guidelines for your AI assistant
  LICENSE              # Project license (MIT License)
```

---

## 🚀 3 ステップで始めましょう

### 1. このリポジトリのクローンを作成します。

```bash
git clone https://github.com/andiupn/trae-starter.git
```

### 2. Web サンプルを実行します。

```bash
docker run -d -p 9002:80 --name trae-starter-web -v $(pwd)/public:/usr/share/nginx/html nginx:alpine
```

*(デモを表示するには http://localhost:9002 を開いてください)。*

### 3. コーディングを開始します。
TRAE IDE でこのフォルダーを開き、プロジェクトの仕様に合わせて `.trae/memories/` をカスタマイズし、バイブ コーディングを開始します。