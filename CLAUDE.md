# CLAUDE.md

This file provides guidance to Claude Code (claude.ai/code) when working with code in this repository.

## 실행 방법

빌드나 설치 과정 없이 `index.html`을 브라우저에서 직접 열면 됩니다.

```bash
open index.html
```

## 아키텍처

단일 파일(`index.html`) 앱으로, HTML/CSS/JS가 한 파일에 포함되어 있습니다.

- **상태**: `items` 배열 (메모리) — `{ text: string, done: boolean }` 객체의 배열
- **영속성**: `localStorage` 키 `shoppingItems`에 JSON 직렬화하여 저장
- **렌더링**: `render()` 함수가 상태 변경 시마다 `<ul>` 전체를 재생성 (가상 DOM 없음)

## GitHub 배포

- 저장소: https://github.com/king2jjang/shopping-list-app
- GitHub Pages: Settings > Pages > Branch: main / (root) 에서 활성화하면 `https://king2jjang.github.io/shopping-list-app/` 으로 서비스

## 주의사항

- `.env`와 `.playwright-mcp/`는 `.gitignore`에 등록되어 있으므로 커밋하지 않음
