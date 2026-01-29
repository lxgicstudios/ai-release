# ai-release

[![npm version](https://img.shields.io/npm/v/%40lxgicstudios%2Fai-release.svg)](https://www.npmjs.com/package/@lxgicstudios/ai-release)
[![npm downloads](https://img.shields.io/npm/dm/%40lxgicstudios%2Fai-release.svg)](https://www.npmjs.com/package/@lxgicstudios/ai-release)
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)


Automatic semantic versioning, release notes, and git tags. Reads your commits and figures out the rest.

## Install

```bash
npm install -g ai-release
```

## Usage

```bash
npx ai-release
# → minor bump: v1.2.0 → v1.3.0
# → Creates annotated tag with release notes

npx ai-release --dry-run
# → Preview the bump and notes without tagging

npx ai-release --no-tag
# → Generate notes without creating a git tag
```

## Setup

```bash
export OPENAI_API_KEY=sk-...
```

## License

MIT
