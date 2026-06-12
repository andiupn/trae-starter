# TRAE 스타터 🛰️
<!--
  Scaffolded by Andi UPN (https://github.com/andiupn)
  Official Website & Support: https://kuncimu.com
  Licensed under MIT License
-->

<div align="center">
  <a href="README.md">English</a> | <a href="README.id.md">Bahasa Indonesia</a> | <a href="README.zh.md">简体中文</a> | <a href="README.hi.md">हिन्दी</a> | <a href="README.fr-ca.md">Français (CA)</a> | <a href="README.de.md">Deutsch</a> | <a href="README.fr.md">Français</a> | <a href="README.pt-br.md">Português (BR)</a> | <a href="README.vi.md">Tiếng Việt</a> | <a href="README.pl.md">Polski</a> | <a href="README.ja.md">日本語</a> | <strong>한국어</strong> | <a href="README.es.md">Español</a> | <a href="README.tr.md">Türkçe</a> | <a href="README.it.md">Italiano</a> | <a href="README.ru.md">Русский</a> | <a href="README.uk.md">Українська</a> | <a href="README.nl.md">Nederlands</a> | <a href="README.sv.md">Svenska</a> | <a href="README.ro.md">Română</a>
</div>
<br>

<div align="center">
  <h3><strong>AI는 똑똑합니다. 하지만 지저분한 환경에서는 길을 잃게 됩니다.</strong></h3>
  <p><strong>TRAE Starter는 TRAE IDE에 완벽한 비전을 제공하는 깔끔한 AI 우선 템플릿입니다.</strong></p>

  <p>토큰 낭비, AI 환각으로 고통받고 컨텍스트 경계로 인해 어려움을 겪지 마세요. Vibe 코딩은 마치 마법처럼 느껴져야 합니다. 이제 실제로 그렇습니다.</p>
</div>

> 📦 **andiupn**([kuncimu.com](https://kuncimu.com))의 무료 템플릿 · [MIT 라이선스](LICENSE)에 따라 라이선스가 부여됨  
> 주의 도움이 된다면 [커피 사주세요](https://ko-fi.com/andiupn) · 🚀 상태 우선 모노레포 기능이 필요하신가요? [PRO 버전](https://github.com/sponsors/andiupn?frequency=monthly)을 사용해 보세요.

---

## 💡 문제: 기존 작업 공간이 AI에 실패하는 이유
TRAE IDE와 같은 AI 편집기는 놀라운 능력을 갖추고 있습니다. 그러나 표준적이고 어수선한 디렉토리에 넣으면 길을 잃습니다. 그들은 관련 없는 로그를 읽고, 토큰 예산을 날려버리고, 환각을 느끼고, 명확한 경계가 없기 때문에 잘못된 디렉터리에 파일을 배치합니다.

---

## ⚡ 솔루션: 프리미엄 AI 비계의 세 가지 기둥

### 1. 🛰️ TRAE IDE를 위한 완벽한 비전
우리는 AI의 로드맵 역할을 하도록 모든 폴더, 구성 및 `.gitignore` 규칙을 설계했습니다. 작업 공간은 매우 깨끗하여 TRAE IDE가 3초 이내에 전체 프로젝트 아키텍처를 이해할 수 있습니다. 낭비되는 토큰이 없고 정확도가 극대화됩니다.

### 2. 🤖 사전 구성된 프로젝트 메모리
`.trae/memories/` 디렉토리를 갖추고 있습니다. 이제 AI에는 프로젝트 기본 설정, 문제 및 아키텍처 결정을 저장하는 전용 공간이 있어 채팅 세션 전반에 걸쳐 지침을 반복하지 않아도 됩니다.

### 3. 📦 샌드박스 웹 샘플
즉시 실행 가능한 컨테이너화된 Nginx 웹 샌드박스로, 라이브 로컬 환경에서 변경 사항, 테스트 규칙 및 프로토타입 레이아웃을 즉시 확인할 수 있습니다.

---

## 📊 LITE 대 PRO: 프리미엄 업그레이드

| 기능 | 🆓 LITE(무료) | 💎 PRO(유료) |
|---|:---:|:---:|
| **규칙 구성** | 기본 규칙 | 종합(웹/모바일/출력) |
| **전문 기술** | 1(테스트) | 2 (+ 코드 검토, 보안) |
| **프로젝트 추억** | 기본 씨앗 | 완전하고 구조화된 |
| **워크플로 파이프라인** | 표준 | 퀘스트 + 전문가 모드 |
| **라이센시** | MIT 라이센스 | 독점 상업용 |

👉 **[전체 기능 비교 및 업그레이드 가이드 보기](COMPARISON.md)**

---

## 📂 작업 공간 청사진

```
your-workspace/
  .trae/               # Rules, commands, and long-term project memory
  assets/              # Screenshots and social previews
  public/              # HTML sandbox web files
  AGENTS.md            # Context & identity guidelines for your AI assistant
  LICENSE              # Project license (MIT License)
```

---

## 🚀 3단계로 시작하기

### 1. 이 저장소를 복제합니다.

```bash
git clone https://github.com/andiupn/trae-starter.git
```

### 2. 웹 샘플을 실행합니다.

```bash
docker run -d -p 9002:80 --name trae-starter-web -v $(pwd)/public:/usr/share/nginx/html nginx:alpine
```

*(데모를 보려면 http://localhost:9002를 여세요).*

### 3. 코딩 시작:
TRAE IDE에서 이 폴더를 열고 프로젝트 사양에 맞게 `.trae/memories/`을 사용자 정의한 후 바이브 코딩을 시작하세요!