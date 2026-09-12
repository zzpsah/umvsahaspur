# Decisions

## 2026-09-13 — Adopt DevOS portable project memory
- Add repository-local `.ai/` context even while the application tree is empty.
- Do not automatically restore deleted application files.
- Use Git history plus explicit user intent before reconstructing prior project content.
- Automatically refresh repository-derived context on pushes to `main`/`master`.
