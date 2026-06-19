### Jitan Gupta

AI adoption practitioner. Building agent-safety tooling and Claude Code workflows. 10 years platform engineering background.

**Current focus:**
- AI agent safety and guardrails (file-safety-guard, MCP tooling)
- Claude Code workflows and the Cowork ecosystem
- Teaching engineers practical AI adoption - YouTube (@jitangupta) and team workshops

---

### Featured Projects

#### [PromptMate](https://github.com/jitangupta/PromptMate) — [Chrome Web Store](https://chromewebstore.google.com/detail/promptmate/oknglgpcglngpaobpjndcaaljdchmgai)
Chrome extension that injects a prompt-management sidebar into ChatGPT, Claude, DeepSeek, and Kimi. Compose prompts from a reusable body with tone and output format presets, then insert in one click — no backend server. Tested with an [agent-operated QA harness](https://github.com/jitangupta/promptmate-agent-qa-harness) across all four platforms.

`JavaScript` `Chrome Extension` `Google Drive API`

#### [Agent QA Harness](https://github.com/jitangupta/agent-qa-harness)
File-based QA harness that lets AI agents test any project in real browser sessions — no test code required. The agent reads a structured runbook, asks 6 questions about your product, generates test cases, runs them, and delivers a development handoff with bugs and UX observations. The [PromptMate Agent QA Harness](https://github.com/jitangupta/promptmate-agent-qa-harness) — 86 test cases across 18 categories — is the worked example in production use.

`Claude Code` `Codex` `Agent QA` `Browser Testing`

#### [File Safety Guard](https://github.com/jitangupta/file-safety-guard)
Plugin for Claude Code and Cowork that prevents accidental file deletion, overwrites, and destructive operations. Adds automatic timestamped backups, dry-run planning with approval gates, activity logging, and bulk operation approval — so AI agents can't silently destroy your files.

`Claude Code Plugin` `Cowork` `Agent Safety`

#### [Content Board](https://github.com/jitangupta/content-board)
Personal YouTube content management app that tracks video ideas through a 9-stage lifecycle — from Draft to Published. Features drag-and-drop reordering, production planning, learning capture, feedback collection, and PWA support. Built entirely with [Claude Code](https://docs.anthropic.com/en/docs/claude-code) as a demonstration of AI-assisted engineering with strict architecture and type safety.

`React 19` `TypeScript` `Firebase` `Tailwind CSS 4` `PWA` `Claude Code`

#### [Cowork Boilerplate](https://github.com/jitangupta/cowork-boilerplate)
A folder-based workflow engine for Claude Cowork — define your process once in config and instruction files, then run it on demand or on schedule. Works for content pipelines, research workflows, report generation, and any repeatable process. Includes battle-tested examples for YouTube content production and daily community scouting.

`Claude Cowork` `Workflow Automation` `CLAUDE.md`

#### [AI Release Orchestration](https://github.com/jitangupta/ai-release-orchestration)
Intelligent recommendation engine that uses **RAG and probabilistic reasoning** to determine which tenants in a multi-tenant SaaS platform should upgrade to a new release. Analyzes release content against tenant profiles and generates per-tenant recommendations (MUST / SHOULD / SKIP) with auditable reasoning.

`C#` `.NET 8` `Azure OpenAI` `Qdrant` `Docker` `RAG`

---

📫 [jitangupta.com](https://jitangupta.com) | YouTube [@jitangupta](https://youtube.com/@jitangupta) | LinkedIn [in/jitangupta](https://linkedin.com/in/jitangupta)
