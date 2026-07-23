# 상인월드 소개서 (deck)

태경씨앤코 · 상인월드 프로젝트 소개서 HTML 슬라이드 (1920×1080, 26장).

## 실행
- `slides/20260722_상인월드소개서.html` 을 브라우저로 열면 됨. (루트 `index.html` 이 자동 리다이렉트)
- 네비: ←/→ 키, 우하단 툴바(이전/다음·전체화면·PDF 내보내기).
- 폰트(Pretendard)·아이콘(Lucide)은 CDN 로드 — 온라인에서 자동 표시. 오프라인이면 시스템 폰트로 폴백.

## 구조
```
slides/20260722_상인월드소개서.html          ← 덱 본체 (디자인 토큰·뷰어 JS 인라인, 자기완결)
projects/20260722_상인월드소개서/asset/       ← 덱이 참조하는 이미지 6개 (상대경로)
  logo.svg · hero_landing.png · news_segye.png
  policy_ai.png · policy_budget.png · policy_mss_survey.png
```

## PDF 내보내기
툴바의 다운로드 버튼(또는 브라우저 인쇄 → PDF로 저장). 배경 그래픽 켜기 권장.
