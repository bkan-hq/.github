# BK-HQ

> AI-Powered 1인 사업 운영 체계

## 조직 구조

```
CEO (BK)
    ↓
Orchestrator (메인 에이전트)
    ├── 법무팀 — 정책 작성, 규정 준수 검사
    ├── 기획팀 — PRD, UX 분석, UI 설계
    ├── 마케팅팀 — 콘텐츠 제작, 실험 분석
    └── 개발팀 — 프론트엔드, 백엔드, QA
```

## 기술 스택

| 영역 | 기술 |
|------|------|
| **Web** | Next.js 14+, TypeScript strict, Tailwind CSS + shadcn/ui |
| **Backend** | FastAPI, Python 3.12+, uv |
| **BaaS** | Supabase (Auth, DB, Storage, Edge Functions) |
| **배포** | Vercel |
| **CI/CD** | GitHub Actions, Dependabot |
| **모니터링** | Sentry, Codecov |
| **협업** | Slack, GitHub Issues (라벨 기반 상태 머신) |

## 레포지토리

| 레포 | 용도 |
|------|------|
| `.github` | 조직 공용 설정 (이슈/PR 템플릿, 프로필) |
| `ops` | 운영 문서, 에이전트 Skills, 워크플로우 템플릿 |
| `project-ASHD` | 영수증/보증서 관리 서비스 (OCR+LLM) |

---

*Powered by Claude Code + MCP*
