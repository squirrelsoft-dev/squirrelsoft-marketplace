# Squirrelsoft Dev Tools Marketplace

Curated collection of development tools, skills, and agents for Claude Code.

## Installation
```bash
/plugin marketplace add squirrelsoft-dev/squirrelsoft-marketplace
```

## Available Plugins

### Claude Builder
Meta-tool for building Claude Code plugins, skills, and agents.
```bash
/plugin install claude-builder@squirrelsoft-dev
```

**Includes:**
- 5 core generator skills
- 4 quick-access commands
- 2 validation agents
- Template library

[View on GitHub](https://github.com/squirrelsoft-dev/claude-builder)

---

### Doc Fetcher
Fetches, caches, and versions documentation from web sources to provide accurate, version-specific context for AI coding agents.
```bash
/plugin install doc-fetcher@squirrelsoft-dev
```

**Includes:**
- Web documentation crawler
- Version-aware caching
- Context management for AI agents
- Documentation search and retrieval

[View on GitHub](https://github.com/squirrelsoft-dev/doc-fetcher)

---

### Infinite Memory
Semantic memory system for Claude Code with persistent context retention through vector embeddings.
```bash
/plugin install infinite-memory@squirrelsoft-dev
```

**Includes:**
- 5 commands for indexing and searching (index-project, search, status, index-file, re-index)
- Auto-index hook for save events
- Semantic search skill with auto-activation
- Vector database powered by Pixeltable
- Model Context Protocol (MCP) integration

**Requirements:**
- Python ≥3.11
- Minimum 4GB RAM (8GB recommended)
- 500MB disk space

[View on GitHub](https://github.com/squirrelsoft-dev/infinite-memory)

---

## Coming Soon

- **Supabase Patterns** - Reusable auth, RLS, and repository patterns
- **Component Registry** - shadcn-style component installation

## About

Built by [Squirrelsoft](https://squirrel.software) | Tools at [squirrelsoft.dev](https://squirrelsoft.dev)