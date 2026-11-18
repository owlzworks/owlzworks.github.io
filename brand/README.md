# OwlzWorks 브랜드 에셋

> 이 폴더는 GitHub Pages로 함께 공개됩니다 (`owlzworks.github.io/brand/…`).

## 최종본 — Google Play 개발자 페이지

| 파일 | 용도 | 규격 |
|---|---|---|
| `google-play/developer-header.jpg` | **헤더 이미지 업로드용** | 4096×2304, JPG |
| `google-play/developer-header.png` | 헤더 무손실 원본 | 4096×2304, 24-bit PNG |
| `google-play/developer-icon.png` | **개발자 아이콘 업로드용** (Honey Lamp) | 512×512, 32-bit PNG |
| `google-play/developer-icon-2048.png` | 아이콘 고해상도 | 2048×2048 |
| `google-play/developer-icon.svg` | 아이콘 벡터 (인쇄·굿즈용) | SVG |

## 브랜드 기준

- **로고 원본**: `../assets/owl_logo_master_black.svg` / `_white.svg` (+ 투명 PNG)
- **표기**: `OwlzWorks` (URL·도메인은 소문자 `owlzworks`)
- **아이콘 컬러 — Honey Lamp**: 배경 `#FFF5DC` → `#FBE3B8` (위→아래 그라데이션), 부엉이 `#7A4122`
  - 홈페이지 파비콘(`../assets/favicon.svg`, `favicon.png`)도 같은 컬러
- **홈페이지**: 배경 `#F9F0DF`, 로고 `#6E4421`
- **헤더 글씨·로고**: `#3D2A1C`, 보조 `#5B4636`
- **글꼴** (Google Fonts): 워드마크 Fredoka 600 · 태그라인 Fredoka 500 · 본문 Nunito 600/700

## 헤더 다시 만들기

`google-play/source/header.html`이 헤더 템플릿입니다 (배경: 같은 폴더의 `header-bg.png`, 16:9).

1. `google-play/source/`에서 로컬 서버를 띄우고 `header.html`을 2048×1152 뷰포트로 엽니다.
2. 2배율로 캡처하면 4096×2304가 됩니다 (Play 규격).
3. 배경을 바꿀 땐 `header-bg.png`를 교체하고, 노트북 로고(`LID` 좌표)와 머그 로고(`.mug` 위치)를 새 배경에 맞게 조정합니다.

## explorations/

채택하지 않은 시안 기록입니다. 비교표(`icon-options-*`)와 시안별 SVG만 보관합니다 — PNG가 필요하면 SVG에서 다시 뽑으면 됩니다.

- `icons/studio/` — 헤더 그림에서 뽑은 팔레트 (Honey Lamp 채택)
- `icons/heritage/`, `heritage-light/` — 클래식 컬러
- `icons/pantone/`, `pantone-light/` — 팬톤 올해의 색상
