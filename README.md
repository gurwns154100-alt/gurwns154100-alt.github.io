# 테마나침반 (주식 AI 사이트 키트 · 테마주형)

- 사이트 설정: `config.json` (이름·주소·시트 URL·색 `theme`·문구 `copy`·기능 `features`)
- **테마 사전: `themes.json`** — 테마 이름·설명·관련 종목(정확한 종목명). 고치면 다음 실행부터 반영
- 고유 기능: 테마 지도(`/theme/`), 테마별 관련주 페이지(`/theme/영문이름/`), 메인 테마 히트맵,
  종목 페이지 '속한 테마' 표시, AI 테마 코멘트, 매일 '테마별 등락률 순위' 리포트
- 작업 방법: `CLAUDE.md` (Claude가 읽는 지시서) 참고
- 로컬 미리보기: `pip install -r requirements.txt` → `DEMO_NEWS=1 python build.py --demo` → `python -m http.server 8000 --directory site`
- 배포 전 `site/`, `posts/` 폴더는 지우세요 (데모 데이터).
