# BK-HQ

> 1인 CEO + AI 에이전트 팀이 운영하는 사업 체계

## 조직 구조

```
CEO (BK)
    ↓
Orchestrator
    ├── 법무팀 — 정책 · 컴플라이언스
    ├── 기획팀 — PRD · UX · UI
    ├── 마케팅팀 — 콘텐츠 · 실험 · 분석
    └── 개발팀 — FE · BE · QA · Eval
```

> 15개 AI 에이전트 · 4개 팀 · 4가지 워크플로우

## 기술 스택

| 영역 | 기술 |
|------|------|
| **Web** | Next.js 16+ (App Router) · TypeScript strict · Tailwind v3 + shadcn/ui |
| **DB** | Supabase \| Neon Serverless Postgres + Drizzle ORM |
| **Auth** | Supabase Auth \| BetterAuth |
| **Deploy** | Vercel · GitHub Actions |
| **Storage** | Supabase Storage · Cloudflare R2 |
| **Python** | 3.12+ · uv · ruff |
| **Package** | pnpm 9+ |

## 레포지토리

| 레포 | 설명 |
|------|------|
| `infra` | 에이전트 Skills · Hooks · 템플릿 · 스크립트 |
| `vault` | 가이드 · 정책 · 리서치 · 의사결정 기록 |
| `ops` | 법무 · 기획 · 마케팅 팀 워크스페이스 |
| `.github` | 이슈/PR 템플릿 · 보안 정책 |
| `project-ASHD` | 영수증·보증서 관리 서비스 (OCR + LLM) |
| `project-ourfolio` | 증거 기반 포트폴리오 플랫폼 |

---

*Powered by Claude Code*
