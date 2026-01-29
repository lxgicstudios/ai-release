---
name: release-gen
description: Automatic semantic versioning and git tags. Use when releasing versions.
---

# Release Generator

Versioning by hand is error-prone. This tool reads your commits, determines the right version bump, and creates annotated tags.

**One command. Zero config. Just works.**

## Quick Start

```bash
npx ai-release
```

## What It Does

- Reads commits since last tag
- Determines semantic version bump
- Generates release notes
- Creates annotated git tag

## Usage Examples

```bash
# Create release
npx ai-release

# Preview without tagging
npx ai-release --dry-run

# Generate notes without tag
npx ai-release --no-tag
```

## Best Practices

- **Use conventional commits** - makes version detection accurate
- **Tag releases** - don't just bump package.json
- **Include release notes** - document what changed
- **Push tags** - git push --tags after release

## When to Use This

- Releasing new versions
- Automating version management
- Generating release notes
- Standardizing release process

## Part of the LXGIC Dev Toolkit

This is one of 110+ free developer tools built by LXGIC Studios. No paywalls, no sign-ups, no API keys on free tiers. Just tools that work.

**Find more:**
- GitHub: https://github.com/LXGIC-Studios
- Twitter: https://x.com/lxgicstudios
- Substack: https://lxgicstudios.substack.com
- Website: https://lxgicstudios.com

## Requirements

No install needed. Just run with npx. Node.js 18+ recommended. Needs OPENAI_API_KEY environment variable.

```bash
npx ai-release --help
```

## How It Works

Reads git history since the last tag, analyzes commit messages to determine if changes are breaking, features, or fixes. Then bumps version accordingly and creates an annotated tag with release notes.

## License

MIT. Free forever. Use it however you want.
