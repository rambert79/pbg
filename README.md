# PBG
Play Board Games

브라우저에서 바로 실행되는 웹 게임 모음입니다. 루트의 `index.html`이 메인 허브이며, 각 게임은 독립된 폴더로 관리합니다.

## 게임 목록

| 폴더 | 게임 | 설명 |
|---|---|---|
| [`badge-reversi/`](badge-reversi/) | Badge Reversi | 이모지 배지로 즐기는 리버시 (PWA 지원) |
| [`exodus-red-sea/`](exodus-red-sea/) | Exodus: Red Sea | 말씀을 타이핑하여 바다를 가르는 게임 |
| [`bible-card-memory/`](bible-card-memory/) | Bible Card Memory | 성경 인물 카드 짝 맞추기 팀 대결 |
| [`jabbok-night/`](jabbok-night/) | 얍복 강의 밤 | 천사와 씨름한 야곱 이야기 (창세기 32장), 씨름·퀴즈 게임 |
| [`creation-days/`](creation-days/) | 창조의 7일 | 창세기 1장, 7일간의 창조를 말씀대로 수행하는 3D 오픈맵 (Three.js 포함) |

## 구조

```
index.html            # 메인 허브 (공용)
LICENSE
README.md
<game>/index.html     # 각 게임 (CSS/JS 인라인)
<game>/...            # 해당 게임 전용 리소스만 게임 폴더 안에 보관
```

## 실행

정적 사이트이므로 `index.html`을 브라우저로 열거나 GitHub Pages로 배포하면 됩니다.

## License
MIT
