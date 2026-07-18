# Squirrelsoft Dev Tools Marketplace

Curated collection of development tools, skills, and agents for Claude Code.

## Installation
```bash
/plugin marketplace add squirrelsoft-dev/squirrelsoft-marketplace
```

## Available Plugins

### Claude Builder
Meta-development toolkit for creating Skills, Subagents, Hooks, Commands, and Plugins. Accelerates Claude Code extensibility development with intelligent generators and templates.
```bash
/plugin install claude-builder@squirrelsoft-dev
```

**Includes:**
- 5 core generator skills (skill-generator, plugin-scaffolder, subagent-generator, hook-generator, extensibility-advisor)
- 4 quick-access commands (/new-skill, /new-plugin, /new-agent, /new-hook)
- 2 validation agents (yaml-validator, structure-checker)
- Template library with 12+ examples

[View on GitHub](https://github.com/squirrelsoft-dev/claude-builder)

---

### Doc Fetcher
Fetch, cache, and version documentation from web sources to provide accurate, version-specific context for AI coding agents.
```bash
/plugin install doc-fetcher@squirrelsoft-dev
```

**Includes:**
- 5 core skills (doc-fetcher, doc-indexer, llms-txt-finder, doc-skill-generator, dependency-detector)
- 5 commands (/fetch-docs, /update-docs, /list-docs, /generate-skill, /config)
- 1 orchestration agent (doc-crawler)
- AI-first documentation detection (llms.txt, claude.txt)
- Smart crawling with robots.txt compliance
- Enhanced error recovery with checkpoint/resume
- Version management and incremental updates

**Features:**
- Global cache architecture (~/.claude/docs/)
- Auto-detects documentation frameworks
- Generates version-specific skills
- Offline-ready documentation
- Incremental updates (95%+ bandwidth savings)

[View on GitHub](https://github.com/squirrelsoft-dev/doc-fetcher)

---

### Agency
Comprehensive workflow automation toolkit for the complete software development lifecycle. Includes 51+ specialized agents, composable workflow commands, and intelligent orchestration for requirements gathering, planning, implementation, testing, and deployment.
```bash
/plugin install agency@squirrelsoft-dev
```

**Includes:**
- 51+ specialized agents across 8 domains (design, engineering, product, marketing, testing, support, project management, spatial computing)
- 15 workflow commands (/work, /plan, /implement, /review, /test, /sprint, /worktree, /refactor, /optimize, /document, /security, /adr, /deploy, /triage, /help)
- Orchestrator agent for intelligent task coordination
- Event-driven automation hooks

**Features:**
- End-to-end development lifecycle automation
- GitHub and Jira integration
- Specialized agents for frontend, backend, AI/ML, DevOps, mobile, and spatial computing
- Design system specialists (UI, UX, brand, visual storytelling)
- Marketing and growth automation (social media, content, SEO, app store)
- Testing and quality assurance automation
- Project management and sprint planning
- Architecture decision records (ADR) workflow

**Status:** 0.2.3

[View on GitHub](https://github.com/squirrelsoft-dev/agency)

---

### X Twitter Scraper
Xquik agent skill and plugin bundle with 126 REST operations, 118 MCP operations through 2 tools, SDKs, webhooks, exports, and approved X workflows.
```bash
/plugin install x-twitter-scraper@squirrelsoft-dev
```

**Includes:**
- X post search, account lookup, timelines, and exports
- REST API, MCP server, SDKs, webhooks, and monitoring
- Confirmation gates for private reads and write actions

**Status:** 2.5.3

[View on GitHub](https://github.com/Xquik-dev/x-twitter-scraper)

Xquik is an independent third-party service. Not affiliated with X Corp. "Twitter" and "X" are trademarks of X Corp.

---

## Coming Soon

- **Supabase Patterns** - Reusable auth, RLS, and repository patterns
- **Component Registry** - shadcn-style component installation

## About

Built by [Squirrelsoft](https://squirrel.software) | Tools at [squirrelsoft.dev](https://squirrelsoft.dev)
