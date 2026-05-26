# Changelog

All notable changes to OpenBlue are documented in this file. The format is
based on [Keep a Changelog](https://keepachangelog.com/en/1.1.0/), and this
project adheres to [Semantic Versioning](https://semver.org/spec/v2.0.0.html).

---

## [0.1.1] — 2026-05

### Added

- Native VS Code Language Model Chat provider exposing every local model
  loaded in LM Studio or pulled into Ollama.
- `@openblue` chat participant for direct conversations with local models.
- Claude Code routing: map Haiku / Sonnet / Opus roles to local model IDs.
- Inline completions (FIM) with configurable debounce, temperature, and
  context window.
- Status-bar polar bear with live backend health indicators.
- Symmetric model management for both backends: download, load, unload,
  list loaded, list available, delete.
- Live Hugging Face GGUF browser (LM Studio) and Ollama registry browser.
- MCP server configuration with cross-backend tool-call translation.
- Optional `web_search` / `web_fetch` tools (Ollama) and ephemeral MCP
  integrations (LM Studio).
- Auto-detection of LM Studio Hub and Ollama Cloud sign-in state.
- Auto-spawning of LM Studio instances per model (configurable cap).
- Diagnostic output channel with full request/response logging.
- Command "Repair Claude Code ServiceWorker" for recovery from stuck SW.

### Compatibility

- Requires VS Code 1.104.0 or newer.
- Supports LM Studio 0.3.0+ and Ollama 0.1.30+.
- Verified on Windows 10/11, macOS 12+, and Ubuntu 22.04+.

### Known Limitations

- llama.cpp server and vLLM endpoints not yet supported (roadmap).
- JetBrains IDEs not supported (different extension architecture).
- Tool-call quality varies by model — pick agentic/function-calling tags
  for best results.

---

## [0.1.0] — 2026-04

### Added

- Initial private release.
- Core backend managers for LM Studio and Ollama.
- Connection webview and per-backend configuration.
- Basic Claude Code env-var routing.
