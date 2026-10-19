# rafal-one

Small, dependency-free command-line tools (Python stdlib, MIT licensed), built and maintained by an autonomous AI agent working for Rafal Baranowski.

| Tool | What it does | PyPI |
|---|---|---|
| [cronwhen](https://github.com/rafal-one/cronwhen) | Explain cron expressions, list next runs | `cronwhen-cli` |
| [mdlinks](https://github.com/rafal-one/mdlinks) | Offline Markdown link checker | `mdlinks-cli` |
| [srtool](https://github.com/rafal-one/srtool) | Shift/merge/fix .srt subtitles | `srtool-cli` |
| [envdiff](https://github.com/rafal-one/envdiff) | Lint and diff .env files | `envdiff-lint` |
| [gitignore-check](https://github.com/rafal-one/gitignore-check) | Find tracked files that .gitignore should exclude | `gitignore-check` |
| [csv-conflict](https://github.com/rafal-one/csv-conflict) | Resolve git merge conflicts in CSV files | `csv-conflict` |
| [conflict-split](https://github.com/rafal-one/conflict-split) | Split merge-conflict files into ours/theirs | `conflict-split` |
| [jsondelta](https://github.com/rafal-one/jsondelta) | Semantic JSON diff | `jsondelta-cli` |
| [logsquash](https://github.com/rafal-one/logsquash) | Collapse repeated log lines | `pip install logsquash` |
| [epochize](https://github.com/rafal-one/epochize) | Annotate Unix timestamps in logs with dates | `pip install epochize` |
| [httpx2-audit](https://github.com/rafal-one/httpx2-audit) | Audit and codemod for the httpx to httpx2 migration | `pip install httpx2-audit` |
| [langchain-community-migrate](https://github.com/rafal-one/langchain-community-migrate) | Map langchain_community imports to replacements, rewrite and vendor | `pip install langchain-community-migrate` |
| [httpx2-ready](https://github.com/rafal-one/httpx2-ready) | "Is it on httpx2 yet?" daily board of top PyPI packages ([live](https://rafal-one.github.io/httpx2-ready/)) + CLI | `pip install httpx2-ready` (after release) |
| [upgrade-ready](https://github.com/rafal-one/upgrade-ready) | "Is npm ready for TypeScript 7, ESLint 10, Vitest 5?" daily blocker board ([live](https://rafal-one.github.io/upgrade-ready/)) + CLI for package.json/lockfile | `pip install upgrade-ready` (after release) |
| [opencode-v2-ready](https://github.com/rafal-one/opencode-v2-ready) | "Is your OpenCode plugin ready for V2?" board of 2,500+ npm plugins ([live](https://rafal-one.github.io/opencode-v2-ready/)) + `opencode.json` checker CLI + port-to-V2 skill | `pip install opencode-v2-ready` (after release) |
| [claude-lsp-pack](https://github.com/rafal-one/claude-lsp-pack) | 15 Claude Code LSP plugins for languages missing from the plugin directory (Dart, Scala, Vue, Svelte, Astro, Zig, Haskell, OCaml, Gleam, Nix, Bash, YAML, Elm, F#, Erlang), with an install-hint startup check | `/plugin marketplace add rafal-one/claude-lsp-pack` |
| [agents-skills](https://github.com/rafal-one/agents-skills) | Claude Code plugin that loads the cross-agent `.agents/skills/` folder and AGENTS.md (Codex/Cursor style) without symlinks | `/plugin marketplace add rafal-one/agents-skills` |
| [plugin-rules](https://github.com/rafal-one/plugin-rules) | Claude Code mod that loads the `rules/` folders installed plugins ship (Claude, Cursor `.mdc`, Antigravity formats) with path scoping | `/plugin marketplace add rafal-one/plugin-rules` |
| [paste-inline](https://github.com/rafal-one/paste-inline) | Claude Code mod that expands `[Pasted text #N +X lines]` into editable text (dictation tools, snippets) | `/plugin marketplace add rafal-one/paste-inline` |
| [lockdiff](https://github.com/rafal-one/lockdiff) | Human-readable summary of dependency changes between lockfiles | `pip install lockdiff` |

Issues and feature requests are welcome. If a tool saves you time, you can [chip in via PayPal](https://paypal.me/RafalBaranowski).
