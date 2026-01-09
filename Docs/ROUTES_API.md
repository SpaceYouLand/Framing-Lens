# Routes + API (MVP)

## Pages

- `/` — Landing
- `/s/new` — Create session
- `/s/[id]/prompt/[n]` — Answer prompts
- `/s/[id]/results` — Results (policy-dependent)
- `/r/[token]` — Shared view (link_view)
- `/p/[slug]` — Public view (public)

## API

- `POST /api/session`
- `POST /api/response`
- `POST /api/session/complete`
- `GET /api/session/[id]/results`
- `GET /api/share/[token]`
- `GET /api/public/[slug]`
