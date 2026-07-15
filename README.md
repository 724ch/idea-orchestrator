# IDEA Orchestrator

손동작 인터랙션이 들어간 단일 페이지 아이디어 보드.

→ **바로 써보기**: <https://724ch.github.io/idea-orchestrator/>
→ **케이스 스터디**: <https://724ch.github.io/idea-orchestrator/case-study.html>

## 사용법

- 캔버스 아무 곳이나 클릭 → 바로 입력
- 노트 어디든 드래그로 이동 · 더블클릭으로 텍스트 편집 · ⌘Z로 되돌리기
- Shift+클릭으로 두 노트 연결 (같은 쌍을 다시 누르면 해제)
- `Hand` 버튼 → 카메라 손동작 인식. 오른손=조작, 왼손=보조 modifier(핀·팬·연결)
- 이미지 파일을 드롭하거나 ⌘V로 붙여넣기 → 이미지 노트

## 스택

Vanilla JS · D3.js(트리 레이아웃) · MediaPipe Hands · Pretendard · localStorage.
빌드 도구 없음, 프레임워크 없음 — HTML + CSS 두 파일.
