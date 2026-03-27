# Changelog

## v6c · Current Release

- Fixed critical re-render bug: `insertBefore` DOM error when using manual factor override
- Rewrote `renderGraph` to full-clear-and-redraw on every call, eliminating all D3 enter/merge/exit state pollution
- Fixed `updateThemeColors` link label selector to match new DOM structure
- Added embedded copyright watermark
- Full code review pass — 20 checks passed

## v6 · Bilingual

- Full i18n system: Chinese / English UI with browser language auto-detection
- Manual language toggle with localStorage persistence
- AI prompt language now follows UI language — Chinese interface produces Chinese node names
- New three-line header design with tagline
- Example buttons updated

## v5

- Unified file import: TXT / PDF / MD / HTML, drag & drop supported
- Activity log system (AppLog) with API usage statistics
- Report titles now incorporate content keywords
- Manual factor override: inject keywords as forced graph nodes, re-analyze with constraints

## v3–v4

- Removed base64 PNG snapshot from report generation
- Fixed report file size bloat (500KB → ~30KB)

## v0–v2

- Initial concept and D3.js force-directed graph rendering
- Basic LLM API integration (online + Ollama local)
- Dual theme (dark / light)
- Report generation
