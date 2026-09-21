# example-app documentation

Citeable product and architecture notes for the private RealWorld / Conduit demo pair:

- [12masta/example-app-frontend](https://github.com/12masta/example-app-frontend)
- [12masta/example-app-backend](https://github.com/12masta/example-app-backend)

This repository is **extra context** for QA Brief. It is not a runnable dispatch target. Do not add it to the Hub allowlist.

## Contents

| Path | What a Brief should use it for |
| --- | --- |
| [frontend/purpose.md](frontend/purpose.md) | Why the SPA exists |
| [frontend/architecture.md](frontend/architecture.md) | Page-scoped routes and React Query |
| [frontend/auth.md](frontend/auth.md) | JWT session restore in the browser |
| [frontend/flows.md](frontend/flows.md) | Feed, article, editor, follow, favorite, settings |
| [frontend/test-seams.md](frontend/test-seams.md) | Jest and Testing Library seams |
| [backend/purpose.md](backend/purpose.md) | Why the API exists |
| [backend/architecture.md](backend/architecture.md) | ASP.NET API shape |
| [backend/auth.md](backend/auth.md) | JWT issuance and validation |
| [backend/flows.md](backend/flows.md) | Articles, comments, profiles, favorites |
| [backend/test-seams.md](backend/test-seams.md) | Backend test seams |
| [product/favorites.md](product/favorites.md) | Opinionated favorite policy that is not a RealWorld default |
