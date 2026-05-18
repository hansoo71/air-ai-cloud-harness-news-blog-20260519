# SKILLS.md

## 자연어 수정 예시
- “주요 뉴스 5건을 3건으로 줄이고 Presales 메시지를 더 임원 보고서처럼 바꿔줘.”
- “폐쇄망 소버린 AI 아키텍처 다이어그램을 추가해줘.”
- “GitHub Pages 배포본과 Telegram standalone HTML을 다시 동기화해줘.”

## 반복 작업 규칙
1. `src/`를 canonical source로 수정한다.
2. `docs/`에 동일 파일과 자산을 복사한다.
3. standalone HTML은 `/opt/data/out/`에 별도 생성한다.
4. 로컬 HTTP와 핵심 문자열 검증 후 commit/push한다.
