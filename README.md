# 한글 떼기 (Korean for Kids)

5살 아이를 위한 한글 학습 웹앱. iPad / iPhone Safari에서 동작.

## 데모

GitHub Pages 활성화 후: `https://viscozegit.github.io/korean-for-kids/`

## 현재 상태

**MVP**: 홈 → 자음 14자 / 모음 10자 그리드 → 3단계 학습(보고 듣기 / 따라 쓰기 / 미니 퀴즈) → 보상. 진도는 localStorage에 자동 저장.

**다음 단계 예정**: 부모 메뉴, 스티커 컬렉션, UI 다듬기.

- 메인 앱: [`/`](https://viscozegit.github.io/korean-for-kids/) (index.html)
- 핵심 기술 검증 페이지: [`/test.html`](https://viscozegit.github.io/korean-for-kids/test.html) — TTS 음성 목록 확인, 트레이싱 디버그용

## 학습 범위 (MVP)

- 자음 14자: ㄱ ㄴ ㄷ ㄹ ㅁ ㅂ ㅅ ㅇ ㅈ ㅊ ㅋ ㅌ ㅍ ㅎ
- 모음 10자: ㅏ ㅑ ㅓ ㅕ ㅗ ㅛ ㅜ ㅠ ㅡ ㅣ

## 문서

- [PRD.md](PRD.md) — 제품 요구사항
- [WIREFRAME.md](WIREFRAME.md) — 화면 와이어프레임

## 사용 방법

iPad/iPhone Safari에서 위 데모 URL 접속.

**중요**: 첫 진입 시 "🔊 오디오 켜기" 버튼을 한 번 눌러야 TTS가 활성화됩니다 (iOS 보안 정책).

## 기술 스택

- Vanilla HTML / CSS / JavaScript (빌드 없음)
- Web Speech API (TTS)
- HTML Canvas (트레이싱)
- localStorage (진도 저장 — 예정)
