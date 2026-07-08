# Stone & Time — Web (돌과 시간 웹 프로토타입)

2D 메트로배니아 「돌과 시간」의 웹 프로토타입 & 티저 페이지.

> "아무도 부탁하지 않았다, 그래도 멈추지 않았다."

## 구성

| 파일 | 내용 |
|---|---|
| `index.html` | **게임 소개(티저)** — 스크롤 시 색이 돌아오는 원페이지. 사이트 랜딩 |
| `play.html` | **여정 프로토타입** — 파츠 리그 골렘 조작(걷기·점프), 이어진 4구간 세계, 격변(흑백→컬러), 2막 회귀, BGM/SFX |
| `world.html` | (예정) 세계관 소개 — StoryWiki 볼트에서 생성 |
| `story.html` | (예정) 스토리 소개 — StoryWiki 볼트에서 생성 |
| `assets/` | 웹 최적화 에셋 (배경 흑백/컬러 페어, 골렘 파츠, BGM mp3) |
| `docs/` | 소개 페이지 디자인 프레임, 지역 배경 프롬프트 킷 |

## 실행

빌드 불필요 — 정적 파일. 로컬에서:

```bash
npx serve .        # 또는 python -m http.server
```

브라우저에서 `index.html` 열기. (BGM은 http 서빙 시에만 정상 재생되는 브라우저가 있음)

**조작**: ←→ 걷기 · Space/↑ 점프 · 모바일: 화면 좌/우 홀드, 짧은 탭 점프

## 배포

정적 사이트라 GitHub Pages로 바로 배포 가능: Settings → Pages → Branch `main` / root.

## 원본 에셋

고해상도 원본(WAV, 8K PNG)은 이 저장소에 포함하지 않음 — 팀 Google Drive에서 관리.
설정·스토리의 단일 진실 원천은 옵시디언 StoryWiki 볼트.

## 크레딧

- 기획/스토리: 정석현 · 2D 아트: sky0ghima · 사운드: dlehfid123 (Suno 시안)
- 웹 구현: Claude (Anthropic) 협업
- 모든 이미지·음원은 개발 중 시안입니다
