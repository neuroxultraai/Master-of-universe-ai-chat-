# AI Doctor (HealthGPT)

**ID:** ai_doctor

**Priority:** High

**Summary:**
Symptom checker, diet guidance, mental-health chat (triage only; no definitive diagnosis).

**Required assets / libraries:**

- Medical QA prompts
- disclaimer UI
- emergency contact flow

**Suggested Implementation Notes:**

- UI: create a dedicated page in `client/pages/{feat['id']}.js`.
- Server: add endpoint `/api/{feat['id']}` to `server/server.js`.
- Env: add any required keys to `server/.env`.

**Example image:** images/ai_doctor.svg
