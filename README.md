# 🛒 쇼핑 리스트 앱

**배포 URL**: https://king2jjang.github.io/shopping-list-app/

간단하게 쓸 수 있는 쇼핑 리스트 웹 앱입니다. 별도 설치 없이 브라우저에서 바로 실행되며, 항목은 `localStorage`에 저장되어 새로고침해도 유지됩니다.

## 기능

- 아이템 추가 (버튼 클릭 또는 Enter 키)
- 체크박스로 완료 표시 / 해제
- 개별 항목 삭제
- 완료 항목 일괄 삭제
- 총 개수 · 완료 · 남은 항목 통계 표시
- localStorage 기반 데이터 영구 저장

## 사용 방법

별도 서버나 빌드 과정이 필요 없습니다.

```bash
# 저장소 클론
git clone https://github.com/king2jjang/shopping-list-app.git

# shopping-list.html 파일을 브라우저로 열기
open shopping-list.html
```

## 기술 스택

- HTML5
- CSS3
- Vanilla JavaScript
- Web Storage API (localStorage)
