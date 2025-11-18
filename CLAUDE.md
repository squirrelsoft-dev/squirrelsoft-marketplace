# CLAUDE.md

This file provides guidance to Claude Code (claude.ai/code) when working with code in this repository.

## Repository Purpose

This is a **Claude Code marketplace repository** - a curated collection/registry of plugins, skills, and agents. It is NOT a traditional application codebase. The repository serves as:

- A catalog of available Claude Code plugins
- Installation instructions for end users
- Community contribution guidelines for plugin authors

## Repository Structure

- `.claude-plugin/marketplace.json` - Core marketplace configuration file defining available plugins
- `README.md` - User-facing catalog with installation instructions
- `CONTRIBUTING.md` - Guidelines for adding new plugins to the marketplace

## Adding a New Plugin to the Marketplace

When adding a plugin, you must update TWO files:

### 1. Update `.claude-plugin/marketplace.json`

Add a new entry to the `plugins` array:

```json
{
  "name": "plugin-name",
  "version": "1.0.0",
  "description": "Brief description",
  "source": {
    "source": "github",
    "repo": "owner/repo-name"
  },
  "category": "development",
  "tags": ["tag1", "tag2"]
}
```

**Important schema requirements:**
- Marketplace `name` must be kebab-case (no spaces)
- Marketplace `owner` field is required and must be an object with:
  - `name` (required): Owner's name
  - `email` (required): Contact email
  - `url` (optional): GitHub profile or website URL
- Plugin `name` must be kebab-case (no spaces)
- Plugin `id` field is NOT allowed (use `name` instead)

### 2. Update `README.md`

Add a new section under "## Available Plugins" following the established format:

```markdown
### Plugin Name
Brief description of what the plugin does.
```bash
/plugin install plugin-name@owner
```

**Includes:**
- Feature 1
- Feature 2

[View on GitHub](https://github.com/owner/plugin-name)

---
```

## Plugin Requirements

Plugins added to this marketplace must:
- Be valid Claude Code plugins with their own repositories
- Have clear documentation in their source repository
- Follow Claude Code plugin best practices
- Be properly licensed
- Not duplicate existing functionality

## Common Tasks

**Add a new plugin:**
1. Verify the plugin meets requirements
2. Update `.claude-plugin/marketplace.json`
3. Update `README.md` in the "Available Plugins" section
4. Ensure both entries have matching names and information

**Move a plugin from "Coming Soon" to "Available":**
1. Add full entry to `.claude-plugin/marketplace.json`
2. Move from "Coming Soon" to "Available Plugins" in README.md with complete details
3. Remove the "Coming Soon" entry

**Update plugin version:**
- Update the `version` field in `.claude-plugin/marketplace.json`
- No change needed in README.md unless installation instructions change

**Note:** Both files must be kept in sync - plugin `name` in marketplace.json should match the installation command format in README.md
