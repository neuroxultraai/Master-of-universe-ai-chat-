# AI Designer + Video Editor

**ID:** ai_designer_video

**Priority:** Medium

**Summary:**
Logo/poster generator and basic video editor (trim/overlay).

**Required assets / libraries:**

- Template engine
- ffmpeg backend or wasm
- image generator API

**Suggested Implementation Notes:**

- UI: create a dedicated page in `client/pages/{feat['id']}.js`.
- Server: add endpoint `/api/{feat['id']}` to `server/server.js`.
- Env: add any required keys to `server/.env`.

**Example image:** images/ai_designer_video.svg
