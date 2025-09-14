# AI Coding Assistant

**ID:** ai_coding_assistant

**Priority:** High

**Summary:**
Code generation, debugging, in-browser runner, project scaffolding.

**Required assets / libraries:**

- Code editor
- sandboxed runner
- AI code endpoints

**Suggested Implementation Notes:**

- UI: create a dedicated page in `client/pages/{feat['id']}.js`.
- Server: add endpoint `/api/{feat['id']}` to `server/server.js`.
- Env: add any required keys to `server/.env`.

**Example image:** images/ai_coding_assistant.svg
