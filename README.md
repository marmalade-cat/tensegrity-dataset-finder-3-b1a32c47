Tensegrity Dataset Finder — prototype

A tiny single-file prototype (index.html) that accepts pasted article HTML/text, extracts URLs, tries to fetch each URL, and validates CSV/JSON files. It reports URL, MIME type, SHA-256 checksum, and a brief schema summary.

Usage:
- Open index.html in a browser (allows network fetches).
- Paste the article HTML or text into the box and click "Scan".
- The tool will list found links and attempt to fetch and validate CSV/JSON resources.

Limitations: Prototype only. Fetches require network access from your browser. No server component. Treat as untested: small codebase for exploration.