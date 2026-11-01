# AX 자동차 교육 — Textbook 파일 총정리

원본: [keerhee/kma-auto-genai-3-1 / Textbook](https://github.com/keerhee/kma-auto-genai-3-1/tree/main/Textbook)
(능률협회 「자동차산업과 생성형 AI 3-1」 교과서 · 정리일 2026-11-01)

> **공통 전제** — 거의 모든 장의 기본 도구는 **Claude 데스크톱 앱의 Code 탭(Claude Code)** 이며,
> Code 탭은 **유료 요금제(Pro · Max · Team · Enterprise)** 에서만 쓸 수 있습니다. 무료 요금제는 채팅만 됩니다.
> 요금 정보는 교재 작성 시점(2026년 10월) 기준이며 바뀔 수 있습니다.

## 파일별 정리

| 번호 | 파일명 (주요 프로그램) | 기능 (배우는 내용) | 구독조건 |
|---|---|---|---|
| 1 | `README.md` (목차) | 교과서 전체 목차 · 읽는 순서 · 업무별 바로가기 · 난이도(1~4단계) 안내 | 무료 (읽기용) |
| 2 | `00_교과서_기획.md` (기획 문서) | 독자 · 목표 · 4부 12장 + 부록 3 구성, 집필 규칙 | 무료 (읽기용) |
| 3 | `01장_AI와_일하는_준비.md` (Claude 데스크톱 · Claude Code · 스킬 · VS Code) | Claude 앱 설치, Code 탭으로 작업 폴더 열기, CLAUDE.md · 스킬 개념, 작업 폴더 정리 습관 | **유료** — Claude Pro 이상 (VS Code는 무료 · 선택) |
| 4 | `02장_산업의_전환점_읽기.md` (Claude · DART) | 테슬라 2008 · GM 2009 파산 · BYD 사례로 자동차 산업 전환점 읽기 | 무료 (읽기 중심) · 실습 시 Claude Pro 이상 |
| 5 | `03장_데이터를_그림으로.md` (Claude Code 스킬 · EGO Lite · Aside · Remotion) | 스킬로 인포그래픽 · 대시보드 만들기, AI 브라우저 자동화 | **유료** — Claude Pro 이상 · EGO Lite 무료 · Aside Free(월 500크레딧)/Pro $20/Max $200 |
| 6 | `04장_AI에게_일_잘_시키기.md` (Claude Code · Obsidian) | 프롬프트 작성, 하네스, 세컨드 브레인(옵시디언), RAG 챗봇 | **유료** — Claude Pro 이상 · Obsidian 무료 |
| 7 | `05장_숫자로_경쟁사_읽기.md` (DART 등 공시 · Docker · MCP · MiroFish) | 공시 실적 · 자동차 금융 분석, 지식그래프, AI 예측시장 시뮬레이션 | **유료** — Claude Pro 이상 · 공시 열람 무료 · 심화(MiroFish)는 Zep 계정 + API 키 2개 |
| 8 | `06장_GitHub로_내_자료_관리.md` (GitHub · GitHub CLI · GitHub Pages) | 저장소 만들기 · 커밋 · 푸시, Pages로 웹 공개 | **유료** — Claude Pro 이상 · GitHub Free 가능 |
| 9 | `07장_업무_에이전트_만들기.md` (Claude Code · 텔레그램 · Gmail · 카카오톡) | 판정 · 메신저 · 메일 · 뉴스레터 · 채용 심사단 에이전트 | **유료** — Claude Pro 이상 · 텔레그램/Gmail 무료 · API 사용 시 종량 과금 |
| 10 | `08장_에이전트를_팀으로.md` (ORCA · Codex · Gemini CLI) | 역할 분담 에이전트 팀, 여러 AI 동시 운영, 투자위원회 시뮬레이션 | **유료** — Claude Pro($20/월) 이상 · ORCA 무료 오픈소스 · Codex/Gemini는 각 구독 |
| 11 | `09장_스마트팩토리와_예지보전.md` (Claude Code · Python · GitHub Pages) | 설비 센서 데이터로 고장 예측(예지보전) 대시보드 | **유료** — Claude Pro 이상 · 선택 단계 AI 설명은 API 키 |
| 12 | `10장_업무_웹앱_처음부터_끝까지.md` (Supabase · Vercel · Cloudflare · Netlify · Stitch) | 요구사항 → 설계 → 개발 → 배포까지 업무 웹앱 제작, AICC 콘솔 | **유료** — Claude Pro 이상 · 배포 서비스 무료 플랜 (Vercel Hobby는 비상업용) |
| 13 | `11장_나만의_AI_업무시스템.md` (GitHub Pages · Cloudflare Access · 에고라이트 · Blender · Gemini) | 포트폴리오 사이트, SSR+, 내 강의 만들기, 콘텐츠 자동화 | **유료** — Claude Pro 이상 · 나머지 무료 (Gemini 무료 키 선택, 도메인만 유료) |
| 14 | `12장_로봇과_스마트팩토리_특강.md` (Claude Code · Python) | 로봇 SI 제안서 작성과 새 유형 대응 | **유료** — Claude Pro 이상 |
| 15 | `부록A_16주_자율학습_캠프.md` (n8n · NotebookLM · Claude API) | 책 이후 16주 자율학습 계획 | **유료** — Claude Pro 이상 · 14주차 n8n은 Claude API 종량 과금 |
| 16 | `부록B_용어집.md` (용어집) | 12개 장에 나온 용어 풀이 모음 | 무료 (읽기용) |
| 17 | `부록C_자료_찾아보기.md` (자료 색인) | 3-1B 실습 자료 59개 폴더 → 해당 장 연결 | 무료 (읽기용) |

※ `images/` 폴더는 교재 삽화 이미지라 표에서 제외했습니다.

## 구독조건 한눈에 보기

| 구분 | 프로그램 |
|---|---|
| **유료 (필수)** | Claude Pro 이상 (월 US$20~, Code 탭 사용 조건) |
| **유료 (선택 · 종량)** | Claude API 키, Aside Pro/Max, Codex · Gemini 유료 구독, 개인 도메인 |
| **무료** | VS Code, Obsidian, GitHub(Free) · GitHub Pages, EGO Lite, ORCA, Docker, 텔레그램, Gmail, Supabase · Vercel(Hobby) · Cloudflare · Netlify 무료 플랜, Blender, n8n, NotebookLM, 각국 공시 시스템(DART 등) |
