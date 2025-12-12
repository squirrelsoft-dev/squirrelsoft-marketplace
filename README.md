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

### Infinite Memory
Semantic memory system for Claude Code with persistent context retention through vector embeddings and intelligent retrieval.
```bash
/plugin install infinite-memory@squirrelsoft-dev
```

**Includes:**
- 5 commands (/index-project, /search, /status, /index-file, /re-index)
- Auto-index hook for save events
- Semantic search skill with auto-activation
- 3 MCP tools (index_project, query_memory, index_file)

**Features:**
- Semantic code search with natural language
- Fast indexing (1,500+ files/second)
- Local-first architecture (complete privacy)
- Vector database powered by Pixeltable
- Incremental updates with hash-based change detection
- High search quality (98% relevance)

**Requirements:**
- Python ≥3.11
- 4GB RAM minimum (8GB recommended)
- 500MB disk space + ~2KB per file

**Status:** 0.1.6-alpha (Alpha release - ready for testing)

[View on GitHub](https://github.com/squirrelsoft-dev/infinite-memory)

---

### Agency
Comprehensive workflow automation toolkit for the complete software development lifecycle. Includes 51+ specialized agents, composable workflow commands, and intelligent orchestration for requirements gathering, planning, implementation, testing, and deployment.
```bash
/plugin install agency@squirrelsoft-dev
```

**Includes:**
- 51+ specialized agents across 8 domains (design, engineering, product, marketing, testing, support, project management, spatial computing)
- 13 workflow commands (/work, /plan, /implement, /review, /test, /sprint, /refactor, /optimize, /document, /security, /adr, /deploy, /help)
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

**Status:** 0.2.1

[View on GitHub](https://github.com/squirrelsoft-dev/agency)

---

## Coming Soon

- **Supabase Patterns** - Reusable auth, RLS, and repository patterns
- **Component Registry** - shadcn-style component installation

## About

Built by [Squirrelsoft](https://squirrel.software) | Tools at [squirrelsoft.dev](https://squirrelsoft.dev)