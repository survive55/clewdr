# Release Notes

## Unreleased

- Removed database persistence support and related storage APIs; configuration now always saves to `clewdr.toml`.
- Dropped Gemini AI Studio and Vertex AI routes, providers, and credentials management from the backend.
- Simplified the frontend by removing Gemini tabs, key/vertex upload flows, and database storage controls.
- Updated documentation to reflect the Claude-only focus going forward.
