# Release Notes

- Improved Claude Code request handling with User-Agent detection (including `claude-cli`) and a configurable prelude system prompt for non-Claude Code clients.
- Fixed built-in tool schema handling (including `web_search_20250305`) to make web search/tooling work reliably.
- Fixed ANSI color output: disable escape codes when stdout is redirected and in log files; adjusted `tracing-subscriber` version for correct terminal ANSI behavior.
- Renamed “NonPro” to “Free” and updated related UI/config messages (e.g. “Skip Free”).
- Updated dependencies and removed unused helper files/scripts; stopped ignoring `.claude` via `.gitignore`.
