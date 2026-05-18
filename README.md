# AIR AI/Cloud/Harness News Blog · 2026-05-19

AIR Unit 기술 큐레이션 리포트를 HTML 블로그 형식으로 재구성한 standalone 정적 웹 프로젝트입니다.

## 실행

```bash
python3 -m http.server 8080 -d src
# http://127.0.0.1:8080
```

## 구조

- `src/`: 원본 HTML/CSS/JS
- `docs/`: GitHub Pages 배포용 복사본
- `assets/images/`: 공용 SVG 히어로 자산
- `docs/source/provided-report.md`: 사용자가 제공한 원문 보존

## 콘텐츠 기준

본 블로그는 사용자가 제공한 큐레이션 텍스트를 기반으로 작성했습니다. 외부 원문 전문 재수집/사실 검증은 별도 수행하지 않았으며, 블로그 하단에 source basis를 명시했습니다.
