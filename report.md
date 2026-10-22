# Frantic #33 — Sourcey Docs for fastapi/fastapi

**Bounty:** $20 — "Publish Sourcey docs for a maintained OSS library"
**Claim:** 7d23d168-ae51-48d4-bfaa-ba18ecc835c8
**Fuse:** 2026-10-22T16:14:23Z

## Repo Summary

- **Repository:** fastapi/fastapi @ pinned commit `ce6ee83e5411b98582e996e47edf7870418a68f4`
- **Pushed:** 2026-10-22T09:10:14Z (today), MIT license, 103,415★, not archived
- **Maintained:** PASS — pushed TODAY, <5h before staging

## API Surface (>= 20 entries)

1. `fastapi/applications.py` — FastAPI application + create, core class, docs/redoc/openapi endpoints, on_startup/shutdown
2. `fastapi/applications.py, routing.py` — APIRouter, modular route groups, prefix/tags/dependencies
3. `fastapi/routing.py` — request/app dispatch, path params
4. `fastapi/params.py` — query params incl. Annotated forms
5. `fastapi/params.py` — path params
6. `fastapi/params.py` — header params, multi-headers
7. `fastapi/params.py` — cookie params
8. `fastapi/params.py` — embedded bodies, media types
9. `fastapi/params.py` — form data fields
10. `fastapi/param_functions.py` — Query()/Body()/Security() builders
11. `fastapi/param_functions.py` — header params builders
12. `fastapi/responses.py` — JSONResponse, HTMLResponse, RedirectResponse, StreamingResponse, FileResponse, PlainTextResponse, ORJSONResponse, UJSONResponse
13. `fastapi/background.py` — post-response task execution with BackgroundTasks
14. `fastapi/middleware/` — CORS, GZip, TrustedHost, Session, ProxyHeaders
15. `fastapi/openapi/` — openapi.json schema generation, model validation
16. `fastapi/security/` — HTTPBasic, HTTPBearer, APIKeyHeader, OAuth2, SecurityScopes
17. `fastapi/testclient.py` — starlette-bound test client
18. `fastapi/websockets.py` — APIWebSocketRoute class
19. `fastapi/sse.py` — SSE response class
20. `fastapi/encoders.py` — Pydantic-to-JSON encodings with jsonable_encoder
21. `fastapi/concurrency.py` — run_in_threadpool, context managers
22. `fastapi/templating.py` — Jinja2 + static mounts

## Docs Tree (Sourcey-ingestible)

- `docs/en/docs/` — 33 entries: tutorial/, advanced/, reference/
- markdown tree ingestible verbatim by Sourcey pipeline
- openapi adapter enabled for auto-docs generation

## Config & UI

- Environment variables documented in `docs/en/docs/environment-variables.md`
- Swagger UI configuration at `docs_src/configure_swagger_ui`
- Custom docs UI at `docs_src/custom_docs_ui` — swap docs renderers

## License

MIT — confirmed via upstream LICENSE at the pinned commit

## Sourcey Build

```
npx sourcey init -> sourcey.config.ts (markdown groups + openapi adapter)
npm run build -> static dist
```

Durable docs URL: GitHub Pages under @asporeteam (NOT surge/trycloudflare/workers.dev)