# PBG
Play Board Games

---
# 🕹️ Badge Reversi Ultimate

![Version](https://img.shields.io/badge/version-v29.1-brightgreen)
![Platform](https://img.shields.io/badge/platform-Web%20%7C%20Mobile-blue)
![License](https://img.shields.io/badge/license-MIT-lightgrey)

**Badge Reversi Ultimate**는 고전 게임인 리버시(오셀로)를 현대적인 감각으로 재해석한 웹 애플리케이션입니다. 외부 라이브러리 의존성 없이 순수 자바스크립트(Vanilla JS)로 구현되어 어떤 환경에서도 빠르고 안정적으로 작동합니다.

---

## ✨ 핵심 기능 (Key Features)

### 📱 완벽한 모바일 경험 (PWA)
- **전체 화면 실행:** `manifest.json` 설정을 통해 모바일 홈 화면에 추가 시 주소창 없는 단독 앱처럼 동작합니다.
- **반응형 UI:** 스마트폰, 태블릿, PC 등 모든 스크린 사이즈에 최적화된 레이아웃을 제공합니다.

### 🎨 시각 및 청각 효과
- **3D 배지 애니메이션:** CSS 3D Transforms를 이용해 배지가 실제로 뒤집히는 듯한 입체적인 효과를 구현했습니다.
- **순차적 플립(Staggered Flip):** 여러 개의 배지가 뒤집힐 때 시차를 두고 차례로 뒤집혀 타격감을 높였습니다.
- **자생적 사운드 엔진:** 별도의 MP3 파일 없이 Web Audio API를 통해 'Pop' 사운드와 승리 효과음을 실시간으로 생성합니다.

### 🛠️ 개발적 특징
- **Zero Dependency:** 외부 라이브러리(CDN) 차단이나 네트워크 오류 걱정 없이 `index.html` 단일 파일로 실행 가능합니다.
- **커스텀 테마:** 게임 시작 전 사용자가 원하는 이모지 배지와 보드 테마 색상을 직접 선택할 수 있습니다.

---

## 🚀 시작하기 (Quick Start)

1. 이 저장소의 모든 파일을 다운로드합니다.
2. `index.html` 파일을 더블 클릭하여 브라우저에서 실행합니다.
3. 모바일의 경우, 브라우저 메뉴에서 **'홈 화면에 추가'**를 누르면 앱처럼 사용할 수 있습니다.

---

## 📂 파일 구성 (Files)

- `index.html`: 게임 로직, UI 디자인, 사운드 엔진이 포함된 메인 파일
- `manifest.json`: 모바일 앱 설정 및 전체 화면 구동을 위한 설정 파일
- `favicon-badgereversi.png`: 게임 아이콘 및 파비콘 이미지 파일

---

## 🛠️ 기술 스택 (Tech Stack)

- **Frontend:** HTML5, CSS3 (Flexbox, Grid, 3D Transform)
- **Script:** JavaScript (ES6+, Web Audio API)
- **Deployment:** GitHub Pages 권장

---

## 📝 라이선스 (License)

- 이 프로젝트는 MIT 라이선스 하에 자유롭게 수정 및 배포가 가능합니다.
- Author: rambert79
