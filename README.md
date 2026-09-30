# flyout.kr

Flyout 스마트 앱 링크 (GitHub Pages, 커스텀 도메인 flyout.kr).

- 앱 스토어 링크: `/` 기본, `/x/` X 광고, `/exo/` 엑소클릭 — 폴더명이 캠페인명. 캠페인 추가 = 폴더 만들고 index.html 복사.
- 웹 가입 중간 페이지(2026-09-30): 템플릿 `join/index.html`, 복사본 `/meta/`(인스타·페북) · `/naver/`(네이버 카페). flyout.fun/register 로 utm 붙여 보내고, 앱 안 브라우저(구글 로그인 막힘)는 크롬·사파리로 넘김. 폴더별 출처값은 파일 안 `CONF` 표, 표에 없는 폴더는 폴더명이 캠페인. `/join/?c=캠페인&s=출처&m=매체` 로 임시 링크. 템플릿 고치면 복사본도 다시 복사(md5 같아야 함). 시험 = `flyout-marketing/scripts/join_test.js <base>`.
- 원본 템플릿: `C:/Users/claude/gocue/site/flyout/app/index.html` (곰튀김.com/flyout/app 과 동일 로직, 로고 경로만 `/logo.png`).
- 클라우드플레어 Web Analytics 비콘 토큰은 flyout.kr 전용 사이트.
